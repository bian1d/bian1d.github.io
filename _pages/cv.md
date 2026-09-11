---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<!-- Education
======
* Ph.D in Version Control Theory, GitHub University, 2018 (expected)
* M.S. in Jekyll, GitHub University, 2014
* B.S. in GitHub, GitHub University, 2012 

Work experience
======
* Spring 2024: Academic Pages Collaborator
  * Github University
  * Duties includes: Updates and improvements to template
  * Supervisor: The Users

* Fall 2015: Research Assistant
  * Github University
  * Duties included: Merging pull requests
  * Supervisor: Professor Hub

* Summer 2015: Research Assistant
  * Github University
  * Duties included: Tagging issues
  * Supervisor: Professor Git
  
Skills
======
* Skill 1
* Skill 2
  * Sub-skill 2.1
  * Sub-skill 2.2
  * Sub-skill 2.3
* Skill 3

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* Currently signed in to 43 different slack teams -->

Education
======
* M.S. in Data Science, Harvard University, 2026/09 – 2028/05 (expected)
* B.S. in Data Science (Minor in Economics), Yuanpei College, Peking University, 2021/09 – 2026/07
  * Cumulative GPA: 3.75/4.00
  * Related Courses: Machine Learning, Generative Modeling, Probability Theory, Econometrics, Operating Systems
  * Awards: Merit Student Award & Second Prize Scholarship, Peking University (2025); Gold Medalist & National Training Squad Member, 34th Chinese Chemistry Olympiad (2020); School-level Learning Excellence Award (2022)
* Exchange Student, Electrical Engineering and Computer Sciences, University of California, Berkeley, 2024/01 – 2024/05
  * GPA: 3.90/4.00
  * Related Courses: Statistics, LLMs and Alignment, Embodied AI, Generative Modeling, CS170 Efficient Algorithms, CS162 Operating Systems, CS61C Computer Architecture

Work experience
======
* Prof. Liangming Pan's Group, Peking University, Beijing, China
  * **Interpretable Data Attribution for LLM Post-training**, 2025/12 – present
    * Identified which RLHF training samples make a language model less toxic by applying influence-function data attribution to PPO rollouts, a setting prior attribution work (pretraining-only) did not cover.
    * Implemented EK-FAC influence functions from scratch in PyTorch, matching brute-force Fisher computation within 1e-3 error; now extending the method to RLVR-trained reasoning models (DeepSeek-R1-Distill-Qwen-1.5B).
    * Builds on: Grosse et al., *Studying Large Language Model Generalization with Influence Functions* (Anthropic, 2023) [[arXiv](https://arxiv.org/abs/2308.03296)] [[Anthropic Research](https://www.anthropic.com/research/studying-large-language-model-generalization-with-influence-functions)]

* Laboratory of Prof. He Wang, Peking University, Beijing, China
  * **Motion Planning and Control for Collaborative Robot and Quadruped System**, 2025/03 – 2025/06
    * Developed RRT-based collaborative motion planning for a robot (GalBot) and quadruped (Unitree Go2) system, enabling synchronized, collision-free task execution.
    * Bridged sim-to-real gaps by calibrating quadruped trajectory and locomotion parameters across real platforms.

  <div class="media-row">
  <figure style="--ar: 0.75">
  <a href="/images/robot_onsite.jpg" target="_blank" rel="noopener"><img src="/images/robot_onsite.jpg" alt="On-site real-robot experiment with GalBot and Unitree Go2"></a>
  <figcaption>On-site real-robot experiment (GalBot + Unitree Go2). Click to enlarge.</figcaption>
  </figure>
  <figure style="--ar: 1.6889">
  <video controls preload="metadata" playsinline poster="/images/robotics_demo_poster.jpg">
  <source src="/files/robotics_demo.mp4" type="video/mp4">
  Your browser does not support the video tag.
  </video>
  <figcaption>Simulation demo: collaborative planning for arm + quadruped (MuJoCo)</figcaption>
  </figure>
  </div>

* Laboratory of Dr. Di He, Peking University, Beijing, China
  * **Molecular Force Field Prediction Using Graph Neural Networks**, 2024/06 – 2024/11
    * Tested whether physics-informed design improves neural network accuracy: implemented force prediction as energy gradients with respect to particle positions, trained on ~1.28 million organic molecules, and matched the SOTA EquiformerV2 model.
    * Integrated real-time data streaming into Meta's Fairseq training framework in Python, sustaining stable training across 8× RTX 4090 GPUs.

* Laboratory of Dr. Xiaotie Deng, Beijing, China
  * **Large-Scale Contextual Market Equilibrium Computation through Deep Learning**, 2023/07 – 2024/02
    * Developed a context-based method for solving large-scale market equilibrium.
    * Proposed Nash-GAP, an optimization metric.
    * Responsible for pre-paper research, coding, experiments, and writing part of the paper.
    * Published in *Frontiers of Algorithmics (IJTCS-FAW 2025)*, LNCS, Springer, pp. 356–371. [[arXiv](https://arxiv.org/abs/2406.15459)] [[Springer](https://link.springer.com/chapter/10.1007/978-981-96-8312-3_27)] [[Abstract](https://bian1d.github.io/posts/2024/02/large-scale-contextual-market-equilibrium/)]

* The First Quantitative Finance Competition of Peking University, Beijing, China
  * **Participant**, 2023/05
    * Built a decision tree model for stock time series data analysis and forecasting.
    * Ranked 15th among contestants.

* Laboratory of Dr. E Weinan, Beijing, China
  * **Application of Neural Networks in Optimal Control**, 2023/05 – 2023/07
    * Reproduced and verified the thesis of fitting a value function in a high dimensional space by a neural network.

* Laboratory of Dr. Leye Wang, Beijing, China
  * **Extension of Spatio-Temporal Prediction Models to Multi-Step Prediction**, 2023/02 – 2023/04
    * Enhanced the STMeta spatio-temporal prediction toolbox for multi-step prediction.

Skills
======
* Language Skills: Native Mandarin Chinese, proficient English (IELTS: 7.0).
* Programming Skills: Python (PyTorch, NumPy, Pandas, etc.), C++, C, Stata, LaTeX, Git, Wandb, Markdown.
* Additional Skills: Game theory, economics.

Research Interests
======
* Interpretability and data attribution for large language models, embodied AI, and computational economics.

Hobbies
======
* Singing (baritone), Frisbee, Tennis, Skiing, and Strategy Games.
