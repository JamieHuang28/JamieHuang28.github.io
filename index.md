---
layout: default
tab: projects
---

# Projects

My projects spans from Computer Vision & Robot Manipulation to Search & Optimization

## OpenVLA Improvement(under implementation)
On July and August of 2026, [Patch Policy(in JEPA)](https://arxiv.org/abs/2607.18236) and [Q-LEARNING WITH WORLD MODELS](https://arxiv.org/pdf/2608.17163) are published. They are all about how to learn with fewer shots, yet no open-source integration of them is available.


## [VisualLanguageAlignment(source code)](https://github.com/JamieHuang28/VisualLanguageAlignment)
How to pair given images with given describing sentences?(which is called Visual-Semantic Alignment) Although [Karpathy](https://karpathy.ai/) himself implements a image description generation model [NeuralTalk2](https://github.com/karpathy/neuraltalk2) for the paper [Karpathy et al. CVPR 2015](https://cs.stanford.edu/people/karpathy/deepimagesent/), the Visual-Semantic Alignment Model is left blank. This project gives the whole implementation in up-to-date transformer-style.

![vla_train_figure](./resources/eval_train.png)

## [MEMOofMAML: a simple illustration of meta-learning](https://github.com/JamieHuang28/MEMOofMAML)
[MAML(model-agnostic meta-learning)](https://arxiv.org/abs/1703.03400) is an algorithm which can "pretrain" NN with few-shot. And it is applicable to all learning without any change. This document is a memo trying to clearly illustrate this classic work.

![MAML_figure](./resources/MAML_param_updates_B.png)

## [iLQR from Scratch(source code)](https://github.com/JamieHuang28/iterative-linear-quadratic-regulator)
iLOR(iterative linear quadratic regulator) is a variant of the LQR(linear quadratic regulator) method for application in nonlinear dynamic system. This project provides:
- Example of UFO Rotation Control
- Example of Vehicle Driving Control
- Full documentation of LQR and iLQR

![ilqr_figure](./resources/ilqr_vehicle_model.png)

## [Auto-Tuning hybrid A*(under implementation)](https://github.com/JamieHuang28/hybrid_astar_algorithm)
By intuition, over 1000 collected data is enough to tune the 3 major parameters. This work is a simple yet efficient method to achieve it with SWO algorithm. (It is implemented during my career in Momenta, but the source code is missing by now)

## [NonlinearOptimizationSolver(source code)](https://github.com/JamieHuang28/NonlinearOptimizationSolver)
This small project show how onlinear-Optimization works with only hunderds lines of code.

{% capture ucr_body %}
## [underwater-cleaning-robot-ros(source code)](https://github.com/JamieHuang28/underwater-cleaning-robot-ros)
UCR(Underwater Cleaning Robot) is a project of HOME(Human-machine Ocean Mechanic Engineering) team, College of Mechanical Engineering, Zhejiang University. UCR packages are developed on ROS. This package is a collection of packages used on UCR such as simulation package and runing-online package.
{% endcapture %}
{% include thumbnail.html src="/resources/ucr_structure.jpg" alt="Underwater cleaning robot structure" body=ucr_body %}