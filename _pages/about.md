---
permalink: /
title: "Changshuo Zhang (张昌硕)"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

我目前是[中国人民大学，高瓴人工智能学院](http://ai.ruc.edu.cn/english/index.htm)的一名硕士二年级（26届）研究生。我在[IIR lab](https://ruc-iir-lab.github.io/)开展研究工作。我的导师是[张骁](https://scholar.google.com/citations?user=5FZ6wbAAAAAJ&hl=zh-CN&oi=ao)副教授和[徐君](https://scholar.google.com/citations?user=su14mcEAAAAJ)教授。我的主要研究兴趣包括推荐系统与强化学习（生成式推荐大模型、时长预估）等。我的微信是：13205201198。

教育经历
======
+ 2019.09~2023.07，本科，电子科技大学，计算机科学与工程学院（计算机科学与技术专业）
  + 专业排名：2/160，GPA：3.89/4.0
+ 2023.09~2026.07，硕士，中国人民大学，高瓴人工智能学院（人工智能专业）
  + 导师：[张骁](https://scholar.google.com/citations?user=5FZ6wbAAAAAJ&hl=zh-CN&oi=ao)副教授、[徐君](https://scholar.google.com/citations?user=su14mcEAAAAJ)教授

求职意向
======

正在投递26届互联网头部计划，意向求职方向：时长预估模型、生成式推荐大模型。

实习经历
======

+ 2024.06~2025.03，快手，策略算法部-用户互动优化组
  + 主导：2\*推全模型，1\*推全策略，4\*LR，1\*新增数据流目标，1\*提出新数据流，中稿WWW一篇。
  + 参与：1\*推全模型。
  + 关键词：视频session时长，互动时机，生成式重排，评论区时长，LT收益。
+ 2025.03~now，Tiktok，Data-Live（直播）
  + 主导：1\*精排主cvr模型备LR，1*精排模型备LR，多个精排主cvr模型迭代中。
  + 参与：二作投稿CIKM一篇，1\*精排模型已LR。
  + 关键词：直播cvr，高时长预估，实时性改善，个性化分位数，低活用户优化。
 
技术栈
======

+ 生成式推荐系统（强化学习for推荐系统）
  + _Better Exploration and exploitation for long-term reward!_
  + KDD + RecSys + SIGIR + NIPS[submitting] + WWW[submitting] + n*LR
+ 奖励模型（时长预估模型）
  + _Provide a better reward!_
  + WWW + CIKM[submitting] + n*LR
+ 其他工作（图神经网络、大语言模型、序列推荐）
  + RecSys + KDD[submitting] + CIKM[submitting] + EMNLP[submitting]

论文发表
======

三篇第一作者中稿论文、四篇第一作者在投论文、七篇工业界验证/推全论文。

+ （第一作者，中稿SIGIR'24，评选为Oral）[Reinforcing Long-Term Performance in Recommender Systems with User-Oriented Exploration Policy](https://dl.acm.org/doi/10.1145/3626772.3657714)
  + 使用强化学习进行个性化分位数优化提高不同活跃度用户体验，提高session深度。
  + Tiktok直播线上验证（ab实验显著）。
+ （第一作者，中稿WWW'25，评选为Oral）[Comment Staytime Prediction with LLM-enhanced Comment Understanding](https://dl.acm.org/doi/10.1145/3701716.3715213)
  + 使用大模型与评论互动信号优化评论区停留时长预估。
  + 快手线上验证（ab实验显著）。
+ （第一作者，中稿RecSys'25，评选为Oral）[Test-Time Alignment for Tracking User Interest Shifts in Sequential Recommendation](https://arxiv.org/abs/2504.01489)
  + 观测到推断时用户会发生兴趣偏移，并在推理时进行自适应调整参数。
  + 在工业界应用有解决实时性问题与更加个性化推荐的前景。
+ （学生二作，中稿SIGKDD'23）[Controllable Multi-Objective Re-ranking with Policy Hypernetworks](https://dl.acm.org/doi/abs/10.1145/3580305.3599796)
  + 离线实验负责人，使用强化学习进行生成式重排序，聚焦在多目标可控推理。
  + 阿里巴巴线上验证（推全），快手线上验证（ab实验显著）。
+ （学生一作，中稿RecSys'24）[Do Not Wait: Learning Re-ranking Model Without User Feedback At Serving Time in E-Commerce](https://dl.acm.org/doi/abs/10.1145/3640457.3688165)
  + 离线实验负责人，使用强化学习进行生成式重排序，聚焦在推理时调整模型参数，先于OpenAI-o1提出，具有前瞻性的工作。
  + 阿里巴巴线上验证（推全）。
+ （单独作者，在投NeurIPS'25）Activity-Driven Quantile Optimization: Dynamic Exploration and Exploitation in Recommender Systems
  + 为不同的用户活跃度设定个性化分位数进行优化，探索低活兴趣并保证高活留存。
  + Tiktok直播线上验证（ab实验显著）。
+ （第二作者，在投CIKM'25）Towards Unbiased and Real-Time Staytime Prediction for Live Streaming Recommendation
  + 提出直播推荐的两大难点：时效性与预估准确性，并提出多塔分类模型进行debias。
  + Tiktok直播现base主精排模型。
+ （学生二作，在投WWW'26）Industry-Scale Online Learning for GLR in E-commerce: An Environment Policy Optimization Approach
  + 离线实验负责人，使用强化学习进行生成式重排序，并流式更新生成器与评估器，并利用评估器（奖励模型/环境）可导的性质深挖评估器，是一种不止对生成式重排序有效，更对大模型优化有前景的做法。
  + 阿里巴巴线上验证（推全）。
+ （第一作者，在投SIGKDD'26）[QAGCF: Graph Collaborative Filtering for Q&A Recommendation](https://arxiv.org/abs/2406.04828)
  + 聚焦在问答推荐场景（类似知乎），使用图神经网络解耦用户-问题-回答三元组关系的协同与语义信号，并借助图滤波器解决高度异质性的问题。
+ （第一作者，在投CIKM'25）[Modeling Domain and Feedback Transitions for Cross-Domain Sequential Recommendation](https://arxiv.org/abs/2408.08209)
  + 聚焦在跨域序列推荐场景，深挖用户发生的跨域与正负反馈转换的行为。
+ （第一作者，在投EMNLP'25）Reward Mixology: Crafting Hybrid Signals for
  Reinforcement Learning Driven In-Context Learning
  + 将示例选取建立为MDP过程，使用强化学习深挖大模型ICL能力。
+ （非第一作者，中稿FCS）[A Survey of Controllable Learning: Methods and Applications in Information Retrieval](https://arxiv.org/abs/2407.06083)
  + 可控信息检索综述，旨在让推荐模型在无需重新训练的情况下，动态适应不断变化的任务目标，应对复杂多变的用户/平台需求。

荣誉证书
======

+ 2020-2021 国家奖学金
+ 四川省优秀大学毕业生
+ 第十二届蓝桥杯大赛软件组全国总决赛 国家级一等奖（前 0.5%）
+ 2021 高教社杯全国大学生数学建模竞赛 国家级二等奖（前 2.78%）
+ 2021 美国大学生数学建模竞赛 Meritorious Winner（前 7%）
+ CCF 计算机软件能力认证 350 分（前 1.93%）
+ 第三届算法设计与编程挑战赛 银奖（前 15%）

技术专长
======

+ 编程语言: C、C++、Matlab、Python、Java、SQL。
+ 算法: [LeetCode](https://leetcode.cn/u/lyingcs/)网站 TOP3.2%、解题 800+。
+ 英语: CET4 与CET6通过。
+ 其他技能: Git、Vim、Latex、Linux、TensorFlow、Pytorch、Qt 等等。

工作经历
======

本科阶段曾担任**学习委员**并连续两年评选为**“优秀班干部”**且曾获学生会**“优秀部员”**称号，研究生阶段担任**校职业发展部部员**。
