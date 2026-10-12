---
title: "FairGlucose: A CGM Fairness Benchmark Reveals Subgroup Disparities Hidden in Population-Level Validation"
date: 2026-08-18
tags: ["fairness","benchmark","CGM","diabetes","digital health"]
author: ["Junjie Luo","Xuzhe Zhi","Rui Han","Abhimanyu Kumbara","Anand K. Iyer","Mansur E. Shomali","Ritu Agarwal","Guodong (Gordon) Gao"]
description: "FairGlucose: A CGM Fairness Benchmark Reveals Subgroup Disparities Hidden in Population-Level Validation. arXiv preprint, 2026."
summary: "As CGM-based AI tools approach clinical deployment, whether their accuracy is equitable across patient demographics remains insufficiently tested."
cover:
    image: ""
    alt: "FairGlucose"
    relative: true
editPost:
    URL: "https://arxiv.org/abs/2608.18296"
    Text: "arXiv preprint"

---

---

##### Download

+ [Paper](https://arxiv.org/abs/2608.18296)

---

##### Abstract

As CGM-based AI tools approach clinical deployment, whether their accuracy is equitable across patient demographics remains insufficiently tested. To enable this evaluation, we constructed FairGlucose, a 300-patient CGM cohort balanced across 12 demographic strata (age x gender x type 1/type 2 diabetes), with 132,480 forecasting samples and 3,945 unique behavioral events (meals, exercise, medication) logged by 81 patients. Benchmarking 33 models across four families on 2-hour glucose forecasting, we find that population-level external validation can conceal substantial subgroup disparities. Aggregate out-of-distribution metrics appear stable (approximately 1.0), yet subgroup-level ratios range from 0.8 to 1.4, with T1D patients showing 6 mg/dL higher prediction error than T2D (p < 0.001). This disparity persists across all 33 models, suggesting a property of the prediction task rather than any single architecture. Further analysis shows that subgroup performance gaps align with the proportion of clinically hard cases, and that input-length sensitivity varies across demographics, motivating personalized configurations. Frontier LLMs underperform specialized neural models by 1-6 mg/dL; behavioral events contribute negligibly (approximately 0.1 mg/dL) even under oracle event access. These findings establish that population-level validation alone is insufficient for equity assessment of digital health AI, motivating subgroup-disaggregated reporting as a default standard.

---

##### Citation

Luo, Junjie, Xuzhe Zhi, Rui Han, Abhimanyu Kumbara, Anand K. Iyer, Mansur E. Shomali, Ritu Agarwal, and Guodong (Gordon) Gao. 2026. "FairGlucose: A CGM Fairness Benchmark Reveals Subgroup Disparities Hidden in Population-Level Validation." *arXiv preprint* arXiv:2608.18296.

```BibTeX
@article{luo2026fairglucose,
  title={FairGlucose: A CGM Fairness Benchmark Reveals Subgroup Disparities Hidden in Population-Level Validation},
  author={Luo, Junjie and Zhi, Xuzhe and Han, Rui and Kumbara, Abhimanyu and Iyer, Anand K. and Shomali, Mansur E. and Agarwal, Ritu and Gao, Gordon},
  journal={arXiv preprint arXiv:2608.18296},
  year={2026}
}
```
