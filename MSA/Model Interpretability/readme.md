# Readme
## 模型的可解释性
人类能通过算法（或其他方法）理解模型的决策过程和结果的程度。
### 博客
- 模型可解释性的详尽介绍，https://www.jiqizhixin.com/articles/2019-10-30-9
## 模型可解释性算法
### Sparse Autoencoder
#### 定义
稀疏自编码算法，简称SAE
#### 论文
- 在国际象棋背景下讨论如何通过语言模型的稀疏自编码器来提取可解释的潜在特征，
  Measuring Progress in Dictionary Learning for Language Model Interpretability with Board Game Models, https://arxiv.org/pdf/2408.00113
  SAE可以用来解开（disentangle）语言模型表示中的可解释特征，但是缺乏明确的“真实”的特征集合来验证SAE提取的特征。本文提出采用结构化的数据来进行实验，这些数据天然有可解释的特征。并且，本文提出了一种新的SAE训练技术：p-annealing。
- Sparse Autoencoders Find Highly Interpretable Features in Language Models, https://arxiv.org/abs/2309.08600
#### 博客
- 讲解稀疏自编码器如何工作，https://www.jiqizhixin.com/articles/2024-08-05-5
- https://github.com/shehper/sparse-dictionary-learning
