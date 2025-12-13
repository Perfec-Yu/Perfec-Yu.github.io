---
layout: single
title: Research
permalink: /research/
author_profile: true
mathjax: true
---

## Featured Publications

Publications here are selected and ranked based on my personal preference instead of citations or venues. For a complete list, please visit my [Google Scholar Profile](https://scholar.google.com/citations?user=bFbykBYAAAAJ&hl=en). 

<div class="notice" markdown="1">
**Information Association for Language Model Updating by Mitigating LM-Logical Discrepancy**  
--_**Pengfei Yu**, Heng Ji (CoNLL 2024)_  [paper](https://aclanthology.org/2024.conll-1.10/)

I completed the first version of this project in 2023, right after ChatGPT was released. From today’s perspective, the experiments are not as comprehensive as I would like. Although the paper didn’t land at a top venue, I still like its central arguments:

* Learning new knowledge involves (1) being able to recall it when needed and (2) applying it appropriately. This work suggests that (1) is often the harder part.
* LLMs are not logical computers: optimizing $P(y \mid x) \to 1$ does not—and arguably should not—establish a logical knowledge $x \to y$ in the model.
</div>

<div class="notice" markdown="1">
**EVEDIT: Event-based Knowledge Editing for Deterministic Knowledge Propagation**  
--_Jiateng Liu, **Pengfei Yu**, Yuji Zhang, Sha Li, Zixuan Zhang, Ruhi Sarikaya, Kevin Small, Heng Ji (EMNLP 2024)_  [paper](https://aclanthology.org/2024.emnlp-main.282/)

This work continues the line of thinking above, but with a novel finding on LLM training, which, in some ways, behaves surprisingly "logically." When training data contains logical inconsistencies about a topic, the model becomes uncertain and inconsistent in its responses, just like a confused person who has been given contradictory information.
</div>

<div class="notice" markdown="1">
**The Law of Knowledge Overshadowing: Towards Understanding, Predicting and Preventing LLM Hallucination**  
--_Yuji Zhang, Sha Li, Cheng Qian, Jiateng Liu, **Pengfei Yu**, Chi Han, Yi R. Fung, Kathleen McKeown, ChengXiang Zhai, Manling Li, Heng Ji (ACL 2025 Findings)_  [paper](https://aclanthology.org/2025.findings-acl.1199/)

Most of the credit for this work goes to Dr. Yuji Zhang. The part I found especially compelling (and contributed to) is the motivating idea that language models can form spurious associations between co-occurring concepts: when “A X B” appears frequently, **A** can become a strong cue for producing **B** later, regardless of **X**. The paper also supports an intuition I've had for a while: hallucination is a form of generalization.
</div>