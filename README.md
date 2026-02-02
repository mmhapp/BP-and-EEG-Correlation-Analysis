# BP-and-EEG-Correlation-Analysis

Jupyter pipeline for BP and EEG correlation analysis, as well as example of input and output signals. Pipeline takes simultaneously recorded EEG and BP signals, cleans and segments them based on stimuli markers, extracts different EEG frequencies with filtering, and computes Spearman correlations between each EEG variable and each BP variable to identify relationships between neural and cardiovascular activity.


Correlations with low p-values:

                    BP    BP sys    BP dia   BP mean
AF7–AF8 EEG   0.071943   -0.1503 -0.139837 -0.144425
TP9–TP10 EEG -0.154539 -0.051374 -0.187051 -0.140057
