---
title: "Visual-Tactile Geometric Reasoning"
collection: research
permalink: /research/2017-07-15-visual-tactile-geometric-reasoning
excerpt: 'This work provides an architecture which uses a learning algorithm that incorporates depth and tactile information to create rich and accurate 3D models from single depth images. The models are then able to be used for robotic manipulation tasks. This is accomplished through the use of a 3D convolutional neural network (CNN). Offline, the network is provided with both depth and tactile information and trained to predict the object’s geometry, filling in the occluded regions of the object. At runtime, the network is provided a partial view of an object. The network then produces an initial object hypothesis using depth alone. A grasp is planned using this hypothesis and a guarded move takes place to collect tactile information. The network can then improve the system’s understanding of the object’s geometry by utilizing the newly collected tactile information.'
date: 2017-07-15
paperurl: 'https://ddm2017.mit.edu/sites/default/files/documents/3.pdf'
---
This work provides an architecture which uses a learning algorithm that incorporates depth and tactile information to create rich and accurate 3D models from single depth images. The models are then able to be used for robotic manipulation tasks. This is accomplished through the use of a 3D convolutional neural network (CNN). Offline, the network is provided with both depth and tactile information and trained to predict the object’s geometry, filling in the occluded regions of the object. At runtime, the network is provided a partial view of an object. The network then produces an initial object hypothesis using depth alone. A grasp is planned using this hypothesis and a guarded move takes place to collect tactile information. The network can then improve the system’s understanding of the object’s geometry by utilizing the newly collected tactile information.

Citation: <cite>Jacob Varley, David Watkins, and Peter Allen. “Visual-Tactile Geometric Reasoning (Abstract and Poster)”. In: Data-Driven Manipulation workshop, Robotics: Science and Systems (2017).</cite>

[Download paper here](https://ddm2017.mit.edu/sites/default/files/documents/3.pdf)

<iframe width="550" height="390" src="https://www.youtube.com/embed/vsJwSkVBtkY" frameborder="0" allowfullscreen></iframe>
