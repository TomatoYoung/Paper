# readme
## 关注
- 目标、背景/困难、动机
- 提出了哪些方法
- 在哪些数据集上做了实验

## 论文及链接
### 综述
- MSA: Multimodal sentiment analysis: A systematic review of history, datasets, multimodal fusion methods, applications, challenges and future directions https://w.sentic.net/multimodal-sentiment-analysis-review.pdf
- NLP: Recent Trends of Multimodal Affective Computing: A Survey from NLP Perspective, https://arxiv.org/pdf/2409.07388
- A Systematic Review on Multimodal Emotion Recognition: Building Blocks, Current State, Applications, and Challenges, https://ieeexplore.ieee.org/document/10602503?denied=

### 方法

#### 数据集和评估集制作方案
- Aligned Better, Listen Better For Audio-Visual Large Language Models，https://openreview.net/forum?id=1SYUKPeM12
- Video-MME: The First-Ever Comprehensive Evaluation Benchmark of Multi-modal LLMs in Video Analysis，https://arxiv.org/abs/2405.21075

#### 模型指令微调方案
- Qwen2-VL: Enhancing Vision-Language Model's Perception of the World at Any Resolution，https://arxiv.org/abs/2409.12191
- llama-factory: LLAMAFACTORY: Unified Efficient Fine-Tuning of 100+ Language Models, https://arxiv.org/pdf/2403.13372
  https://llamafactory.readthedocs.io/zh-cn/latest/, https://github.com/hiyouga/LLaMA-Factory

#### 多模态差异导致的噪声分析
- The Curse of Multi-Modalities: Evaluating Hallucinations of Large Multimodal Models across Language, Visual, and Audio，https://arxiv.org/abs/2410.12787 （Hallucination的定义参见：https://www.iguazio.com/glossary/llm-hallucination/ ）

#### 模型低秩微调训练方法
- LoRA: Low-Rank Adaptation of Large Language Models, https://arxiv.org/abs/2106.09685
- LoRA+: Efficient Low Rank Adaptation of Large Models, https://arxiv.org/abs/2402.12354

#### 使大语言模型可以理解视频中的视听内容
- video LLAMA: 

### 算法
#### SAE算法
- 自编码器AutoEncoder，降噪自编码器DAE，稀疏自编码器SAE，变分自编码器VAE 简介, https://www.cnblogs.com/jins-note/p/12883863.html
- SAE, https://cdn.openai.com/papers/sparse-autoencoders.pdf, https://new.qq.com/rain/a/20240607A0101Q00
- SAE算法用于可解释性, https://www.jiqizhixin.com/articles/2024-08-05-5

## 文献矩阵
| 文献 | 研究目标 | 研究方法 | 使用数据集 | 主要结果 | 优点 | 缺点 | 相关性 |
| --- | --- | --- | --- | --- | --- | --- | --- |
