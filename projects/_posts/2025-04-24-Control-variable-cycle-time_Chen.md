---
layout: project
title: Hybrid feedback and reinforcement learning-based control of machine cycle time for a multi-stage production system
contributors: [Chen]
Lab contributors: [Chen]
handle: REMS-PM
status: collection
category: projects
# type: manufacturing
domain: control
system_type: fsms

# Optional
paper website: [https://www.sciencedirect.com/science/article/abs/pii/S0278612522001698]
website: [https://www.sciencedirect.com/science/article/abs/pii/S0278612522001698]
grant:
grant_url:
image: /assets/images/projects/Manufacturing/control/control_variable_CycleTime.png
tagline: Establish a hybrid integrated control framework for machine cycle time and energy control. \
  Combine the strengths of both deep reinforcement learning (DRL) and feedback control.\
  Develop a DRL algorithm boosted by model-based value expansion for cycle time control. \
  Develop feedback control for energy saving using system property of opportunity window. \
  Demonstrate the great potential of hybrid integrated control in manufacturing industry.
tags: []


# Data and code
github: 
neurovault:
openneuro:
figshare:
figshare_names:
osf:
---
{% assign fsms_projects = site.pages | where: "category", "projects" | where: "domain", "control" | where: "system_type", "fsms" %}


{% include JB/setup %}

With the increasing need of flexible manufacturing systems, machine flexibility has become one of the major impact factors. 
An important aspect of machine flexibility is the ability to change an individual machine’s capacity (or cycle time) to improve the overall system efficiency. 
In this project, a novel control method is proposed for multi-stage production systems to dynamically change the individual machines’ cycle time to improve overall system efficiency. 
The proposed control method integrates distributed feedback control scheme and a Reinforcement Learning (RL) control scheme based on an extended actor-critic algorithm. 
The feedback control will determine whether a machine is turned on or off using real-time system status, while the RL control scheme will decide how to increase or decrease a machine’s cycle time when a machine is on. 
An improved actor-critic RL algorithm is developed to add an auxiliary model-based path to the standard model-free RL to enhance the learning performance. 
To demonstrate the effectiveness of the proposed method, numerical case studies have been performed that clearly show improvements in the overall profits and energy savings compared to other methods.



