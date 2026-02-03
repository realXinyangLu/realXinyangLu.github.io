---
title: "Action and trajectory planning for urban autonomous driving with hierarchical reinforcement learning"
collection: publications
category: _2023
permalink: /publication/2023-action
authors: '<b>Xinyang Lu</b>, Flint Xiaofeng Fan, Tianying Wang'
venue: "ICML workshop, 2023"
teaser: "/images/teasers/action.png"
paperurl: 'https://arxiv.org/abs/2306.15968'
bibtexurl: 'https://academicpages.github.io/files/action.bib'
---

Reinforcement Learning (RL) has made promising progress in planning and decision-making for Autonomous Vehicles (AVs) in simple driving scenarios. However, existing RL algorithms for AVs fail to learn critical driving skills in complex urban scenarios. First, urban driving scenarios require AVs to handle multiple driving tasks of which conventional RL algorithms are incapable. Second, the presence of other vehicles in urban scenarios results in a dynamically changing environment, which challenges RL algorithms to plan the action and trajectory of the AV. In this work, we propose an action and trajectory planner using Hierarchical Reinforcement Learning (atHRL) method, which models the agent behavior in a hierarchical model by using the mid-level perception of the lidar and birdeye view. The proposed atHRL method learns to make decisions about the agent’s future trajectory and computes target waypoints under continuous settings based on a hierarchical DDPG algorithm. The waypoints planned by the atHRL model are then sent to a low-level controller to generate the steering and throttle commands required for the vehicle maneuver. We empirically verify the efficacy of atHRL through extensive experiments in complex urban driving scenarios that compose multiple tasks with the presence of other vehicles in the CARLA simulator. The experimental results suggest a significant performance improvement compared to the state-of-the-art RL methods.
