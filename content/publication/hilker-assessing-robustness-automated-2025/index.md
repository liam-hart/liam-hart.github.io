---
title: Assessing the Robustness of Automated Scoring of Divergent Thinking Tasks with
  Adversarial Examples
authors:
- Yannick Hilker
- Boris Forthmann
- Philipp Doebler
date: '2025-04-01'
publishDate: '2025-05-28T02:32:39.871548Z'
publication_types:
- manuscript
publication: '*PsyArXiv*'
doi: 10.31234/osf.io/47zxm_v1
abstract: "Automated scoring with machine learning has received considerable attention,
  especially for the Alternative Uses Test (AUT) of divergent thinking. In particular,
  supervised learning on word embeddings and approaches based on large language models
  predict human ratings with sufficient accuracy for many practical purposes. However,
  since automated systems will potentially be used without a ``human in the loop'',
  the robustness of any model is crucial, not only for the validity of basic research,
  but also for applications. We investigate the potential of adversarial examples
  (AEs) as robustness checks. AEs are synthetic responses obtained by subtle permutations
  of original responses that are assigned a substantially different score by the automated
  system. Specifically, we propose to employ synonyms to obtain semantically close
  synthetic responses. A synthetic response is an AE, when the deviation of the automated
  scores of the synthetic response and the original response is at least as large
  as the prediction error of the automated system. A random forest trained on GloVe
  word embeddings predicts human ratings of 2,690 distinct original AUT answers (stimuli:
  brick, paperclip) and for 39% 42% AEs can be found, including both single and multi-word
  responses. On average, the AEs have slightly higher automated scores than the originals.
  While a small fraction of the AEs are invalid AUT responses, pronounced large deviations
  indicate that the prediction model is non-robust. Retraining including the AEs in
  the training data improves the robustness. We recommend to use AEs routinely to
  assess the robustness of automated scoring systems."
tags:
- /unread
- adversarial examples
- automated scoring
- creativity assessment
- divergent thinking
- random forest
- robustness
---
