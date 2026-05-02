-- -
layout: page
title: Equilibrium - Anchored Rollouts
for Stable Multi - Step Prediction
description: RSS 2026 paper project page
img: /assets/img / equilibrium_rollouts / teaser.png
importance: 1
category: research
    -- -

    # # Overview

This project presents an equilibrium - anchored prediction framework
for stable multi - step rollout of soft and continuum robotic systems under actuation shift.The method separates the steady - state response from transient correction by learning an input - conditioned equilibrium anchor from static data and a residual dynamics model from trajectory data.

The framework is evaluated on a tendon - driven 3 D continuum arm, classical nonlinear benchmarks, and a soft - tail hardware testbed under actuation - frequency shift.

# # Paper

    **
    Equilibrium - Anchored Residual Dynamics
for Stable Multi - Step Rollouts of Soft Robotic Systems **
    Rahdar Hussain Afridi, Coauthor Names

Accepted at ** Robotics: Science and Systems(RSS), 2026 ** .

Paper PDF: coming soon
Supplementary video: coming soon

# # Method

The key idea is to decompose prediction into two components:

    1. an equilibrium anchor learned from static input - state pairs,
    2. a residual correction learned from dynamic trajectories.

This avoids forcing a single predictor to model both steady - state response and transient deviation during long recursive rollout.

# # Results

The method improves long - horizon prediction under out - of - distribution actuation.On the continuum - arm benchmark, it reduces backbone and tip RMSE compared with anchor - only and residual - only baselines.Additional soft - tail hardware experiments show improved robustness under actuation - frequency shift.

# # Videos

Coming soon.

# # Code

A cleaned and documented implementation is being prepared
for public release.A tagged release corresponding to the RSS 2026 camera - ready experiments will be linked here once finalized.

For reproducibility inquiries before release, please contact the authors.

# # Citation

    ``
`bibtex
@inproceedings{afridi2026equilibrium,
  title = {Equilibrium-Anchored Residual Dynamics for Stable Multi-Step Rollouts of Soft Robotic Systems},
  author = {Afridi, Rahdar Hussain and Coauthor Names},
  booktitle = {Robotics: Science and Systems},
  year = {2026}
}
