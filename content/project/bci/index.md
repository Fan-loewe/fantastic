---
title: Robot movement with mind
summary: Student project at TU Munich
date: 2019-06-01
type: docs
math: false
tags:
  - Brain-computer interface
  - Signal Processing
  - Machine learning

image:
  caption: 'caption'
---
{{< youtube lB6WYwblP8A >}}

During my master's program at TUM, I participated in a team project focused on controlling a robotic car using a brain-computer interface (BCI). The control mechanism involved using blinking boxes with three different frequencies. When a person looks at these boxes, their brain activity varies depending on the frequency. We extracted the corresponding EEG signals and trained a classifier to distinguish between these differences. The BCI then linked the classification results to the car's motor commands. Specifically, the three different blinking frequencies corresponded to the commands "left," "right," and "keep going," enabling us to control the car with our minds.

This project encompassed several key areas of knowledge, including:

* SSVEP-based brain-computer interface
* EEG signal acquisition and processing
* Training a linear discriminant analysis classifier
