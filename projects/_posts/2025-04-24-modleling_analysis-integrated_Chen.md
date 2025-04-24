---
layout: project
title: Integrated Process-System Modeling and Performance Analysis for Serial Production Lines
contributors: [Chen]
Lab contributors: [Chen]
handle: REMS-PM
status: collection
category: projects
#type: manufacturing
domain: modeling and analysis
system_type: integrated

# Optional
paper website: [https://ieeexplore.ieee.org/document/9794392]
website: [https://ieeexplore.ieee.org/document/9794392]
grant:
grant_url:
image: /assets/images/projects/Manufacturing/modeling_analysis/modeling_integrated.png
tagline: Leveraging the sensor data, develop a novel process-system integrated data-enabled math model to incorporate process-level and system-level dynamics seamlessly, and a fast recursive algorithm to quickly evaluate both quality and quantity performance. \
  Develop a data-enabled analytical method to identify the real-time permanent production loss (PPL) efficiently.\
  Develop a PPL attribution method to identify the root cause and the problematic machines that are most responsible for production loss in a real-time fashion.
tags: []


# Data and code
github: 
neurovault:
openneuro:
figshare:
figshare_names:
osf:
---
{% assign integrated_projects = site.pages | where: "category", "projects" | where: "domain", "modeling and analysis" | where: "system_type", "integrated" %}


{% include JB/setup %}

The performance of a smart manufacturing system is affected by not only the constituent processes but also their system-level interactions. 
However, in most current studies, individual process modeling and system-level performance evaluation are independent. This can substantially impact production efficiency. 
In this project, utilizing available sensor data, an integrated data-enabled model is developed to seamlessly fuse two conventionally separated system-level and process-level models and analysis. 
A fast recursive method is developed to evaluate the system yield. 
The permanent production loss (PPL) concept is defined and evaluated based on the proposed integrated model. 
Furthermore, PPL attributions due to random downtime and quality issues have been identified. 
Case studies have shown that the integrated model is of high fidelity, and the PPL analysis can effectively identify the root cause of production yield loss.


