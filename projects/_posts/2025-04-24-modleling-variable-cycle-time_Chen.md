---
layout: project
title: Data-Enabled Real-Time Modeling for Production Systems with Variable Cycle Time
contributors: [Chen,Jing]
Lab contributors: [Chen,Jing]
handle: REMS-PM
status: collection
category: projects
#type: manufacturing
domain: modeling and analysis
system_type: fsms

# Optional
paper website: [https://www.sciencedirect.com/science/article/pii/S2351978921000664]
website: [https://www.sciencedirect.com/science/article/pii/S2351978921000664]
grant:
grant_url:
image: /assets/images/projects/modeling_variable_CycleTime.png
tagline: A data-enabled mathematical model in describing a production line with variable cycle time machines, in which machine and system constraints are ensured and the sensor data such as random machine downtimes are enabled as inputs.
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

Cycle time is one of the essential parameters that could lead to a significant improvement on the productivity of a manufacturing system. In the traditional manufacturing systems, cycle time for each station is recommended by the vendor and determined based on production line design and through repeated experiments and simulations. Once determined, the cycle time is typically unchangeable during the production operation. Nowadays, the development of smart manufacturing enables a flexible production operation, and the cycle time of each machine can be made changeable to quickly respond to market demand fluctuation and to further improve the system efficiency. 
To evaluate the performance of a serial production line with variable cycle time, a novel data-enabled manufacturing system model is developed, in which sensor data inputs are allowed and cycle times are modeled as input variables. 
In addition, an opportunity window concept, which has been studied in the previous study and has been treated as a real-time system status measurement, is extended to the variable cycle time scenario. 
Numerical case studies are presented to validate the fidelity of the data-enabled model and demonstrate the influence of variable cycle time of individual machines on the production line throughput and the opportunity windows.



