# LIME and SHAP as interpretabilty methods for black box models.

A "black-box" model is a machine learning model whose predictions are provided without insight into the internal processes of the algorithm.
These models are often complex and highly accurate but lack direct human interpretability. Examples of black-box models include neural networks (specifically, backpropagation neural networks) and ensemble methods like gradient boosting models due to their intricate complexity. The term "black box" signifies the model's inability to offer clear information about the prediction calculation process, thus limiting interpretability.

In contrast, "white-box" models are known for their easy interpretability and a more causal relationship between input and output variables. Examples of machine learning methods falling into this category include
linear regression, logistic regression, decision trees, Bayesian Networks, and the k-nearest neighbors (k-NN) classifier. White-box models are often simpler but more interpretable. It's important to note that the relationship between model accuracy and interpretability is not straightforward. For example, multiple linear regression is easily interpretable due to its linear nature, making it possible to understand the contribution of each variable to predictions. However, when dealing with a model that involves hundreds of variables, interpretability becomes challenging, highlighting the limitations of white-box models in handling complex datasets.

One common drawback of white-box models is their potential for lower prediction accuracy, especially when dealing with real-world datasets that often exhibit non-linear relationships between features. 
In such cases, more complex black-box models, combined with efforts to ensure interpretability, can provide a more reliable tool. The term "black box" does not imply impossibility but rather significant difficulty in interpretation. Even highly complex models are ultimately based on algorithms and procedures. The challenge lies in the intricacy of the model's internal structure, making it harder to understand. While extracting information from such complexity can be challenging, it is not impossible.

Comparatively, the human brain, when faced with questions and decisions, serves as a tool capable of providing information about various situations. 
However, the human mind also faces limitations in providing clear answers, especially when multiple factors are at play, making it difficult to ascertain the exact cause of certain events. 
Algorithms, with their finite structure and complexity, can offer estimations and calculations based on a large number of parameters, potentially shedding light on how hypotheses were chosen to fit the data. 
Thus, the concept of a "black box" in algorithms does not imply infeasibility but rather the inherent complexity that requires effort to understand fully.
