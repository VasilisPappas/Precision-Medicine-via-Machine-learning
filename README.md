# Predicting dementia and anxiety
This project demonstrates the application of supervised learning techniques, specifically **tree-based algorithms** like Random Forests and XG Boosting trees, in conjunction with interpretability methods, *LIME* and *SHAP*. 
The study utilizes real-world data from individuals aged 50 and above, dealing with depressive syndromes or forms of dementia.

The dataset includes 504 patients, both males and females, who sought psychological and mental health assessment at the University General Hospital of Patras (UGHP).
Data collection was overseen by Associate Professor Alexopoulos Panagiotis from UGHP's Special Clinic of Psychiatry and Early Diagnosis of Neurological Disorders. 
Patients underwent comprehensive neuropsychological assessments (take a look: ['Diagnostic tools'](https://github.com/VasilisPappas/Precision-Medicine-via-Machine-learning/blob/main/Diagnostic%20tools.md)) divided into two categories: **neuropsychiatric** indicators related to psychiatric and depressive symptoms 
and **neurocognitive** indicators evaluating cognitive brain function, memory and abilities.


The central aim is to refine questionnaires, maintaining efficacy through question reduction. 
By leveraging 61 variables like age, sex (a.k.a. gender), education and diagnosis, the objective is to categorize patients using their responses or those provided by their caregivers.
The **diagnosis** variable has four classes: 

* 0: normal diagnosis 

* 1: mild cognitive impairment (MCI)

* 2: dementia due to Alzheimer's disease (AD)

* 3: other types of dementia or pre-dementia syndromes like Parkinson's disease dementia or vascular dementia. 

### Precision (or personalized) medicine employs comprehensive EHR data (Electronic Health Records), encompassing demographic features and biomarkers, to facilitate tailored medical interventions. Although this dataset lacks biomarkers and sufficient demographic data, it serves as an initial foray into precision medicine, where patients are distinguished based on a growing array of variables.

*Further details about the entire project can be found in my master's thesis (available in Greek): [Machine learning in precision medicine](https://nemertes.library.upatras.gr/handle/10889/24195).
Additionally, the pertinent code implemented in the Python programming language, is provided through: [Descriptive Statistics](https://github.com/VasilisPappas/Precision-Medicine-via-Machine-learning/blob/main/Descriptive%20Statistics.ipynb), [Classification decision tree](https://github.com/VasilisPappas/Precision-Medicine-via-Machine-learning/blob/main/Classification%20decision%20tree.ipynb), [Classification Random Forest algorithm](https://github.com/VasilisPappas/Precision-Medicine-via-Machine-learning/blob/main/Classification%20Random%20Forest%20algorithm.ipynb), [Classification AdaBoost algorithm](https://github.com/VasilisPappas/Precision-Medicine-via-Machine-learning/blob/main/Classification%20AdaBoost%20algorithm.ipynb), [Classification Gradient Boosting algorithm](https://github.com/VasilisPappas/Precision-Medicine-via-Machine-learning/blob/main/Classification%20Gradient%20Boosting%20algorithm.ipynb) and [Classification XGBoost algorithm](https://github.com/VasilisPappas/Precision-Medicine-via-Machine-learning/blob/main/Classification%20XGBoost%20algorithm.ipynb).*
