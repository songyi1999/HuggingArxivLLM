# 基于文本的人员检索中合成数据验证的实证研究

发布时间：2025年03月28日

`其他` `计算机视觉` `图像生成`

> An Empirical Study of Validating Synthetic Data for Text-Based Person Retrieval

# 摘要

> 数据在基于文本的人员检索（TBPR）研究中至关重要。当前主流研究范式依赖于带有手动标注的真实人物图像，这不仅涉及隐私问题，还耗费大量人力。尽管一些开创性研究尝试将合成数据引入TBPR，但依然无法摆脱对真实数据的依赖，导致数据多样性不足，进而影响TBPR效果。此外，现有研究视角有限，限制了合成数据潜力的充分挖掘。本文通过实证研究，从三个方面深入探索合成数据在TBPR中的应用潜力。

第一，我们提出了一种跨类图像生成流水线，创新性地引入自动提示构建策略，指导生成式AI模型生成多样化跨类图像，完全摆脱了对原始数据的依赖。第二，我们开发了一套同一类图像增强流水线，利用生成式AI模型对图像进行深度编辑，获取丰富多样的同一类图像。第三，结合所提出的流水线和自动文本生成技术，我们通过大量实验验证了合成数据在多种场景下的有效性。同时，我们深入研究了多种抗噪声学习策略，有效缓解了合成数据的固有噪声问题。为推动TBPR研究发展，我们将开源代码及生成的合成大规模数据集，助力相关研究迈向新高度。

> Data plays a pivotal role in Text-Based Person Retrieval (TBPR) research. Mainstream research paradigm necessitates real-world person images with manual textual annotations for training models, posing privacy-sensitive and labor-intensive issues. Several pioneering efforts explore synthetic data for TBPR but still rely on real data, keeping the aforementioned issues and also resulting in diversity-deficient issue in synthetic datasets, thus impacting TBPR performance. Moreover, these works tend to explore synthetic data for TBPR through limited perspectives, leading to exploration-restricted issue. In this paper, we conduct an empirical study to explore the potential of synthetic data for TBPR, highlighting three key aspects. (1) We propose an inter-class image generation pipeline, in which an automatic prompt construction strategy is introduced to guide generative Artificial Intelligence (AI) models in generating various inter-class images without reliance on original data. (2) We develop an intra-class image augmentation pipeline, in which the generative AI models are applied to further edit the images for obtaining various intra-class images. (3) Building upon the proposed pipelines and an automatic text generation pipeline, we explore the effectiveness of synthetic data in diverse scenarios through extensive experiments. Additionally, we experimentally investigate various noise-robust learning strategies to mitigate the inherent noise in synthetic data. We will release the code, along with the synthetic large-scale dataset generated by our pipelines, which are expected to advance practical TBPR research.

[Arxiv](https://arxiv.org/abs/2503.22171)