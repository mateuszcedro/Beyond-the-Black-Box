# Beyond the Black Box
This repository contain research paper and supplementary code associated with the article *Beyond the Black Box: Do More Complex Models Provide Superior XAI Explanations?* (Cedro, Chlebus 2024)

## Abstract
The increasing complexity of Artificial Intelligence models poses challenges to interpretability, particularly in healthcare sector. This study investigates the impact of the deep learning models complexity and Explainable AI (XAI) efficacy, utilizing four ResNet architectures (ResNet-18, 34, 50, 101). Through methodical experimentation on 4,369 lung X-ray images of COVID-19-infected and healthy patients, the research evaluates models' classification performance and the relevance of corresponding XAI explanations with respect to the ground-truth disease masks. Results indicate that the increase in model complexity is associated with the decrease in classification accuracy and AUC-ROC scores (ResNet-18: 98.4\%, 0.997, ResNet-101: 95.9\%, 0.988). Notably, in eleven out of twelve statistical tests performed, no statistically significant differences occurred between XAI quantitative metrics - Relevance Rank Accuracy and proposed Positive Attribution Ratio - across trained models. These results suggest that increased model complexity does not consistently lead to higher performance or the relevance of explanations of models’ decision-making processes.

![grads](https://github.com/mateuszcedro/Beyond-the-Black-Box/blob/main/notebook/imgs/grads.png)

![grads](https://github.com/mateuszcedro/Beyond-the-Black-Box/blob/main/notebook/imgs/workflow_schema.png)

Note that the model representation is illustrative and may not precisely reflect the original and specific number and type of layers of each model.
