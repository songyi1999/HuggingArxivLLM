# OMCAT：全场景智能Transformer

发布时间：2024年10月15日

`LLM应用` `多媒体` `人工智能`

> OMCAT: Omni Context Aware Transformer

# 摘要

> 大型语言模型 (LLM) 在文本生成和理解方面取得了显著进展，最近更是扩展到多模态领域，集成了视觉和音频输入。然而，这些模型在细粒度的跨模态时间理解上仍显不足，尤其是在音频和视频流之间关联事件时。为此，我们推出了两个关键成果：OCTAV 数据集和 OMCAT 模型。OCTAV 旨在捕捉音频和视频间的事件过渡，而 OMCAT 则通过创新的 RoTE 技术，提升了时间锚定任务的效率和准确性。经过三阶段训练——特征对齐、指令调优和 OCTAV 特定训练——OMCAT 在跨模态时间理解上表现卓越。我们的模型在 AVQA 任务和 OCTAV 基准测试中均达到最先进水平，显著提升了时间推理和跨模态对齐能力。所有数据集和代码将公开发布，演示页面链接为 https://om-cat.github.io。

> Large Language Models (LLMs) have made significant strides in text generation and comprehension, with recent advancements extending into multimodal LLMs that integrate visual and audio inputs. However, these models continue to struggle with fine-grained, cross-modal temporal understanding, particularly when correlating events across audio and video streams. We address these challenges with two key contributions: a new dataset and model, called OCTAV and OMCAT respectively. OCTAV (Omni Context and Temporal Audio Video) is a novel dataset designed to capture event transitions across audio and video. Second, OMCAT (Omni Context Aware Transformer) is a powerful model that leverages RoTE (Rotary Time Embeddings), an innovative extension of RoPE, to enhance temporal grounding and computational efficiency in time-anchored tasks. Through a robust three-stage training pipeline-feature alignment, instruction tuning, and OCTAV-specific training-OMCAT excels in cross-modal temporal understanding. Our model demonstrates state-of-the-art performance on Audio-Visual Question Answering (AVQA) tasks and the OCTAV benchmark, showcasing significant gains in temporal reasoning and cross-modal alignment, as validated through comprehensive experiments and ablation studies. Our dataset and code will be made publicly available. The link to our demo page is https://om-cat.github.io.

[Arxiv](https://arxiv.org/abs/2410.12109)