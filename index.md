---
layout: default
tab: projects
---

# Projects

My projects span from computer vision and robot manipulation to search and optimization.

## OpenVLA Improvement (under implementation)
In July and August of 2026, [Patch Policy (in JEPA)](https://arxiv.org/abs/2607.18236) and [Q-Learning with World Models](https://arxiv.org/pdf/2608.17163) were published. They are all about how to learn with fewer shots, yet no open-source integration of them is available.

## [VisualLanguageAlignment (source code)](https://github.com/JamieHuang28/VisualLanguageAlignment)

<table>
  <tr>
    <td style="width:25%;vertical-align:middle;padding-right:16px;">
      <img src="./resources/eval_train.png" alt="vla_train_figure" style="width:160px;max-width:100%;display:block;margin:0;">
    </td>
    <td style="width:75%;vertical-align:middle;">
      <p>How to pair given images with given describing sentences? (This is called Visual-Semantic Alignment.) Although <a href="https://karpathy.ai/">Karpathy</a> himself implements an image description generation model, <a href="https://github.com/karpathy/neuraltalk2">NeuralTalk2</a>, for the paper <a href="https://cs.stanford.edu/people/karpathy/deepimagesent/">Karpathy et al. CVPR 2015</a>, the Visual-Semantic Alignment model is left blank. This project provides a complete implementation in an up-to-date transformer style.</p>
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
      <p><a href="https://arxiv.org/abs/1703.03400">MAML (model-agnostic meta-learning)</a> is an algorithm that can "pretrain" a neural network with few-shot learning. It is applicable to all learning tasks without any change. This document is a memo that tries to illustrate this classic work clearly.</p>
    </td>
  </tr>
</table>

## [iLQR from Scratch (source code)](https://github.com/JamieHuang28/iterative-linear-quadratic-regulator)

<table>
  <tr>
    <td style="width:25%;vertical-align:middle;padding-right:16px;">
      <img src="./resources/ilqr_vehicle_model.png" alt="ilqr_figure" style="width:160px;max-width:100%;display:block;margin:0;">
    </td>
    <td style="width:75%;vertical-align:middle;">
      <p>iLQR (iterative linear quadratic regulator) is a variant of the LQR (linear quadratic regulator) method for application in nonlinear dynamic systems. This project provides:</p>
      <ul>
        <li>Example of UFO Rotation Control</li>
        <li>Example of Vehicle Driving Control</li>
        <li>Full documentation of LQR and iLQR</li>
      </ul>
    </td>
  </tr>
</table>

## [Auto-Tuning hybrid A* (under implementation)](https://github.com/JamieHuang28/hybrid_astar_algorithm)
By intuition, over 1,000 collected data points are enough to tune the 3 major parameters. This work is a simple yet efficient method to achieve it with the SWO algorithm. (It was implemented during my career at Momenta, but the source code is missing for now.)

## [NanoNonlinearOptimizationSolver (source code)](https://github.com/JamieHuang28/NanoNonlinearOptimizationSolver)
This mini project implements a prototype of a nonlinear solver with only hundreds of lines of code.

## [underwater-cleaning-robot-ros (source code)](https://github.com/JamieHuang28/underwater-cleaning-robot-ros)

<table>
  <tr>
    <td style="width:25%;vertical-align:middle;padding-right:16px;">
      <img src="./resources/ucr_structure.jpg" alt="Underwater cleaning robot structure" style="width:160px;max-width:100%;display:block;margin:0;">
    </td>
    <td style="width:75%;vertical-align:middle;">
      <p>UCR (Underwater Cleaning Robot) is a project of the HOME (Human-machine Ocean Mechanic Engineering) team, College of Mechanical Engineering, Zhejiang University. UCR packages are developed on ROS. This package is a collection of packages used on UCR, such as the simulation package and the running-online package.</p>
    </td>
  </tr>
</table>
