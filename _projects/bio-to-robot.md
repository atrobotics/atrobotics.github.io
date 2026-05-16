---
layout: page
title: Bio-to-Robot Transfer
description: Fish sensorimotor dynamics transferred to a robotic fish using an interpretable ARX model.
img: assets/img/tocfig.png
importance: 1
category: research
---

![Bio-to-Robot Transfer](/assets/img/tocfig.png)

This project presents a biologically grounded framework for transferring fish sensorimotor dynamics to a robotic fish. We use synchronized electromyography and kinematic data from freely swimming koi to train an interpretable system-identification model, then evaluate its transfer to a robotic fish without robot-specific retraining.

The model maps biological muscle activity to tail motion using a compact ARX architecture, allowing the extraction of interpretable system properties such as delay, gain, natural frequency, and damping. Despite the domain shift between living fish and robotic hardware, the fish-trained model predicts robotic tail displacement with strong accuracy.

**Model:** Interpretable ARX system identification

**Input:** Fish EMG and robotic PWM actuation

**Output:** Tail displacement prediction

**Project website:** [bio-to-robot.github.io](https://bio-to-robot.github.io/)

**Paper:** [10.1002/aisy.202501117](https://doi.org/10.1002/aisy.202501117)

```bibtex
@article{afridi2025bio_to_robot,
  title = {Bio-to-Robot Transfer of Fish Sensorimotor Dynamics via Interpretable Model},
  author = {Afridi, Waqar Hussain and Tanveer, Ahsan and Afridi, Rahdar Hussain and Hamza, Muhammad and Wu, Mingxin and Li, Liang and Xie, Guangming},
  journal = {Advanced Intelligent Systems},
  pages = {e202501117},
  year = {2025},
  doi = {10.1002/aisy.202501117}
}
```
