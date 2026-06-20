---
title: "CLASS: Collaborative Lesson Plan Generation Agents With Skill-Structure Co-Evolution"
collection:
category: underreview
permalink: /publication/CLASS
excerpt: '<img src="/files/CLASS/framework.pdf" alt="Teaser Image" width="70%" style="border-radius: 5px;"><br> Personalized lesson plan generation requires coordinating multiple pedagogical skills under diverse learner profiles, yet existing systems based on large language models (LLMs) typically rely on fixed agent roles and rigid collaboration structures. To address this, we propose CLASS, a multi-agent framework that enables the co-evolution of skills and collaborative structures through a "Generate-Evaluate-Evolve" closed-loop.'
date: 2026-05-20
venue:
projecturl: /publication/projectpage/CLASS
paperurl:
codeurl:
arxivurl:
slidesurl:
videourl:
bibtexurl:
authors: 'Bowen Yang*, Haoran Ji*, Ruohan Wang, Xixian Chen, Fangwei Zhong<sup><i class="fas fa-envelope"></i></sup>'
---

Personalized lesson plan generation requires coordinating multiple pedagogical skills under diverse learner profiles, yet existing systems based on large language models (LLMs) typically rely on fixed agent roles and rigid collaboration structures. To address this, we propose CLASS, a multi-agent framework that enables the co-evolution of skills and collaborative structures through a "Generate-Evaluate-Evolve" closed-loop. CLASS employs a two-stage search strategy, combining tree-based local exploration for task decomposition and skill acquisition with graph-based global optimization for flexible coordination and escaping local optima. Additionally, we introduce a student modeling method based on a capability tree and construct a unified objective function to balance instructional plan quality, alignment with learner profiles, and computational cost. Experimental results under an LLM-based simulated student evaluation framework show that CLASS achieves a 25.1% average improvement over the Single Agent baseline across four benchmark datasets (Algebra, MBPP, GSM8K, and RACE), while maintaining a favorable performance–cost trade-off. Through skill-structure co-evolution, CLASS attains state-of-the-art performance among the compared methods within this evaluation setting.
