---
layout: project
title: Multi-agent reinforcement learning for integrated manufacturing system-process control
contributors: [Chen]
Lab contributors: [Chen]
handle: REMS-PM
status: collection
category: projects
#type: manufacturing
domain: control
system_type: integrated

# Optional
paper website: [https://www.sciencedirect.com/science/article/pii/S0278612524001845]
website: [https://www.sciencedirect.com/science/article/pii/S0278612524001845]
grant:
grant_url:
image: /assets/images/projects/Manufacturing/control/control_integrated.png
tagline: Develop a dynamic system-process integrated model.\
 Incorporate both system and process parameters into the model to effectively evaluate dynamics.\
 Establish a MARL-based control scheme for real-time process adjustments to optimize system yields.\
 Develop C-MAAC and P-MAAC MARL algorithms to enhance agent collaboration with system properties.\
 Demonstrate the great potential of the system-process integrated control in manufacturing industry.
tags: []


# Data and code
github: 
neurovault:
openneuro:
figshare:
figshare_names:
osf:
---
{% assign integrated_projects = site.pages | where: "category", "projects" | where: "domain", "control" | where: "system_type", "integrated" %}


{% include JB/setup %}

The increasing complexity, adaptability, and interconnections inherent in modern manufacturing systems have spurred a demand for integrated methodologies to boost productivity, improve quality, and streamline operations across the entire system. 
This project introduces a holistic system-process modeling and control approach, utilizing a Multi-Agent Reinforcement Learning (MARL) based integrated control scheme to optimize system yields. 
The key innovation of this work lies in integrating the theoretical development of manufacturing system-process property understanding with enhanced MARL-based control strategies, thereby improving system dynamics comprehension. 
This, in turn, enhances informed decision-making and contributes to overall efficiency improvements. In addition, we present two innovative MARL algorithms: the credit-assigned multi-agent actor-attention-critic (C-MAAC) and the physics-guided multi-agent actor-attention-critic (P-MAAC), each designed to capture the individual contributions of agents within the system. 
C-MAAC extracts global information via parallel-trained attention blocks, whereas P-MAAC embeds system dynamics through permanent production loss (PPL) attribution. 
Numerical experiments underscore the efficacy of our MARL-based control scheme, particularly highlighting the superior training and execution performance of C-MAAC and P-MAAC. Notably, P-MAAC achieves rapid convergence and exhibits remarkable robustness against environmental variations, validating the proposed approach’s practical relevance and effectiveness.

