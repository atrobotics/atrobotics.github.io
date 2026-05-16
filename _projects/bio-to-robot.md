---
layout: page
title: Bio-to-Robot Transfer
description: Fish sensorimotor dynamics transferred to a robotic fish using an interpretable ARX model.
img: /assets/img/tocfig.png
importance: 1
category: research
---

<div class="row">
  <div class="col-sm mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/tocfig.png" title="Bio-to-Robot Transfer" class="img-fluid rounded z-depth-1" %}
  </div>
</div>

This project presents a biologically grounded framework for transferring fish sensorimotor dynamics to a robotic fish. We use synchronized electromyography and kinematic data from freely swimming koi to train an interpretable system-identification model, then evaluate its transfer to a robotic fish without robot-specific retraining.

The model maps biological muscle activity to tail motion using a compact ARX architecture, allowing the extraction of interpretable system properties such as delay, gain, natural frequency, and damping. Despite the domain shift between living fish and robotic hardware, the fish-trained model predicts robotic tail displacement with strong accuracy.

<div class="row mt-4">
  <div class="col-sm-4">
    <strong>Model</strong><br>
    Interpretable ARX system identification
  </div>
  <div class="col-sm-4">
    <strong>Input</strong><br>
    Fish EMG / robotic PWM actuation
  </div>
  <div class="col-sm-4">
    <strong>Output</strong><br>
    Tail displacement prediction
  </div>
</div>

<br>

**Project website:** [bio-to-robot.github.io](https://bio-to-robot.github.io/)  
**Paper:** [10.1002/aisy.202501117](https://doi.org/10.1002/aisy.202501117)

```bibtex
@article{afridi2025bio_to_robot,
  title   = {Bio-to-Robot Transfer of Fish Sensorimotor Dynamics via Interpretable Model},
  author  = {Afridi, Waqar Hussain and Tanveer, Ahsan and Afridi, Rahdar Hussain and Hamza, Muhammad and Wu, Mingxin and Li, Liang and Xie, Guangming},
  journal = {Advanced Intelligent Systems},
  pages   = {e202501117},
  year    = {2025},
  doi     = {10.1002/aisy.202501117}
}
