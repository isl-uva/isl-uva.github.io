---
layout: project
title: From Nash Q-learning to nash-MADDPG Advancements in multiagent control for multiproduct flexible manufacturing systems
contributors: [Muhammad Waseem]
handle: nash-maddpg
status: collection
type: manufacturing

# Optional
website: [https://www.sciencedirect.com/science/article/pii/S0278612524000530]
grant: NSF
grant_url:
image: /assets/images/projects/nash_maddpg.png
tagline: An integrated multiagent RL and game theory approach for complex manufacturing systems
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

The emergence of flexible manufacturing systems (FMS) capable of processing multiple product types is a result of the growing demand for product customization and personalization. Such multiproduct systems are charac
terized by a higher level of uncertainty and variability when compared to traditional manufacturing systems. This paper proposes a Nash integrated multiagent deep deterministic policy gradient method (Nash-MADDPG) to 
control the mobile robots’ assignment in a multiproduct FMS to enable intelligent decision-making, interaction, and dynamic learning capabilities. A mathematical model of a multiproduct FMS from a previous study is 
described, and system dynamic property is characterized by permanent production loss (PPL). Then, by observing PPL of the system and market demand for each product type, the multi-agent control scheme is 
developed to assign mobile robots to load/unload various product types at various machines. First, a Nash game is developed among the mobile robots and to improve the cooperation, a collaboration cost is defined. This 
collaboration cost is then used in the reward function of the multiagent deep deterministic policy gradient (MADDPG) algorithm. Second, the actions are jointly defined based on the action values of MADDPG, and the 
mobile robots’ strategies in the Nash game, which update the environment to a new state. The performance of the proposed method is verified by comparing it with conventional Nash Q-learning, vanilla MADDPG, Q-learning based single agent reinforcement learning (SARL) and a first-come-first-serve (FCFS) based control. The results demonstrate that the multi-agent control scheme under the proposed Nash-MADDPG is effective in dealing with 
cooperative FMS environment that involves complicated dynamics and uncertainties.





