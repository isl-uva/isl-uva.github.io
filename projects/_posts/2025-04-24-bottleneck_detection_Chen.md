---
layout: project
title: Dynamic bottleneck identification and production loss evaluation for assembly lines
contributors: [Chen]
Lab contributors: [Chen]
handle: REMS-PM
status: collection
category: projects
#type: manufacturing
domain: modeling and analysis
system_type: fsms

# Optional
paper website: [https://www.sciencedirect.com/science/article/pii/S2213846323001463]
website: [https://www.sciencedirect.com/science/article/pii/S2213846323001463]
grant:
grant_url:
image: /assets/images/projects/Manufacturing/modeling_analysis/bottleneck_detection.png
tagline: Development of a robust and explainable data-enabled mathematical model that can evaluate the system performance of an assembly line with limited real-time sensor data.\
   Establishment of a dynamic bottleneck detection methodology based on the developed model and physical understanding of the highly stochastic system.\
   Further quantification of the production loss attributed to each bottleneck, providing a powerful tool for industrial engineers to quickly identify the bottleneck station that leads to the largest production loss and take action to eliminate the problem.
tags: []


# Data and code
github: 
neurovault:
openneuro:
figshare:
figshare_names:
osf:
---
{% assign fsms_projects = site.pages | where: "category", "projects" | where: "domain", "modeling and analysis" | where: "system_type", "fsms" %}


{% include JB/setup %}

Identifying bottlenecks is a crucial challenge for manufacturing firms in their quest to increase capacity. 
While many approaches have been proposed to address this issue, existing solutions still have limitations in dealing with highly dynamic, stochastic systems in modern smart manufacturing. 
Hence, identifying bottlenecks remains a complex task. 
To address these shortcomings, we propose a novel data-enabled mathematical model for evaluating the performance of assembly lines with limited sensor information. 
A dynamic bottleneck detection method is then developed based on this proposed model. 
Furthermore, the production loss caused by the detected bottleneck stations, referred to as the dynamic production loss (DPL), can be evaluated and attributed. 
Numerical case studies are presented to validate the accuracy of the data-enabled model and demonstrate the effectiveness of the bottleneck detection and DPL evaluation methods.


