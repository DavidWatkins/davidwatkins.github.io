---
title: "A Survey of Robotic Language Grounding: Tradeoffs Between Symbols and Embeddings"
collection: publications
permalink: /publication/2024-05-21-robotic-language-grounding
excerpt: ''
date: 2024-05-21
venue: 'IJCAI 2024'
paperurl: 'https://arxiv.org/abs/2405.13245'
citation: 'Cohen, V., Liu, J. X., Mooney, R., Tellex, S., & Watkins, D. (2024, August). A survey of robotic language grounding: tradeoffs between symbols and embeddings. In Proceedings of the Thirty-Third International Joint Conference on Artificial Intelligence (pp. 7999-8009).'
---

# Abstract

With large language models, robots can understand language more flexibly and are more capable than ever before. This survey reviews and situates recent literature into a spectrum with two poles:

	1.	Mapping between language and some manually defined formal representation of meaning.
	2.	Mapping between language and high-dimensional vector spaces that translate directly to low-level robot policy.

Using a formal representation allows the meaning of the language to be precisely represented, limits the size of the learning problem, and leads to a framework for interpretability and formal safety guarantees. Methods that embed language and perceptual data into high-dimensional spaces avoid this manually specified symbolic structure and thus have the potential to be more general when fed enough data, but require more data and computing to train. We discuss the benefits and tradeoffs of each approach and finish by providing directions for future work that achieves the best of both worlds.