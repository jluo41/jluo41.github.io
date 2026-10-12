---
title: "EventGlucose: A Benchmark for Continuous Glucose Monitoring Forecasting with Behavioral Event Context"
date: 2026-08-07
tags: ["benchmark","CGM","diabetes","time series","foundation model","LLM"]
author: ["Junjie Luo","Xuzhe Zhi","Rui Han","Abhimanyu Kumbara","Mansur E. Shomali","Anand K. Iyer","Ritu Agarwal","Guodong (Gordon) Gao"]
description: "EventGlucose: A Benchmark for Continuous Glucose Monitoring Forecasting with Behavioral Event Context. KDD 2026."
summary: "Glucose forecasting is critical for diabetes management."
cover:
    image: ""
    alt: "EventGlucose"
    relative: true
editPost:
    URL: "https://doi.org/10.1145/3770855.3817572"
    Text: "KDD 2026"

---

---

##### Download

+ [Paper](https://doi.org/10.1145/3770855.3817572)

---

##### Abstract

Glucose forecasting is critical for diabetes management. Continuous glucose monitoring (CGM) provides real-time readings, but glucose values alone do not capture the behavioral events (meals, exercise, medication) that clinicians and patients use to make daily decisions. In spite of advances in time series foundation models and large language models (LLMs), systematic study of event-aware glucose forecasting remains limited, and how behavioral event context helps different model families remains unclear. We introduce EventGlucose, a benchmark where every task pairs glucose time series with behavioral event context; every task requires event context for accurate prediction. EventGlucose provides 60 task instances spanning demographics, event types, and 5 context conditions, from no context to detailed event descriptions. We evaluate 18 model configurations zero-shot, covering LLM-based forecasters, multimodal architectures, time series foundation models, and statistical baselines. We report Clarke Error Grid-weighted CRPS metrics that emphasize clinical risk zones. Our experiments reveal a Context Integration Gap: richer context can help, but most current models fail to use it. Only GPT-4o-mini improves with more context, gaining 9% from NoCtx to StandardEventInfo. Ten of twelve context-aware models degrade with detailed descriptions, by up to 78% in ct-CRPS. Context effects are also asymmetric: meal tasks benefit in 4 of 6 demographic subgroups, while exercise tasks benefit in none, suggesting failures depend on event type rather than on context generally. Larger models also tend to degrade more than smaller ones within each model family. Despite EventGlucose's balanced design, Type 1 diabetes and middle-aged patients remain harder to predict than other subgroups. EventGlucose is the first benchmark to evaluate time series foundation models and LLMs on event-aware glucose forecasting, and it shows where current models break down when behavioral context is available. The benchmark is available at https://github.com/JHU-CDHAI/EventGlucoseBench.

---

##### Citation

Luo, Junjie, Xuzhe Zhi, Rui Han, Abhimanyu Kumbara, Mansur E. Shomali, Anand K. Iyer, Ritu Agarwal, and Guodong (Gordon) Gao. 2026. "EventGlucose: A Benchmark for Continuous Glucose Monitoring Forecasting with Behavioral Event Context." In *Proceedings of the 32nd ACM SIGKDD Conference on Knowledge Discovery and Data Mining (KDD 2026)*, 9510-9521.

```BibTeX
@inproceedings{luo2026eventglucose,
  title={EventGlucose: A Benchmark for Continuous Glucose Monitoring Forecasting with Behavioral Event Context},
  author={Luo, Junjie and Zhi, Xuzhe and Han, Rui and Kumbara, Abhimanyu and Shomali, Mansur E. and Iyer, Anand K. and Agarwal, Ritu and Gao, Gordon},
  booktitle={Proceedings of the 32nd ACM SIGKDD Conference on Knowledge Discovery and Data Mining},
  pages={9510--9521},
  year={2026},
  doi={10.1145/3770855.3817572}
}
```
