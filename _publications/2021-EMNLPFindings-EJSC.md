---
title: "An Explicit-Joint and Supervised-Contrastive Learning Framework for Few-Shot Intent Classification and Slot Filling"
collection: publications
permalink: /publication/2021-EMNLPFindings-EJSC
excerpt: 'This paper is about intent classification (IC) and slot filling (SF) in few-shot scenario.'
date: November 2021
venue: 'Findings of the 2021 Conference on Empirical Methods in Natural Language Processing (EMNLP), long paper'
paperurl: 'https://arxiv.org/abs/2110.13691'
citation: 'Han Liu, Feng Zhang, Xiaotong Zhang, Siyang Zhao, Xianchao Zhang. CoRR abs/2110.13691 (2021)'
---

![Framework](https://github.com/FengZhang-git/feng/tree/master/_publications/framework.png)
<img src="https://github.com/FengZhang-git/feng/tree/master/_publications/framework.png" width = "400" height = "260" alt="Framework" align=center>

## Abstract

Intent classification (IC) and slot filling (SF) are critical building blocks in taskoriented dialogue systems. These two tasks are closely-related and can flourish each other. Since only a few utterances can be utilized for identifying fast-emerging new intents and slots, data scarcity issue often occurs when implementing IC and SF. However, few IC/SF models perform well when the number of training samples per class is quite small. In this paper, we propose a novel explicit-joint and supervisedcontrastive learning framework for few-shot intent classification and slot filling. Its highlights are as follows. (i) The model extracts intent and slot representations via bidirectional interactions and extends prototypical network to achieve explicit-joint learning, which guarantees that IC and SF tasks can mutually reinforce each other. (ii) The model integrates with supervised contrastive learning, which ensures that samples from the same class are pulled together and samples from different classes are pushed apart. In addition, the model follows a not common but practical way to construct the episode, which gets rid of the traditional setting with fixed way and shot, and allows for unbalanced datasets. Extensive experiments on three public datasets show that our model can achieve promising performance.

[Download paper here](https://arxiv.org/abs/2110.13691)

[Code for paper](https://github.com/FengZhang-git/EJSC)
