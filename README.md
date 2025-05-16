# FAKD-XAI
FAKD-XAI: Feature-Aligned Knowledge Distillation with Explainable AI for Efficient Brain Tumor Classification
## Abstract
# Feature-Aligned Knowledge Distillation with XAI (FAKD-XAI)

Accurate and efficient classification of brain tumors by magnetic resonance imaging (MRI) scans is essential for clinical follow-up and treatment planning. However, in deep learning models, computational costs are often a significant barrier to practical application. This paper presents **Feature-Aligned Knowledge Distillation with XAI (FAKD-XAI)**, a novel framework that classifies and rationally interprets brain tumors in an efficient manner. FAKD-XAI combines logit-level Knowledge Distillation with an adaptive intermediate feature-level distillation from **ResNet-50 (Teacher Model)** to a lightweight **MobileNetV3-Large (Student Model)** to facilitate learning between complex and simple models. Our alignment module featuring a `1×1` convolution layer was able to overcome the architectural divergences of the student model and enabled the efficient use of stratified feature transfer at different levels of the hierarchy. FAKD-XAI integrates **Local Interpretable Model-agnostic Explanations (LIME)**, which enhances the understanding of the workings behind model predictions, promoting trust from clinicians. FAKD-XAI achieved an **accuracy of 99.47%** on the Brain Tumor MRI dataset while remaining computationally efficient for practical, clinical deployment. The use of **Explainable AI (XAI)** confirms that the model focuses on pertinent tumor areas, suggesting FAKD-XAI’s usefulness as a reliable diagnostic aid.


Dataset: [Brain Tumor MRI Dataset from Kaggle](https://www.kaggle.com/datasets/masoudnickparvar/brain-tumor-mri-dataset)


## FAKD-XAI Framework

![](https://www.googleapis.com/download/storage/v1/b/kaggle-forum-message-attachments/o/inbox%2F19186184%2F4348607d22bdf346d095c61105ba4a59%2FFAKD-XAI.png?generation=1746009023884310&alt=media)


