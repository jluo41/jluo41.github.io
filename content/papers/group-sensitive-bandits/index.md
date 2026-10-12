---
title: "Group-Sensitive Offline Contextual Bandits"
date: 2025-10-31
tags: ["contextual bandits","fairness","offline policy optimization","machine learning"]
author: ["Yihong Guo","Junjie Luo","Guodong (Gordon) Gao","Ritu Agarwal","Anqi Liu"]
description: "Group-Sensitive Offline Contextual Bandits. arXiv preprint, 2025."
summary: "Offline contextual bandits allow one to learn policies from historical/offline data without requiring online interaction."
cover:
    image: ""
    alt: "Group-Sensitive Offline Contextual Bandits"
    relative: true
editPost:
    URL: "https://arxiv.org/abs/2510.27123"
    Text: "arXiv preprint"

---

---

##### Download

+ [Paper](https://arxiv.org/abs/2510.27123)

---

##### Abstract

Offline contextual bandits allow one to learn policies from historical/offline data without requiring online interaction. However, offline policy optimization that maximizes overall expected rewards can unintentionally amplify the reward disparities across groups. As a result, some groups might benefit more than others from the learned policy, raising concerns about fairness, especially when the resources are limited. In this paper, we study a group-sensitive fairness constraint in offline contextual bandits, reducing group-wise reward disparities that may arise during policy learning. We tackle the following common-parity requirements: the reward disparity is constrained within some user-defined threshold or the reward disparity should be minimized during policy optimization. We propose a constrained offline policy optimization framework by introducing group-wise reward disparity constraints into an off-policy gradient-based optimization procedure. To improve the estimation of the group-wise reward disparity during training, we employ a doubly robust estimator and further provide a convergence guarantee for policy optimization. Empirical results in synthetic and real-world datasets demonstrate that our method effectively reduces reward disparities while maintaining competitive overall performance.

---

##### Citation

Guo, Yihong, Junjie Luo, Guodong (Gordon) Gao, Ritu Agarwal, and Anqi Liu. 2025. "Group-Sensitive Offline Contextual Bandits." *arXiv preprint* arXiv:2510.27123.

```BibTeX
@article{guo2025group,
  title={Group-Sensitive Offline Contextual Bandits},
  author={Guo, Yihong and Luo, Junjie and Gao, Gordon and Agarwal, Ritu and Liu, Anqi},
  journal={arXiv preprint arXiv:2510.27123},
  year={2025}
}
```
