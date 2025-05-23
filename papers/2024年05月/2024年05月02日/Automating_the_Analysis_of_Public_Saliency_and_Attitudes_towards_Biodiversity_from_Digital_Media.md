# 自动化地从数字媒体中分析公众对生物多样性的关注点和态度

发布时间：2024年05月02日

`LLM应用` `生物多样性保护`

> Automating the Analysis of Public Saliency and Attitudes towards Biodiversity from Digital Media

# 摘要

> 探索公众对野生动物的看法对于理解我们与自然界的联系至关重要，也有助于跟踪全球生物多样性目标的实现情况。然而，在全球范围内进行这样的评估并非易事。传统的通过手动筛选搜索词来查询新闻和社交媒体不仅耗时耗力，还可能导致有偏差的结果。此外，检索到的原始数据往往混杂着大量无关信息和转载文章。为了应对这些挑战，我们采用了先进的自然语言处理（NLP）技术。我们提出了一种基于民间分类法的搜索词生成方法，并利用余弦相似度结合词频-逆文档频率（TF-IDF）向量来筛选掉转载内容。我们还开发了一个可扩展的相关性过滤流程，该流程首先通过无监督学习识别常见主题，然后利用开源的零样本大型语言模型（LLM）为新闻标题自动分配主题，进而确定其相关性。最后，我们对筛选后的数据进行了情感、主题和数量分析。我们通过一个案例研究，分析了 COVID-19 大流行期间关于某些哺乳动物（如蝙蝠、穿山甲、大象和大猩猩）的新闻和社交媒体数据，展示了我们的方法。研究发现，在数据收集期间，高达 62% 的含有蝙蝠关键词的文章与生物多样性无关，这凸显了相关性过滤的必要性。在大流行初期，我们注意到与马蹄蝠（被认为与大流行有关）相关的文章数量激增，情感倾向也发生了显著变化，而其他研究对象则未出现这种情况。这些方法为保护工作者提供了新的途径，使他们能够利用现成的现代和新兴的 NLP 工具，包括 LLM，来分析公众在当前事件或活动中对生物多样性的看法。

> Measuring public attitudes toward wildlife provides crucial insights into our relationship with nature and helps monitor progress toward Global Biodiversity Framework targets. Yet, conducting such assessments at a global scale is challenging. Manually curating search terms for querying news and social media is tedious, costly, and can lead to biased results. Raw news and social media data returned from queries are often cluttered with irrelevant content and syndicated articles. We aim to overcome these challenges by leveraging modern Natural Language Processing (NLP) tools. We introduce a folk taxonomy approach for improved search term generation and employ cosine similarity on Term Frequency-Inverse Document Frequency vectors to filter syndicated articles. We also introduce an extensible relevance filtering pipeline which uses unsupervised learning to reveal common topics, followed by an open-source zero-shot Large Language Model (LLM) to assign topics to news article titles, which are then used to assign relevance. Finally, we conduct sentiment, topic, and volume analyses on resulting data. We illustrate our methodology with a case study of news and X (formerly Twitter) data before and during the COVID-19 pandemic for various mammal taxa, including bats, pangolins, elephants, and gorillas. During the data collection period, up to 62% of articles including keywords pertaining to bats were deemed irrelevant to biodiversity, underscoring the importance of relevance filtering. At the pandemic's onset, we observed increased volume and a significant sentiment shift toward horseshoe bats, which were implicated in the pandemic, but not for other focal taxa. The proposed methods open the door to conservation practitioners applying modern and emerging NLP tools, including LLMs "out of the box," to analyze public perceptions of biodiversity during current events or campaigns.

![自动化地从数字媒体中分析公众对生物多样性的关注点和态度](../../..//opt/data/Projects/HuggingArxiv/paper_images/2405.01610/data-pipeline.png)

![自动化地从数字媒体中分析公众对生物多样性的关注点和态度](../../..//opt/data/Projects/HuggingArxiv/paper_images/2405.01610/folk-taxonomy-carnivora-lion-cluster.png)

![自动化地从数字媒体中分析公众对生物多样性的关注点和态度](../../..//opt/data/Projects/HuggingArxiv/paper_images/2405.01610/relevance-scraped-original-sankey-3.png)

![自动化地从数字媒体中分析公众对生物多样性的关注点和态度](../../..//opt/data/Projects/HuggingArxiv/paper_images/2405.01610/gorilla_relevant_volume_choropleth.png)

![自动化地从数字媒体中分析公众对生物多样性的关注点和态度](../../..//opt/data/Projects/HuggingArxiv/paper_images/2405.01610/pangolin_relevant_volume_choropleth.png)

![自动化地从数字媒体中分析公众对生物多样性的关注点和态度](../../..//opt/data/Projects/HuggingArxiv/paper_images/2405.01610/pipistrelle_relevant_volume_choropleth.png)

![自动化地从数字媒体中分析公众对生物多样性的关注点和态度](../../..//opt/data/Projects/HuggingArxiv/paper_images/2405.01610/x1.png)

![自动化地从数字媒体中分析公众对生物多样性的关注点和态度](../../..//opt/data/Projects/HuggingArxiv/paper_images/2405.01610/VolumeMain.jpeg)

![自动化地从数字媒体中分析公众对生物多样性的关注点和态度](../../..//opt/data/Projects/HuggingArxiv/paper_images/2405.01610/SentMain.jpeg)

![自动化地从数字媒体中分析公众对生物多样性的关注点和态度](../../..//opt/data/Projects/HuggingArxiv/paper_images/2405.01610/x2.png)

![自动化地从数字媒体中分析公众对生物多样性的关注点和态度](../../..//opt/data/Projects/HuggingArxiv/paper_images/2405.01610/allVolume.jpeg)

![自动化地从数字媒体中分析公众对生物多样性的关注点和态度](../../..//opt/data/Projects/HuggingArxiv/paper_images/2405.01610/allSentiment.jpeg)

[Arxiv](https://arxiv.org/abs/2405.01610)