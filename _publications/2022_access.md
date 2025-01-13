---
title: "AI Golf: Golf Swing Analysis Tool for Self-Training"
collection: publications
permalink: /publication/2022-access
excerpt: ''
date: 2022-10-06
venue: 'IEEE Access'
paperurl: 'https://ieeexplore.ieee.org/document/9913343/'
citation: 'Liao et al. "Ai golf: Golf swing analysis tool for self-training." IEEE Access 10 (2022): 106286-106295.'
---
## Authors
Chen-Chieh Liao, **Dong-Hyun Hwang**, and Hideki Koike

NAVER CLOVA and Tokyo Institute of Technology

## Abstract
In the field of the acquisition of sports skills, a common way to improve sports skills, such as
golf swings, is to imitate professional players’ motions. However, it is difficult for beginners to specify the keyframes on which they should focus and which part of the body they should correct because of inconsistent timing and lack of knowledge. In this study, a golf swing analysis tool using neural networks is proposed to address this gap. The proposed system compares two motion sequences and specifies keyframes in which significant differences can be observed between the two motions. In addition, the system helps users intuitively understand the differences between themselves and professional players by using
interpretable clues. The main challenge of this study is to target the fine-grained differences between users and professionals that can be used for self-training. Moreover, the significance of the proposed approach is the use of an unsupervised learning method without prior knowledge and labeled data, which will benefit future applications and research in other sports and skill training processes. In our approach, neural networks
are first used to create a motion synchronizer to align motions with different phases and timing. Next,
a motion discrepancy detector is implemented to find fine-grained differences between motions in latent
spaces that are learned by the networks. Furthermore, we consider that learning intermediate motions may be feasible for beginners because, in this way, they can gradually change their pose to match the ideal form.
Therefore, based on the synchronization and discrepancy detection results, we utilize a decoder to restore the intermediate human poses between two motions from the latent space. Finally, we suggest possible applications for analyzing and visualizing the discrepancy between the two input motions and interacting with the users. With the proposed application, users can easily understand the differences between their motions and those of various experts during self-training and learn how to improve their motions.