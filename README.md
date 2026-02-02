# BP-and-EEG-Correlation-Analysis

Jupyter pipeline for BP and EEG correlation analysis, as well as example of input and output signals. Pipeline takes simultaneously recorded EEG and BP signals, cleans and segments them based on stimuli markers, extracts different EEG frequencies with filtering, and computes Spearman correlations between each EEG variable and each BP variable to identify relationships between neural and cardiovascular activity.

## Correlations with low p-values

| Brain Region (EEG) | BP (General) | BP Systolic | BP Diastolic | BP Mean |
| :--- | :---: | :---: | :---: | :---: |
| **AF7–AF8** | 0.072 | -0.150 | -0.140 | -0.144 |
| **TP9–TP10** | -0.155 | -0.051 | -0.187 | -0.140 |
