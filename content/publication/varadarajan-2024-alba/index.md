---
title: 'ALBA: Adaptive Language-Based Assessments for Mental Health'
authors:
- Vasudha Varadarajan
- Sverker Sikström
- Oscar Kjell
- H Schwartz
date: '2024-01-01'
publishDate: '2024-09-20T05:49:28.774852Z'
publication_types:
- paper-conference
publication: '*Proceedings of the 2024 Conference of the North American Chapter of
  the Association for Computational Linguistics: Human Language Technologies (Volume
  1: Long Papers)*'

url_pdf: https://aclanthology.org/2024.naacl-long.136.pdf
url_code: https://github.com/humanlab/alba-irt

abstract: Mental health issues differ widely among individuals, with varied signs and symptoms. Recently, language-based assessments have shown promise in capturing this diversity, but they require a substantial sample of words per person for accuracy. This work introducesthe task of Adaptive Language-Based Assessment (ALBA), which involves adaptively ordering questions while also scoring an individual’s latent psychological trait using limited language responses to previous questions. To this end, we develop adaptive testing methods under two psychometric measurement theories -- Classical Test Theory and Item Response Theory. We empirically evaluate ordering and scoring strategies, organizing into two new methods -- a semi-supervised item response theory-basedmethod (ALIRT) and a supervised Actor-Critic model. While we found both methods to improve over non-adaptive baselines, We found ALIRT to be the most accurate and scalable, achieving the highest accuracy with fewer questions (e.g., Pearson r ≈ 0.93 after only 3 questions as compared to typically needing at least 7 questions). In general, adaptive language-based assessments of depression and anxiety were able to utilize a smaller sample of language without compromising validity or large computational costs.

summary: This study introduces Adaptive Language-Based Assessment (ALBA) for mental health, using limited language responses to adaptively order questions and assess psychological traits. Two methods, ALIRT and Actor-Critic, outperformed non-adaptive baselines. ALIRT proved most effective, achieving high accuracy with fewer questions, demonstrating that adaptive assessments can maintain validity with smaller language samples and lower computational costs.

tags:
- mental health, assessments, adaptive, item response theory, chatbot
  
featured: true
image:
  caption: 'Adaptively asking questions by modeling a latent variable for the assessed score.'
  
---
