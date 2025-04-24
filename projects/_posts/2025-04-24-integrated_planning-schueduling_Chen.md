---
layout: project
title: Demand-driven hierarchical integrated planning-scheduling control for a mobile robot-operated flexible smart manufacturing system
contributors: [Chen, Kshitij, Muhammad]
Lab contributors: [Chen, Kshitij, Muhammad]
handle: REMS-PM
status: collection
category: projects
#type: manufacturing
domain: control
system_type: mobile

# Optional
paper website: [https://www.sciencedirect.com/science/article/abs/pii/S0736584525000699]
website: [https://www.sciencedirect.com/science/article/abs/pii/S0736584525000699]
grant:
grant_url:
image: /assets/images/projects/Manufacturing/control/planning-scheduling.png
tagline: Utilizes a comprehensive system identification model developed through behavioral cloning to incorporate system dynamic properties.\
 Introduces a demand-driven hierarchical integrated planning-scheduling control framework for FSMS based on the model. \
 The two interconnected feedback control loops, an outer planner loop and an inner scheduler loop, can synergistically generate integrated planning-scheduling policies.\
 Presents a novel P-MADDPG algorithm that leverages system properties to improve scheduling.
tags: []


# Data and code
github: 
neurovault:
openneuro:
figshare:
figshare_names:
osf:
---
{% assign integrated_projects = site.pages | where: "category", "projects" | where: "domain", "control" | where: "system_type", "mobile" %}


{% include JB/setup %}

The rapid advancement of Industry 4.0 has transformed manufacturing, giving rise to Flexible Smart Manufacturing Systems (FSMS) capable of adapting to fluctuating market demands and operational uncertainties—essential for achieving mass customization. 
However, conventional approaches that separate long-term planning from real-time scheduling struggle to meet the demands of modern manufacturing environments, particularly in adapting to frequent demand fluctuations, managing system complexity, and ensuring rapid responsiveness. 
To address this challenge, this paper presents a demand-driven hierarchical framework that integrates planning and scheduling for flexible smart manufacturing, enabled by a mobile, multi-skilled, robot-operated system. 
First, a novel system identification model is developed using behavioral cloning to extract essential system properties that inform decision-making. 
Next, a coupled dual-loop control structure is introduced: an outer planner loop optimizes robot configurations based on demand forecasts, while an inner scheduler loop dynamically adjusts robot assignments in response to unexpected disruptions. 
The control strategy leverages the System Property-Infused Multi-Agent Deep Deterministic Policy Gradient (P-MADDPG) algorithm, which integrates dynamic system properties to improve adaptability and decision-making in complex environments. 
Extensive experiments are carried out to demonstrate the framework's effectiveness in adapting to frequently shifting demands, minimizing resource waste, and achieving superior performance with higher throughput compared to existing approaches, thereby providing a robust solution for integrated planning and scheduling in personalized production.

