### Artificial Intelligence in Clinical Pharmacology: A Primer 

In this repository, we provide further details on the exemplar binary classification model detailed in the paper. 

This model is built using publicly available data from over 20,000 participants in the US National Health and Nutritional Survey (NHANES 2007 - 2016) to predict dysglycaemia (composite of either abnormal oral glucose tolerance test or elevated glycated haemoglobin (HbA1c)  ≥ 48 mmol/mol), which could be utilised to inform health interventions and titration of anti-diabetic medicines. 

This model is purely for educational purposes and is not intended for clinical practice. As such, the focus is on clinical decisions and potential pitfalls which extend beyond this binary classification model. The data and code are publically available for readers. 

Coding notebook in python is available: https://github.com/dkdryan/ai_cpt/blob/main/ai_development.ipynb

To replicate the python package enviroment and ensure the notebook runs successfully, use the provided conda environment file `ai_cpt_env.yaml`. To set up the conda environment, run the following on the the command line, after installing conda:

```bash
conda env create --file ai_cpt_env.yaml
```
