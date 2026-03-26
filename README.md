# Awesome Embodied Evaluation [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of resources for evaluating embodied AI systems. Focused, comprehensive, and practitioner-oriented.

Curated by [CookeyEval](https://cookey.com.cn) — we believe that rigorous evaluation is the foundation of trustworthy robotics. This list focuses exclusively on the "evaluation" dimension of embodied AI, bringing together benchmarks, tools, datasets, and methodologies that help us measure how well robots actually perform in the real world.

---

## Table of Contents

- [Benchmarks](#benchmarks)
- [Evaluation Tools & Frameworks](#evaluation-tools--frameworks)
- [Evaluation Papers](#evaluation-papers)
- [Datasets for Evaluation](#datasets-for-evaluation)
- [Leaderboards](#leaderboards)
- [Standards & Reports](#standards--reports)
- [Contributing](#contributing)

---

## Benchmarks

Comprehensive evaluation benchmarks for embodied AI tasks, from manipulation to navigation and beyond.

### General Manipulation Benchmarks

- [RLBench](https://sites.google.com/view/rlbench) - A large-scale benchmark for robot learning featuring 100+ unique tasks with demonstrations, designed for few-shot learning evaluation.
- [MetaWorld](https://meta-world.github.io/) - A benchmark for meta-reinforcement learning in robotic manipulation, with 50 diverse tasks and evaluation protocols for generalization.
- [ManiSkill2](https://github.com/haosulab/ManiSkill2) - A unified benchmark for generalizable manipulation skills, supporting 2D/3D visual observations and fast parallel simulation.

### Long-Horizon and Multi-Task Benchmarks

- [CALVIN](https://github.com/mees/calvin) - A benchmark for language-conditioned long-horizon robot manipulation, featuring 1000+ hours of teleoperated demonstrations.
- [LIBERO](https://libero-project.github.io/) - A benchmark for lifelong learning in robotics, designed to evaluate continual learning and task composition capabilities.
- [BEHAVIOR-1K](https://behavior.stanford.edu/behavior-1k) - A comprehensive benchmark for household activities with 1,000 activities in realistic simulated environments.

### Vision-Language-Action (VLA) Benchmarks

- [SimplerEnv](https://github.com/simpler-conversation/simpler-env) - A simplified evaluation environment for vision-language models in robotic manipulation, enabling fast prototyping.
- [VLABench](https://github.com/VLABench/VLABench) - A benchmark specifically designed for evaluating Vision-Language-Action models on compositional tasks.
- [Open X-Embodiment](https://robotics-transformer-x.github.io/) - A large-scale dataset and benchmark spanning multiple robot embodiments and environments for cross-embodiment generalization.

### Simulation Environments

- [Habitat](https://aihabitat.org/) - A simulation platform for embodied AI research, particularly focused on navigation and mobile manipulation.
- [Isaac Gym](https://developer.nvidia.com/isaac-gym) - NVIDIA's high-performance GPU-based physics simulation for robot learning with massive parallelization.
- [MuJoCo](https://mujoco.org/) - A general-purpose physics engine with high-quality contact dynamics, widely used for continuous control evaluation.

---

## Evaluation Tools & Frameworks

Libraries and frameworks for conducting systematic evaluations of embodied AI systems.

- [EvalAI](https://eval.ai/) - An open-source platform for evaluating AI models, supporting embodied AI challenges with leaderboards and automated evaluation.
- [Gymnasium](https://gymnasium.farama.org/) - The standard API for reinforcement learning environments, providing standardized interfaces for evaluation loops.
- [Stable-Baselines3](https://stable-baselines3.readthedocs.io/) - A set of reliable implementations of RL algorithms with comprehensive evaluation utilities.
- [WandB (Weights & Biases)](https://wandb.ai/) - Experiment tracking and visualization platform with support for robotics evaluation metrics and video logging.
- [RoboMetrics](https://github.com/robometrics) - A toolkit for standardized evaluation metrics in robotic manipulation tasks.

---

## Evaluation Papers

Key research papers focusing on evaluation methodologies, metrics, and analysis of embodied AI systems.

### Evaluation Methodology

- ["How to Train Your Robot with Deep Reinforcement Learning: Lessons from Benchmarking Model-Based RL"](https://arxiv.org/abs/2011.07378) - Comprehensive analysis of evaluation practices in model-based RL for robotics.
- ["Benchmarking Reinforcement Learning Algorithms on Real-World Robots"](https://arxiv.org/abs/2009.13907) - Systematic study of the gap between simulation and real-world evaluation.
- ["The Surprising Effectiveness of Representation Learning for Visual Imitation"](https://arxiv.org/abs/2112.01514) - Analysis of evaluation metrics for visual imitation learning.

### Metrics and Analysis

- ["What Matters in Learning from Offline Human Demonstrations for Robot Manipulation"](https://arxiv.org/abs/2108.03298) - Analysis of evaluation metrics for imitation learning from human demonstrations.
- ["Scaling Robot Learning with Semantically Imagined Experience"](https://arxiv.org/abs/2302.11550) - Evaluation framework for scaling policies to diverse real-world scenarios.
- ["A Recipe for Unsupervised Learning of Visual Representations for Robotics"](https://arxiv.org/abs/2306.12831) - Methodology for evaluating learned visual representations in control tasks.

### Generalization and Robustness

- ["SORNet: Spatial Object-Centric Representations for Sequential Manipulation"](https://arxiv.org/abs/2110.10692) - Evaluation of object-centric representations for generalization.
- ["Real-World Robot Learning with Masked Visual Pre-training"](https://arxiv.org/abs/2210.03109) - Analysis of pre-training strategies and their evaluation on real robots.

---

## Datasets for Evaluation

Datasets specifically curated for training and evaluating embodied AI systems.

- [BridgeData V2](https://github.com/rail-berkeley/bridge_data_v2) - A large-scale dataset of robotic manipulation tasks with 60,000+ trajectories across diverse environments.
- [RT-1 Dataset](https://github.com/google-research/robotics_transformer) - The dataset used to train RT-1, containing 130,000+ episodes of real robot execution.
- [RoboTurk](https://roboturk.stanford.edu/) - A crowdsourced dataset of robot manipulation demonstrations collected via teleoperation.
- [MIME](https://sites.google.com/view/mime-dataset) - A dataset of human demonstrations with multi-modal sensory data for imitation learning evaluation.
- [ALOHA](https://tonyzhaozh.github.io/aloha/) - A low-cost hardware system and dataset for bimanual manipulation tasks.

---

## Leaderboards

Public leaderboards tracking the state-of-the-art in embodied AI tasks.

- [VLA Leaderboard](https://vla-leaderboard.github.io/) - Comprehensive leaderboard for Vision-Language-Action models on robotic manipulation tasks.
- [RoboChallenge](https://robochallenge.ai/) - A community-driven leaderboard for comparing robotic learning algorithms across standardized tasks.
- [Open X-Embodiment Leaderboard](https://robotics-transformer-x.github.io/) - Cross-embodiment evaluation leaderboard for generalist robot policies.
- [Habitat Challenge](https://aihabitat.org/challenge/) - Annual challenge and leaderboard for embodied navigation and mobile manipulation.
- [Procgen Benchmark Leaderboard](https://github.com/openai/procgen) - Leaderboard for evaluating generalization in reinforcement learning.

---

## Standards & Reports

Industry standards, white papers, and reports on robotics evaluation methodologies.

### International Standards

- [ISO/TC 299 - Robotics](https://www.iso.org/committee/679470.html) - International standards for robotics including safety and performance evaluation frameworks.
- [IEEE Robotics & Automation Society Standards](https://www.ieee-ras.org/industry-government/education-career-resources/standards) - Standards for robot performance evaluation and benchmarking.
- [NIST Robotics Test Facilities](https://www.nist.gov/el/intelligent-systems-division-73500/robotics-test-facilities) - U.S. national standards for robotics testing and evaluation.

### Research Reports

- ["On the Opportunities and Risks of Foundation Models for Embodied AI"](https://arxiv.org/abs/2306.16107) - Stanford HAI report on evaluation challenges in embodied foundation models.
- ["Embodied AI: Trends and Challenges"](https://www.ri.cmu.edu/publications/) - CMU Robotics Institute report on evaluation methodologies.
- ["Toward Standardized Evaluation of Robotic Manipulation"](https://arxiv.org/abs/2204.12509) - Proposal for standardized evaluation protocols in manipulation research.

### Industry Reports

- [Stanford AI Index Report - Robotics Chapter](https://aiindex.stanford.edu/report/) - Annual analysis of robotics AI progress with standardized evaluation metrics.
- [McKinsey Robotics Survey](https://www.mckinsey.com/capabilities/operations/our-insights) - Industry survey on robotics deployment and evaluation practices.

---

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

### Guidelines

1. **Focus on Evaluation**: This list is specifically for evaluation-related resources. General robotics resources should be directed to other awesome lists.
2. **Quality over Quantity**: We prioritize resources that are actively maintained, well-documented, and widely used in the community.
3. **Real Resources Only**: All submissions must link to real, existing projects or papers.
4. **Clear Descriptions**: Each entry should have a concise, informative description explaining its evaluation focus.

### How to Contribute

1. Fork the repository
2. Create a new branch (`git checkout -b add-resource`)
3. Add your resource to the appropriate category
4. Submit a Pull Request with a clear description of the addition

---

## About CookeyEval

<p align="center">
  <strong>Curated by CookeyEval — Embodied AI Evaluation Lab</strong>
</p>

<p align="center">
  Measuring how well robots serve humans, from a user-experience perspective.
</p>

<p align="center">
  <a href="https://cookey.com.cn">Website</a> •
  <a href="https://twitter.com/CookeyEval">Twitter @CookeyEval</a>
</p>

---

*Last updated: March 2026*
