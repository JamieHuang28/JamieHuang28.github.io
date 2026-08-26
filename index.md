---
layout: default
tab: projects
---

# Projects

My projects spans from Computer Vision & Robot Manipulation to Search & Optimization

## OpenVLA Improvement(under implementation)
On July and August of 2026, [Patch Policy(in JEPA)](https://arxiv.org/abs/2607.18236) and [Q-LEARNING WITH WORLD MODELS](https://arxiv.org/pdf/2608.17163) are published. They are all about how to learn with fewer shots, yet no open-source integration of them is available.

## [VisualLanguageAlignment(source code)](https://github.com/JamieHuang28/VisualLanguageAlignment)

<table>
  <tr>
    <td style="width:25%;vertical-align:middle;padding-right:16px;">
      <img src="./resources/eval_train.png" alt="vla_train_figure" style="width:160px;max-width:100%;display:block;margin:0;">
    </td>
    <td style="width:75%;vertical-align:middle;">
      <p>How to pair given images with given describing sentences?(which is called Visual-Semantic Alignment) Although <a href="https://karpathy.ai/">Karpathy</a> himself implements a image description generation model <a href="https://github.com/karpathy/neuraltalk2">NeuralTalk2</a> for the paper <a href="https://cs.stanford.edu/people/karpathy/deepimagesent/">Karpathy et al. CVPR 2015</a>, the Visual-Semantic Alignment Model is left blank. This project gives the whole implementation in up-to-date transformer-style.</p>
    </td>
  </tr>
</table>

## [MEMOofMAML: a simple illustration of meta-learning](https://github.com/JamieHuang28/MEMOofMAML)

<table>
  <tr>
    <td style="width:25%;vertical-align:middle;padding-right:16px;">
      <img src="./resources/MAML_param_updates_B.png" alt="MAML_figure" style="width:160px;max-width:100%;display:block;margin:0;">
    </td>
    <td style="width:75%;vertical-align:middle;">
      <p><a href="https://arxiv.org/abs/1703.03400">MAML(model-agnostic meta-learning)</a> is an algorithm which can "pretrain" NN with few-shot. And it is applicable to all learning without any change. This document is a memo trying to clearly illustrate this classic work.</p>
    </td>
  </tr>
</table>

## [iLQR from Scratch(source code)](https://github.com/JamieHuang28/iterative-linear-quadratic-regulator)

<table>
  <tr>
    <td style="width:25%;vertical-align:middle;padding-right:16px;">
      <img src="./resources/ilqr_vehicle_model.png" alt="ilqr_figure" style="width:160px;max-width:100%;display:block;margin:0;">
    </td>
    <td style="width:75%;vertical-align:middle;">
      <p>iLOR(iterative linear quadratic regulator) is a variant of the LQR(linear quadratic regulator) method for application in nonlinear dynamic system. This project provides:</p>
      <ul>
        <li>Example of UFO Rotation Control</li>
        <li>Example of Vehicle Driving Control</li>
        <li>Full documentation of LQR and iLQR</li>
      </ul>
    </td>
  </tr>
</table>

## [Auto-Tuning hybrid A*(under implementation)](https://github.com/JamieHuang28/hybrid_astar_algorithm)
By intuition, over 1000 collected data is enough to tune the 3 major parameters. This work is a simple yet efficient method to achieve it with SWO algorithm. (It is implemented during my career in Momenta, but the source code is missing by now)

## [NonlinearOptimizationSolver(source code)](https://github.com/JamieHuang28/NonlinearOptimizationSolver)
This small project show how onlinear-Optimization works with only hunderds lines of code.

## [underwater-cleaning-robot-ros(source code)](https://github.com/JamieHuang28/underwater-cleaning-robot-ros)

<table>
  <tr>
    <td style="width:25%;vertical-align:middle;padding-right:16px;">
      <img src="./resources/ucr_structure.jpg" alt="Underwater cleaning robot structure" style="width:160px;max-width:100%;display:block;margin:0;">
    </td>
    <td style="width:75%;vertical-align:middle;">
      <p>UCR(Underwater Cleaning Robot) is a project of HOME(Human-machine Ocean Mechanic Engineering) team, College of Mechanical Engineering, Zhejiang University. UCR packages are developed on ROS. This package is a collection of packages used on UCR such as simulation package and runing-online package.</p>
    </td>
  </tr>
</table>
