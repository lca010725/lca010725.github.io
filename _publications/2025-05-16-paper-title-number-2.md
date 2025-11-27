---
title: "Gradient-Adaptive Policy Optimization: Towards Multi-Objective Alignment of Large Language Models"
collection: publications
category: conferences
permalink: /publication/2025-05-16-paper-title-number-2
excerpt: '**Chengao Li**, Hanyu Zhang, Yunkun Xu, Hongyan Xue, Xiang Ao*, and Qing He*.'
date: 2025-05-16
venue: 'Proceedings of the 63rd Annual Meeting of the Association for Computational Linguistics (ACL 2025)'
# slidesurl: 'https://academicpages.github.io/files/slides2.pdf'
paperurl: 'https://lca010725.github.io/files/ACL2025_paper.pdf'
citation: 'Chengao Li, Hanyu Zhang, Yunkun Xu, Hongyan Xue, Xiang Ao, and Qing He. 2025. Gradient-Adaptive Policy Optimization: Towards Multi-Objective Alignment of Large Language Models. In Proceedings of the 63rd Annual Meeting of the Association for Computational Linguistics (Volume 1: Long Papers), pages 11214–11232, Vienna, Austria. Association for Computational Linguistics.'
---

`Abstract` Reinforcement Learning from Human Feedback (RLHF) has emerged as a powerful technique for aligning large language models (LLMs) with human preferences. However, effectively aligning LLMs with diverse human preferences remains a significant challenge, particularly when they are conflict. To address this issue, we frame human value alignment as a multi-objective optimization problem, aiming to maximize a set of potentially conflicting objectives. We introduce Gradient-Adaptive Policy Optimization (GAPO), a novel fine-tuning paradigm that employs multiple-gradient descent to align LLMs with diverse preference distributions. GAPO adaptively rescales the gradients for each objective to determine an update direction that optimally balances the trade-offs between objectives. Additionally, we introduce P-GAPO, which incorporates user preferences across different objectives and achieves Pareto solutions that better align with the user's specific needs.
