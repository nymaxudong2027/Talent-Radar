# Talent-Radar
A conceptual paper: Implicit talent profiling and anti-poisoning system based on LLMs. (基于大模型交互轨迹的隐式人才画像与防投毒系统概念论文)
Title:
From Discrete Sampling to Continuous Manifolds: An Implicit Talent Profiling and Anti-Poisoning System Based on LLM Interaction Trajectories

Abstract:
Traditional standardized examinations are inherently low-frequency, low-dimensional discrete samplings of knowledge, making it difficult to accurately assess an individual's interdisciplinary associative abilities and innovative potential. This paper proposes a novel "Implicit Talent Profiling System" (conceptualized as "Talent Radar"). By collecting the trajectory of users' inquiries during human-AI collaboration with Large Language Models (LLMs), the system extracts core features such as the breadth of domains, the depth of follow-up questions, and the iteration rate of error correction. Utilizing Transformer-based models, high-dimensional text interactions are transformed into a "Talent Embedding" vector, which is then matched against benchmark occupational vectors using cosine similarity and K-Means clustering algorithms. Furthermore, to address Goodhart's Law and potential Data Poisoning attacks, this paper introduces a dual-defense mechanism consisting of "implicit data collection" and "dynamic game-theoretic probing." This research provides a new mathematical and algorithmic perspective for future educational evaluation systems and human resource matching.

1. Introduction

Limitations of Traditional Evaluation: Demonstrating the mathematical dimensionality reduction flaws of traditional closed-book exams in assessing high-dimensional latent variables (e.g., creativity, critical thinking).
The New Paradigm of Human-AI Collaboration: Articulating the core concept that "questioning is capability." The questioning trajectory is a continuous manifold mapping of the user in a high-dimensional knowledge space.
2. System Architecture: Vectorization of Talent Features

Multi-dimensional Feature Extraction: Applying information entropy to measure domain span, and calculating the depth of multi-turn dialogues to assess logical inquiry capabilities.
Matrix Vector Mapping: Utilizing deep learning models (e.g., BERT/GPT) to compress and normalize long-term interaction logs into high-dimensional feature vectors.
Similarity Matching Model: Establishing a "benchmark vector library" of top talents and calculating the match rate via vector angle (cosine similarity).
3. Adversarial Security & Defense Mechanisms

Goodhart's Law and Data Poisoning: Analyzing the risk of users utilizing automated scripts or generating fake, profound questions to deceive the system if the evaluation metrics are made public.
Consistency Anomaly Detection: Using statistical algorithms to detect "teleportation" in the high-dimensional space of capability vectors (i.e., knowledge gaps caused by cheating).
Dynamic Game-Theoretic Probing: Triggering random follow-up questions by the system when detecting high-difficulty prompts, acting as a two-way verification to increase the cognitive and time cost of cheating.
4. Conclusion & Future Work

Summarizing how this model reshapes the foundational logic of educational evaluation, and calling for the exploration of a "seamless/implicit" capability assessment paradigm under the premise of privacy protection.

论文题目：
从离散采样到连续流形：基于大语言模型交互轨迹的隐式人才画像与防投毒系统
(From Discrete Sampling to Continuous Manifolds: An Implicit Talent Profiling and Anti-Poisoning System Based on LLM Interaction Trajectories)

摘要 (Abstract)：
传统的标准化考试本质上是一种低频、低维的离散知识采样，难以准确评估个人的跨学科联想能力与创新潜力。本文提出了一种全新的“隐式人才画像系统”（概念名：人才雷达）。该系统通过收集用户与大语言模型（LLM）协同工作时的提问轨迹，将提问的广度、追问深度和纠错迭代率作为核心特征。利用基于 Transformer 的模型将高维文本交互转化为“个人能力特征向量（Talent Embedding）”，并使用余弦相似度与K-Means聚类算法将其与基准职业向量进行匹配。此外，针对“古德哈特定律”及潜在的数据投毒（Data Poisoning）攻击，本文提出了“隐蔽收集”与“动态博弈反问”的双重防御机制。本研究为未来的教育评价体系与人力资源匹配提供了全新的数学与算法视角。

1. 引言 (Introduction)

传统评估的局限性： 证明传统闭卷考试在评估高维隐变量（如创造力、批判性思维）时的数学降维缺陷。
人机协同的新范式： 阐述“提问即能力”的核心理念，提问轨迹是用户在高维知识空间中的连续流形映射。
2. 系统架构：人才特征向量化 (System Architecture)

多维特征提取： 运用信息熵衡量领域跨度，统计多轮对话深度评估逻辑追问能力。
矩阵向量映射： 利用深度学习模型（如BERT/GPT）将长期交互记录压缩归一化为高维特征向量。
相似度匹配模型： 建立顶尖人才“基准向量库”，通过向量夹角计算匹配度。
3. 对抗性安全与防御机制 (Adversarial Security & Defense Mechanisms)

古德哈特定律与数据投毒： 分析如果系统公开，用户可能使用脚本刷单、生成虚假深度问题以欺骗系统的风险。
一致性异常检测： 使用统计学算法检测能力向量的高维空间“瞬移”（即作弊导致的知识断层）。
动态博弈论反问： 系统在检测到高难度提问时，随机生成反问进行双向校验，增加作弊的时间成本和认知门槛。
4. 结论与未来展望 (Conclusion & Future Work)

总结该模型如何重塑教育底层的评价逻辑，呼吁在保护隐私的前提下探索“无感化”的能力测评新范式。
