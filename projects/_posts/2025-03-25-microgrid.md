---
layout: project
title: Integrated Energy Optimization in Manufacturing Through Multiagent Deep Reinforcement Learning Holistic Control of Manufacturing, Microgrid Systems, and Battery Storage
contributors: Muhammad Waseem
handle: Microgrid_manufacturing
status: collection
type: sustainable_manufacturing

# Optional
website: https://asmedigitalcollection.asme.org/manufacturingscience/article/147/6/061003/1211186
grant: NSF
grant_url:
image: /assets/images/projects/microgrid.png
tagline: Integrated microgrid and manufacturing system with battery degradation control
tags: []

# Data and code
github: 
neurovault:
openneuro:
figshare:
figshare_names:
osf:
---
{% include JB/setup %}

Microgrid technology integrates storage devices, renewable energy sources, and controllable loads and has been widely explored in residential, commercial, and critical facilities. However, its potential in manufacturing remains largely underexplored, where optimal control of microgrids containing energy storage systems (ESS) is crucial. Two primary challenges arise in integrated microgrid-manufacturing systems: fluctuating renewable energy output and nondeterministic polynomial (NP)-hard demand-side control. Addressing both challenges simultaneously increases complexity. This article proposes an integrated control considering ESS degradation, optimizing control on both the manufacturing demand and microgrid energy supply sides within the production constraints. It formulates the problem in a decentralized partially observable Markov decision process (Dec-POMDP) framework, treating the system as a multiagent environment. The multiagent deep deterministic policy gradient (MADDPG) algorithm is adapted to optimize control policies. Investigating the trained policies provides insights into their logic, and a rule-based policy is introduced for practical implementation. Experimental validation on a manufacturing system validates the effectiveness of the proposed method and the rule-based policy.





