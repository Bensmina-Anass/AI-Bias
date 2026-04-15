# AI Bias Awareness: The COMPAS Case Study

An educational Jupyter notebook exploring how artificial intelligence can amplify human injustice, using the real-world COMPAS recidivism dataset as a case study.

## Overview

This project investigates racial bias in the COMPAS (Correctional Offender Management Profiling for Alternative Sanctions) algorithm — a tool used in the U.S. criminal justice system to predict the likelihood of reoffending. It walks through data exploration, statistical analysis, and bias detection to illustrate how algorithmic bias manifests in practice.

## Contents

| File | Description |
|------|-------------|
| `AI_Bias_Awareness.ipynb` | Main notebook — data exploration, analysis, and bias detection |
| `Identifying_Bias_in_AI.md` | Reference guide covering six types of ML bias |
| `archive/cox-violent-parsed.csv` | COMPAS dataset (ProPublica, 2016) |

## Topics Covered

- The illusion of objectivity in algorithmic decision-making
- Six types of ML bias: Historical, Representation, Measurement, Aggregation, Evaluation, and Deployment
- Exploratory data analysis on the COMPAS dataset
- Racial disparities in risk score distributions
- How proxy variables can encode discrimination even without explicit demographic features

## Requirements

```bash
pip install pandas numpy matplotlib seaborn
```

Then open the notebook:

```bash
jupyter notebook AI_Bias_Awareness.ipynb
```

## Dataset

The dataset is sourced from [ProPublica's 2016 investigation](https://www.propublica.org/article/machine-bias-risk-assessments-in-criminal-sentencing) into the COMPAS algorithm. It contains records of defendants from Broward County, Florida, including demographics, prior offense counts, COMPAS risk scores, and actual recidivism outcomes.

## References

- ProPublica — *Machine Bias* (2016)
- Kaggle — *Intro to AI Ethics*, Alexis Cook
- Barocas, S., Hardt, M., & Narayanan, A. — *Fairness and Machine Learning* (2019)
