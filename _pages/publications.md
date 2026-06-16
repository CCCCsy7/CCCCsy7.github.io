---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

## Preprints & Workshop Papers

**ContextLeak: Auditing Leakage in Private In-Context Learning Methods**  
Jacob Choi&#42;, Shuying Cao&#42;, Xingjian Dong&#42;, Amin Banayeeanzade, Wang Bill Zhu, Robin Jia, and Sai Praneeth Karimireddy  
*Equal contribution*  
*arXiv preprint arXiv:2512.16059; ACL 2025 L2M2 Workshop*  
[arXiv](https://arxiv.org/abs/2512.16059)

ContextLeak is an empirical auditing framework for measuring information leakage in private in-context learning methods. The project studies whether sensitive information contained in in-context examples can still be exposed through model outputs, even when privacy-preserving mechanisms or heuristic defenses are applied.

Our approach uses canary insertion and targeted adversarial queries to probe worst-case leakage behavior. By designing different types of canaries and query strategies, ContextLeak provides a systematic way to evaluate how much private information may be recoverable from model responses under different privacy mechanisms, model families, and task settings.

We evaluate ContextLeak across both classification and open-ended generation tasks, including private ICL mechanisms with theoretical guarantees and heuristic defenses. The results highlight the gap between theoretical privacy protection and empirical leakage behavior, and show the importance of auditing deployed LLM systems beyond relying only on formal guarantees.
