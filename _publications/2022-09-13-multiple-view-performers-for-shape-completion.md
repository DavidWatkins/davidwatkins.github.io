---
title: "Multiple View Performers for Shape Completion"
collection: publications
permalink: /publication/2022-09-13-multiple-view-performers-for-shape-completion
excerpt: ''
date: 2022-09-13
venue: 'arXiv'
paperurl: 'https://arxiv.org/abs/2209.06291'
citation: 'Watkins, D., Allen, P., Choromanski, K., Varley, J., & Waytowich, N. (2022). Multiple View Performers for Shape Completion. arXiv preprint arXiv:2209.06291.'
---

# Abstract
We propose the Multiple View Performer (MVP) - a new architecture for 3D shape completion from a series of temporally sequential views. MVP accomplishes this task by using linear-attention Transformers called Performers. Our model allows the current observation of the scene to attend to the previous ones for more accurate infilling. The history of past observations is compressed via the compact associative memory approximating modern continuous Hopfield memory, but crucially of size independent from the history length. We compare our model with several baselines for shape completion over time, demonstrating the generalization gains that MVP provides. To the best of our knowledge, MVP is the first multiple view voxel reconstruction method that does not require registration of multiple depth views and the first causal Transformer based model for 3D shape completion.
