# MuQ：利用梅尔残差向量量化实现自监督音乐表示学习

发布时间：2025年01月02日

`其他

理由：这篇论文主要讨论的是自监督学习在音乐信息理解任务中的应用，特别是提出了一种名为MuQ的自监督音乐表示学习模型。虽然论文中提到了对比学习和联合音乐-文本嵌入模型，但这些内容与Agent、RAG、LLM应用、LLM理论等分类没有直接关联。因此，这篇论文更适合归类为其他。` `信息检索`

> MuQ: Self-Supervised Music Representation Learning with Mel Residual Vector Quantization

# 摘要

> # 摘要
近年来，基于自监督学习（SSL）预训练的基础模型在音乐标签、乐器分类、调性检测等音乐信息理解任务中表现出色。本文提出了一种名为MuQ的自监督音乐表示学习模型。与以往研究不同，MuQ通过预测梅尔残差向量量化（Mel-RVQ）生成的标记进行训练。Mel-RVQ采用残差线性投影结构对梅尔频谱进行量化，提升了目标提取的稳定性和效率，从而带来更优的性能。实验表明，MuQ仅用0.9K小时的开源预训练数据便在多种下游任务中超越了之前的自监督音乐表示模型。通过将数据扩展到160K小时以上并采用迭代训练，模型性能持续提升。此外，我们还提出了基于对比学习的联合音乐-文本嵌入模型MuQ-MuLan，在MagnaTagATune数据集的零样本音乐标签任务中达到了最先进的性能。代码和检查点已开源：https://github.com/tencent-ailab/MuQ。

> Recent years have witnessed the success of foundation models pre-trained with self-supervised learning (SSL) in various music informatics understanding tasks, including music tagging, instrument classification, key detection, and more. In this paper, we propose a self-supervised music representation learning model for music understanding. Distinguished from previous studies adopting random projection or existing neural codec, the proposed model, named MuQ, is trained to predict tokens generated by Mel Residual Vector Quantization (Mel-RVQ). Our Mel-RVQ utilizes residual linear projection structure for Mel spectrum quantization to enhance the stability and efficiency of target extraction and lead to better performance. Experiments in a large variety of downstream tasks demonstrate that MuQ outperforms previous self-supervised music representation models with only 0.9K hours of open-source pre-training data. Scaling up the data to over 160K hours and adopting iterative training consistently improve the model performance. To further validate the strength of our model, we present MuQ-MuLan, a joint music-text embedding model based on contrastive learning, which achieves state-of-the-art performance in the zero-shot music tagging task on the MagnaTagATune dataset. Code and checkpoints are open source in https://github.com/tencent-ailab/MuQ.

[Arxiv](https://arxiv.org/abs/2501.01108)