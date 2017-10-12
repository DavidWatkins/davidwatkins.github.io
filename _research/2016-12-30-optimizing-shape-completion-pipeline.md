---
title: "Optimizing the Shape Completion Pipeline"
collection: research
permalink: /research/2016-12-30-optimizing-shape-completion-pipeline
excerpt: 'Expanding on the work done by Jake Varley et al. for the Shape Completion Enabled Robotic Grasping[3], I performed a series of optimizations that would enhance the pipeline to increase is performance and its flexibility. The marching cubes algorithm  as been rewritten to support GPU operations, preliminary code as been written for completing entire scenes based on work done by Evan Shelhamer et al.[2], and written a headless depth renderer to help generate scenes for training data much faster than the current pipeline. These three contributions will prove to effectively push forward the shape completion project to a much more usable state for not only our lab but also any labs that may choose to use this software in the future.'
date: 2016-12-30
paperurl: '/files/2016_fall_OSCP.pdf'
--- 
Expanding on the work done by Jake Varley et al. for the Shape Completion Enabled Robotic Grasping[3], I performed a series of optimizations that would enhance the pipeline to increase is performance and its flexibility. The marching cubes algorithm  as been rewritten to support GPU operations, preliminary code as been written for completing entire scenes based on work done by Evan Shelhamer et al.[2], and written a headless depth renderer to help generate scenes for training data much faster than the current pipeline. These three contributions will prove to effectively push forward the shape completion project to a much more usable state for not only our lab but also any labs that may choose to use this software in the future.

[Download paper here]({{ base_path }}/files/2016_fall_OSCP.pdf)
[Download source here]({{ base_path }}/files/2016_fall_OSCP.tar.gz)
