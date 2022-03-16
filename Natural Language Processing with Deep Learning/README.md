# [Generating Robustness: Exploring Various Ways to Adapt Question Answering to New Domains](Natural%20Language%20Processing%20with%20Deep%20Learning)

[Link to Report](/Natural%20Language%20Processing%20with%20Deep%20Learning/Report%20-%20Generating%20Robustness.pdf)
[Link to Poster](/Natural%20Language%20Processing%20with%20Deep%20Learning/Academic%20Poster%20-%20Generating%20Robustness.pdf)

Class: [CS 224N](https://web.stanford.edu/class/cs224n/) - Natural Language Processing with Deep Learning

Code: Private Github due to Default Final Project

Question Answering (QA), or the task of asking a model to answer a question correctly given a passage, is one of the most promising areas in NLP. However, state-of-the-art QA models tend to overfit to training data and do not generalize well to new domains, requiring additional training on domain-specific datasets to adapt. In this project, we aim to design a QA system that is robust to domain shifts and can perform well on out-of-domain (OOD) fewshot data.

We implement a variety of techniques that boost the robustness of a QA model trained with domain adversarial learning and evaluated on out-of-domain data, yielding a 16% increase in F1 score in development and 10% increase in test. We find that the following innovations boost model performance: 1) finetuning the model on augmented out-of-domain augmented data, 2) aggregating Wikipedia type datasets during adversarial training to simplify the domain discriminator’s task, and 3) supplementing the training data with synthetic QA pairs generated with roundtrip consistency. We also ensemble the best-performing models on each dataset and find that ensembling yields further performance increases.