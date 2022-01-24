---
title: "Accelerated Robot Learning via Human Brain Signals"
collection: publications
permalink: /publication/2020-05-31-accelerated-robot-learning
excerpt: ''
date: 2020-05-31
venue: 'ICRA'
paperurl: 'https://arxiv.org/pdf/1910.00682'
citation: 'I. Akinola et al., "Accelerated Robot Learning via Human Brain Signals," 2020 IEEE International Conference on Robotics and Automation (ICRA), 2020, pp. 3799-3805, doi: 10.1109/ICRA40945.2020.9196566.'
---

# Abstract
In reinforcement learning (RL), sparse rewards are a natural way to specify the task to be learned. However, most RL algorithms struggle to learn in this setting since the learning signal is mostly zeros. In contrast, humans are good at assessing and predicting the future consequences of actions and can serve as good reward/policy shapers to accelerate the robot learning process. Previous works have shown that the human brain generates an error-related signal, measurable using electroencephelography (EEG), when the human perceives the task being done erroneously. In this work, we propose a method that uses evaluative feedback obtained from human brain signals measured via scalp EEG to accelerate RL for robotic agents in sparse reward settings. As the robot learns the task, the EEG of a human observer watching the robot attempts is recorded and decoded into noisy error feedback signal. From this feedback, we use supervised learning to obtain a policy that subsequently augments the behavior policy and guides exploration in the early stages of RL. This bootstraps the RL learning process to enable learning from sparse reward. Using a simple robotic navigation task as a test bed, we show that our method achieves a stable obstacle-avoidance policy with high success rate, outperforming learning from sparse rewards only that struggles to achieve obstacle avoidance behavior or fails to advance to the goal.
