---
title: "Combining Learning from Human Feedback and Knowledge Engineering to Solve Hierarchical Tasks in Minecraft"
collection: publications
permalink: /publication/2021-12-07-combing-learning-from-human-feedback
excerpt: ''
date: 2022-01-01
venue: 'AAAI-MAKE'
paperurl: 'https://arxiv.org/abs/2112.03482'
citation: 'Goecks, Vinicius G., et al. “Combining Learning from Human Feedback and Knowledge Engineering to Solve Hierarchical Tasks in Minecraft.” ArXiv:2112.03482 [Cs], Dec. 2021. arXiv.org, http://arxiv.org/abs/2112.03482.'
---

# Abstract
Real-world tasks of interest are generally poorly defined by human-readable descriptions and have no pre-defined reward signals unless it is defined by a human designer. Conversely, data-driven algorithms are often designed to solve a specific, narrowly defined, task with performance metrics that drives the agent's learning. In this work, we present the solution that won first place and was awarded the most human-like agent in the 2021 NeurIPS Competition MineRL BASALT Challenge: Learning from Human Feedback in Minecraft, which challenged participants to use human data to solve four tasks defined only by a natural language description and no reward function. Our approach uses the available human demonstration data to train an imitation learning policy for navigation and additional human feedback to train an image classifier. These modules, together with an estimated odometry map, are then combined into a state-machine designed based on human knowledge of the tasks that breaks them down in a natural hierarchy and controls which macro behavior the learning agent should follow at any instant. We compare this hybrid intelligence approach to both end-to-end machine learning and pure engineered solutions, which are then judged by human evaluators. Codebase is available at this [url](https://github.com/viniciusguigo/kairos_minerl_basalt). 
