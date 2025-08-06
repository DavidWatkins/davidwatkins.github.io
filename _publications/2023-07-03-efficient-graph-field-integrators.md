---
title: "Efficient Graph Field Integrators Meet Point Clouds"
collection: publications
permalink: /publication/2023-07-03-efficient-graph-field-integrators
excerpt: ''
date: 2023-07-03
venue: International Conference on Machine Learning (ICML 2023)
paperurl: https://proceedings.mlr.press/v202/choromanski23b.html
citation: Choromanski, K., Sehanobish, A., Lin, H., Zhao, Y., Berger, E., Parshakova, T., Pan, A., Watkins, D., Zhang, T., Likhosherstov, V., Basu Roy Chowdhury, S., Dubey, K. A., Jain, D., Sarlos, T., Chaturvedi, S., & Weller, A. (2023, July). Efficient graph field integrators meet point clouds. In Proceedings of the 40th International Conference on Machine Learning (pp. 5978-6004). PMLR.
---

# Abstract
We present two new classes of algorithms for efficient field integration on graphs encoding point cloud data. The first class (SF) leverages the bounded genus of point cloud mesh graphs, while the second class (RFD) uses popular k-nearest-neighbor graph representations for point clouds. Both can be viewed as providing the functionality of Fast Multipole Methods (FMMs), which have had a tremendous impact on efficient integration, but for non-Euclidean spaces. We focus on geometries induced by distributions of walk lengths between points (e.g., shortest-path distance). We provide an extensive theoretical analysis of our algorithms, obtaining new results in structural graph theory as a byproduct. We also perform exhaustive empirical evaluation, including on-surface interpolation for rigid and deformable objects (in particular for mesh-dynamics modeling) as well as Wasserstein distance computations for point clouds, including the Gromov-Wasserstein variant.