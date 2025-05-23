# 应对分布漂移的 LLM 对齐：鲁棒优化的应用

发布时间：2025年04月08日

`LLM理论` `人工智能` `机器学习`

> Leveraging Robust Optimization for LLM Alignment under Distribution Shifts

# 摘要

> 大型语言模型 (LLMs) 通过偏好对齐方法引导输出符合人类价值观，但受限于高质量标注数据的稀缺性。近期研究转向利用 LLM 生成的合成数据作为替代方案，但合成数据可能引发分布偏移，损害细腻的人类偏好。本文提出了一种新型分布感知优化框架，旨在提升偏好对齐效果。方法借助分类器估计目标与训练分布的似然比，并在目标偏好分布数据区域上最小化最坏情况损失。通过优化过程中优先考虑目标分布，我们的方法有效缓解了分布变化的影响，增强了生成忠实反映人类价值观的响应能力。

> Large language models (LLMs) increasingly rely on preference alignment methods to steer outputs toward human values, yet these methods are often constrained by the scarcity of high-quality human-annotated data. To tackle this, recent approaches have turned to synthetic data generated by LLMs as a scalable alternative. However, synthetic data can introduce distribution shifts, compromising the nuanced human preferences that are essential for desirable outputs. In this paper, we propose a novel distribution-aware optimization framework that improves preference alignment in the presence of such shifts. Our approach first estimates the likelihood ratios between the target and training distributions leveraging a learned classifier, then it minimizes the worst-case loss over data regions that reflect the target human-preferred distribution. By explicitly prioritizing the target distribution during optimization, our method mitigates the adverse effects of distributional variation and enhances the generation of responses that faithfully reflect human values.

[Arxiv](https://arxiv.org/abs/2504.05831)