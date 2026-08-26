---
layout: default
tab: projects
---

My projects span from Computer Vision, Robot Manipulation to Search and Optimization.

<table class="project-list">
  <tr>
    <td colspan="2">
      <span class="project-title">OpenVLA Improvement (under implementation)</span>
      <p>In July and August of 2026, <a href="https://arxiv.org/abs/2607.18236">Patch Policy (in JEPA)</a> and <a href="https://arxiv.org/pdf/2608.17163">Q-Learning with World Models</a> were published. They are all about how to learn with fewer shots, yet no open-source integration of them is available.</p>
    </td>
  </tr>
  <tr>
    <td class="project-thumb">
      <img src="./resources/eval_train.png" alt="vla_train_figure">
    </td>
    <td class="project-body">
      <a class="project-title" href="https://github.com/JamieHuang28/VisualLanguageAlignment">VisualLanguageAlignment (source code)</a>
      <p>How to pair given images with given describing sentences? (This is called Visual-Semantic Alignment.) Although <a href="https://karpathy.ai/">Karpathy</a> himself implements an image description generation model, <a href="https://github.com/karpathy/neuraltalk2">NeuralTalk2</a>, for the paper <a href="https://cs.stanford.edu/people/karpathy/deepimagesent/">Karpathy et al. CVPR 2015</a>, the Visual-Semantic Alignment model is left blank. This project provides a complete implementation in an up-to-date transformer style.</p>
    </td>
  </tr>
  <tr>
    <td class="project-thumb">
      <img src="./resources/MAML_param_updates_B.png" alt="MAML_figure">
    </td>
    <td class="project-body">
      <a class="project-title" href="https://github.com/JamieHuang28/MEMOofMAML">MEMOofMAML: a simple illustration of meta-learning (source code)</a>
      <p><a href="https://arxiv.org/abs/1703.03400">MAML (model-agnostic meta-learning)</a> is an algorithm that can "pretrain" a neural network with few-shot learning. It is applicable to all learning tasks without any change. This document is a memo that tries to illustrate this classic work clearly.</p>
    </td>
  </tr>
  <tr>
    <td class="project-thumb">
      <img src="./resources/ilqr_vehicle_model.png" alt="ilqr_figure">
    </td>
    <td class="project-body">
      <a class="project-title" href="https://github.com/JamieHuang28/iterative-linear-quadratic-regulator">iLQR from Scratch (source code)</a>
      <p>iLQR (iterative linear quadratic regulator) is a variant of the LQR (linear quadratic regulator) method for application in nonlinear dynamic systems. This project provides:</p>
      <ul>
        <li>Example of UFO Rotation Control</li>
        <li>Example of Vehicle Driving Control</li>
        <li>Full documentation of LQR and iLQR</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td colspan="2">
      <a class="project-title" href="https://github.com/JamieHuang28/hybrid_astar_algorithm">Auto-Tuning hybrid A* (under recovery)</a>
      <p>By intuition, over 1,000 collected data points are enough to tune the 3 major parameters. This work is a simple yet efficient method to achieve it with the SWO algorithm. (It was implemented during my career at Momenta, but the source code is missing for now.)</p>
    </td>
  </tr>
  <tr>
    <td colspan="2">
      <a class="project-title" href="https://github.com/JamieHuang28/NanoNonlinearOptimizationSolver">NanoNonlinearOptimizationSolver (source code)</a>
      <p>This mini project implements a prototype of a nonlinear solver with only hundreds of lines of code.</p>
    </td>
  </tr>
  <tr>
    <td class="project-thumb">
      <img src="./resources/ucr_structure.jpg" alt="Underwater cleaning robot structure">
    </td>
    <td class="project-body">
      <a class="project-title" href="https://github.com/JamieHuang28/underwater-cleaning-robot-ros">underwater-cleaning-robot-ros (source code)</a>
      <p>UCR (Underwater Cleaning Robot) is a project of the HOME (Human-machine Ocean Mechanic Engineering) team, College of Mechanical Engineering, Zhejiang University. UCR packages are developed on ROS. This package is a collection of packages used on UCR, such as the simulation package and the running-online package.</p>
    </td>
  </tr>
</table>
