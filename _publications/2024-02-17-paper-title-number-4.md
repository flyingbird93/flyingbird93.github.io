---
title: "Improving Image Aesthetic Assessment via Multiple Image Joint Learning"
collection: publications
category: conferences
excerpt: 'This paper is about fixing template issue #693.'
date: 2024-06-20
venue: 'https://github.com/flyingbird93/MILNet'
paperurl: 'https://dl.acm.org/doi/abs/10.1145/3687128'
citation: 'Shi T, Chen C, Wu Z, et al. Improving Image Aesthetic Assessment via Multiple Image Joint Learning[J]. ACM Transactions on Multimedia Computing, Communications and Applications, 2024.'
---

Image Aesthetic Assessment (IAA) is a task aimed at predicting the aesthetic score of a given image. MostState-of-the-art (SOTA) approaches take a single image as input to predict its aesthetic score. However.single-image-based methods have significant limitations, as they can not predict the accurate result of imageswhich have large differences of aesthetic voting distribution, Taking inspiration from the practice thatpeople often considers similar experiences as references to bolster the consistence of the voting processTherefore, we present a novel IAA approach to emulate this natural voting process. The key idea is toenhance conventional single-image-based lAA by incorporating multiple reference images retrieved based onaesthetic similarity (the similarity of aesthetic attribution). By global level initializing and employing GraphConvolutional Network (GCN) to continuously update the intrinsic relationships among multiple images.the lAA model can effectively identify weight for multiple image joint learning. As a result, it can makemore accurate predictions by emploving feature and relationshins of references to construct a consistentaesthetic representation. Moreover, we introduce a novel Adaptive Earth Mover's Distance (adaEMD) lossfunction tailored for inter-image reasoning in the presence of a long-tailed and imbalanced distributionwithin large-scale aesthetic datasets. Both these technical innovations collectively contribute to the superiorperformance of our proposed approach compared to the benchmark AVA and TAD, resulting in signifcantoutperformance of other SOTA methods. The code is available at https:/github.com/flyingbird9/MlLNet.
