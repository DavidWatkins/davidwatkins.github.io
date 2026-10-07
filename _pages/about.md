---
permalink: /
title: "David Watkins - Head of Research"
excerpt: "About me"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

I'm **Head of Research** at [Tutor Intelligence](https://tutorintelligence.com/), where I lead robot learning research connecting policy training, demonstration quality, and deployment on a 100-robot bimanual fleet. I also advise [Tola Capital](https://tolacapital.com/) on robotics and AI investments. Previously I was a **Research Lead** at the [RAI Institute](https://rai-inst.com/) (formerly Boston Dynamics AI Institute), where I built the Foundation Models and Capture teams, foundation models, and large-scale data infrastructure for robot learning.

### Research at Tutor Intelligence

- Led team improvements to full-rate, synchronized data logging and headless teleoperation; co-authored [**DF1: Maintaining Demonstration Quality in a 100-Robot Teleoperation Pipeline**]({{ base_url }}/publication/2026-07-13-df1-demo-quality) (RSS 2026 Workshop: It's the Demos)
- Moved research training to a **32-H100 allocation** and experiment tracking to self-hosted MLflow
- Designed Rust middleware for data collection and policy execution, and brought an initial version onto robot hardware with motion inhibited
- Set the research roadmap for policy evaluation and learning from human interventions

### Selected Research

- [**BRIDGE**]({{ base_url }}/publication/2026-07-14-bridge-state-gated-experts) combines handheld demonstrations with targeted teleoperation through state-gated diffusion policy experts for contact-rich manipulation. **Under review at ICRA 2027.**
- [**Koala Gripper**]({{ base_url }}/publication/2026-08-20-koala-gripper) co-designs handheld and actuated grippers with matched geometry, sensing, and force transmission for dexterous manipulation learning. **Under review at IEEE Transactions on Robotics (T-RO).**
- [**DF1**]({{ base_url }}/publication/2026-07-13-df1-demo-quality) connects teleoperation, data curation, and policy training with human interventions to maintain demonstration quality at fleet scale. **RSS 2026 Workshop: It's the Demos.**

### Foundation Models & Large-Scale Training

- Built foundation models research capability from scratch; pitched, launched, and led a team of 10+ researchers
- Designed and trained video prediction models using internet-scale video data on a **320 H100 GPU cluster** (early 2023)
- Created [**Theia**](https://arxiv.org/abs/2407.20179), a vision foundation model that distills multiple pretrained models into a single compact representation (CoRL 2024)
- Built multimodal architectures combining diverse sensor modalities with internet-scale pretrained priors for improved downstream performance

### Data Infrastructure & Quality at Scale

- Founded and led the **Capture** team (30 people), the largest data collection effort at the institute with a roadmap for **100,000+ demonstrations**
- Built handheld force-based data collection capturing force, vision, and proprioception for in-the-wild demonstrations
- Created task definition frameworks and benchmark protocols that improved demonstration quality and consistency across teams
- Established research partnerships with Google, Columbia, ETH Zurich, and Agile Robots for data and evaluation

### Reinforcement Learning from Human Feedback

- Won **1st place** at the [MineRL BASALT Competition](https://arxiv.org/abs/2112.03482) (NeurIPS 2021) for learning from human feedback, combining imitation learning, human preference data, and hierarchical knowledge engineering to solve tasks defined only by natural language descriptions
- Developed [DIP-RL](https://arxiv.org/abs/2307.12158), a preference-based RL algorithm that leverages demonstrations to infer reward functions from human preferences (ICML 2023 Workshop)
- Developed gradient-free RL enabling online learning with non-differentiable semantic reward functions (U.S. Patent pending, May 2025)

### Publications & Writing

- Published at **CoRL 2024**, **IJCAI 2024**, **ICML 2023**, **IROS 2022** (Best Paper Finalist), and more
- Authored a [survey on language grounding](https://arxiv.org/abs/2405.13245) examining the spectrum from symbolic representations to end-to-end learned embeddings (IJCAI 2024)
- Co-authored [**"Elephants Don't Write Sonnets"**]({{ base_url }}/publication/2025-08-06-elephants-dont-write-sonnets) with [Stefanie Tellex](https://cs.brown.edu/people/stellex/) for the forthcoming MIT Press volume *Designing an Intelligence*, on the Grounded Turing Test for embodied AI
- Write about AI at [whattotelltherobot.com](https://whattotelltherobot.com)
- Co-organized the [New England Manipulation Symposium (NEMS) 2025](https://nems25.github.io/) at MIT

### Education & Background

- **Ph.D., M.S., B.S.** from [Columbia University](http://www.cs.columbia.edu/robotics/), [Columbia Robotics Lab](http://www.cs.columbia.edu/robotics/) under [Prof. Peter Allen](https://www.cs.columbia.edu/~allen/) ([academic lineage]({{ base_url }}/lineage))
- Dissertation on mobile manipulation without runtime localization (**IROS 2022 Best Paper Finalist**)
- **Army Research Lab Fellow** (2018–2022)
- **CEO/Co-founder** of Odefi ([Columbia-IBM Blockchain Accelerator](https://innovationresources.columbia.edu/content/columbia-ibm-launch-accelerator))

More information is available in my <a href="{{ base_url }}/cv">curriculum vitae</a> or my <a href="{{ base_url }}/resume">resume</a>.
