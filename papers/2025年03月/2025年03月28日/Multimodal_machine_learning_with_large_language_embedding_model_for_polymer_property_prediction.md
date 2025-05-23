# 多模态机器学习结合大语言嵌入模型应用于聚合物性质预测

发布时间：2025年03月28日

`LLM应用` `材料科学` `聚合物`

> Multimodal machine learning with large language embedding model for polymer property prediction

# 摘要

> 当代大型语言模型（LLMs），如GPT-4和Llama，凭借强大的计算能力和多样化的文本语料库，在解读和生成特定领域内容方面表现出色，包括材料科学。为了充分利用这些模型中蕴含的领域知识，我们提出了一种简单而有效的多模态架构——PolyLLMem。该架构整合了Llama 3生成的文本嵌入与Uni-Mol提取的分子结构嵌入，专门用于聚合物性质预测任务。在我们的模型中，针对有限的聚合物数据集，我们在性质预测任务中引入了低秩自适应（LoRA）层，对嵌入进行优化，从而提升其在聚合物SMILES表示法中的化学相关性。这种对文本和结构信息的精细融合，使得PolyLLMem即使在训练数据稀缺的情况下，也能精准预测多种聚合物性质。其性能不仅可与图模型相媲美，在某些情况下甚至超越了通常需要在数百万聚合物样本上进行预训练的Transformer模型。这些发现表明，如Llama这样的LLMs能够有效捕获聚合物PSMILES中编码的化学信息，并证实了将LLM嵌入与分子结构嵌入进行多模态融合的有效性，这不仅克服了数据稀缺性，还加速了先进聚合物材料的发现。

> Contemporary large language models (LLMs), such as GPT-4 and Llama, have harnessed extensive computational power and diverse text corpora to achieve remarkable proficiency in interpreting and generating domain-specific content, including materials science. To leverage the domain knowledge embedded within these models, we propose a simple yet effective multimodal architecture, PolyLLMem, which integrates text embeddings generated by Llama 3 with molecular structure embeddings derived from Uni-Mol, for polymer properties prediction tasks. In our model, Low-rank adaptation (LoRA) layers were also incorporated during the property prediction tasks to refine the embeddings based on our limited polymer dataset, thereby enhancing their chemical relevance for polymer SMILES representation. This balanced fusion of fine-tuned textual and structural information enables PolyLLMem to accurately predict a variety of polymer properties despite the scarcity of training data. Its performance is comparable to, and in some cases exceeds, that of graph-based models, as well as transformer-based models that typically require pretraining on millions of polymer samples. These findings demonstrate that LLM, such as Llama, can effectively capture chemical information encoded in polymer PSMILES, and underscore the efficacy of multimodal fusion of LLM embeddings and molecular structure embeddings in overcoming data scarcity and accelerating the discovery of advanced polymeric materials.

[Arxiv](https://arxiv.org/abs/2503.22962)