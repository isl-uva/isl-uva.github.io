---
layout: project
title: Data-Enabled Permanent Production Loss Analysis for Serial Production Systems with Variable Cycle Time Machines
contributors: [Chen,Jing]
Lab contributors: [Chen,Jing]
handle: REMS-PM
status: collection
category: projects
#type: manufacturing
domain: modeling and analysis
system_type: fsms

# Optional
paper website: [https://ieeexplore.ieee.org/document/9466325]
website: [https://ieeexplore.ieee.org/document/9466325]
grant:
grant_url:
image: /assets/images/projects/Manufacturing/modeling_analysis/analysis_variable_CycleTime.png
tagline: Based on the data-enabled model, this project propose an analytical analysis method to efficiently identify real-time permanent production loss (PPL) attributed to each machine, and evaluate their opportunity windows for such systems.
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

Real time production performance evaluation plays a vital role in diagnosing manufacturing system health status and achieving productivity improvements. 
However, most existing studies on system performance evaluation are based on steady state analysis and focused on the production system with fixed cycle time machines. 
The real-time performance evaluation for a manufacturing system with variable cycle time machines, although typical for a large number of realistic scenarios, has been mostly ignored. 
The development of smart manufacturing and increasingly available sensor data have provided unprecedented opportunities to carry out thorough analysis on the real-time performance of such complex systems. 
In this project, we developed a data-enabled methodology to efficiently identify and predict the real-time permanent production loss for a serial production line with variable cycle time machines. 
The concept and evaluation method of opportunity window are introduced to facilitate the permanent production loss estimation. 
Numerical case studies are presented to demonstrate the effectiveness of the proposed methods for opportunity window evaluation and production loss identification.


