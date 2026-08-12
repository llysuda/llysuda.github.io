---
title: "Followbench: A multi-level fine-grained constraints following benchmark for large language models"
collection: publications
category: papersxxxx
permalink: /publication/2024-08-11-followbench
excerpt: 'Yuxin Jiang, Yufei Wang, Xingshan Zeng, Wanjun Zhong, **Liangyou Li**, Fei Mi, Lifeng Shang, Xin Jiang, Qun Liu, Wei Wang'
date: 2024-08-11
venue: 'Proceedings of ACL'
dataurl: 'https://github.com/YJiangcm/FollowBench'
paperurl: 'https://aclanthology.org/2024.acl-long.257.pdf'
---

The ability to follow instructions is crucial for Large Language Models (LLMs) to handle various real-world applications. Existing benchmarks primarily focus on evaluating pure response quality, rather than assessing whether the response follows constraints stated in the instruction. To fill this research gap, in this paper, we propose FollowBench, a Multi-level Fine-grained Constraints Following Benchmark for LLMs. FollowBench comprehensively includes five different types (ie, Content, Situation, Style, Format, and Example) of fine-grained constraints. To enable a precise constraint following estimation on diverse difficulties, we introduce a Multi-level mechanism that incrementally adds a single constraint to the initial instruction at each increased level. To assess whether LLMs’ outputs have satisfied every individual constraint, we propose to prompt strong LLMs with constraint-evolution paths to handle challenging open-ended instructions. By evaluating 13 closed-source and open-source popular LLMs on FollowBench, we highlight the weaknesses of LLMs in instruction following and point towards potential avenues for future work. The data and code are publicly available at https://github.com/YJiangcm/FollowBench.
