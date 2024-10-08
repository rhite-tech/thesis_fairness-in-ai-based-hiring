# AI-Based Hiring

This repository corresponds to the Master's thesis in Artificial Intelligence by Alexia Muresan, at University of Amsterdam, 2024. This research is part of a project on Bias Identification methods initiated by Rhite and has been guided and supervised by Rhite and the University of Amsterdam.

The research explores whether LLMs mitigate or amplify bias in hiring decisions

**⚠️ Note on Code Quality**

Please note that this code was developed as part of a thesis project and, due to time constraints, has not undergone extensive optimization or formal quality checks. While it serves the primary purpose of supporting the research findings, it may not meet industry standards in terms of performance, maintainability, security or robustness.

Users are welcome to use and explore the code, but we recommend careful consideration and further testing before applying it in any production environment. Contributions for improvements or optimizations are also encouraged.

## Files

This repository contains the following files

### Thesis

* `AI-Based Hiring LLMs and Tradicional AI_AM.pdf`

### Initial versions of code used in the bias evaluations

* `bias_eval_BERT_ethnicity.ipynb`
* `bias_eval_BERT_gender.ipynb`
* `bias_eval_GPT_ethnicity.ipynb`
* `bias_eval_GPT_gender.ipynb`
* `bias_eval_trad_models_ethnicity.ipynb`
* `bias_eval_trad_models_gender.ipynb`

**Note**: this is the code only for scenario 2 (train of biased data, test on balanced data).
The rest of the results can be reproduced by simply changing the datsets used in the notebooks.

### Synthetically generated datasets

* **balanced**: `balanced_resumes_final.csv`
* **gender biased**: `gender_biased_final.csv`
* **biased in terms of ethnicity**: `ethnicity_biased_final.csv`

### Code used to generate the synthetic datasets

* `dataset_generation.ipynb`

### Code used to compute the number of trainable parameters in the instances of traditional models used in this thesis

* `parameter_calculation.ipynb`

The number of parameters for the LLMs is considered common knowledge/found online, not directly computed.
