---
title: "RGB and LUT based Cross Attention Network for Image Enhancement"
collection: publications
category: manuscripts
excerpt: 'This paper is about the number 2. The number 3 is left for future work.'
date: 2023-11-15
githubsurl: 'https://github.com/flyingbird93/CANet'
paperurl: 'https://papers.bmvc2023.org/0348.pdf'
citation: 'Tengfei Shi, Chenglizhao Chen, Yuanbo He, Aimin Hao. “RGB and LUT based Cross Attention Network for Image Enhancement”, British Machine Vision Conference (BMVC), 2023, 348-350.'
---

Image enhancement aims to improve the quality of images by adjusting their color and is widely usedinprofessional digital photography. Deep learning-based 3 Dimensional LookUp-Table (3D LUT) of RGB color transformation has achieved promising performance in terms of speed and precision. However, the focus has mainly been on building an adaptive enhancer by only learning the global color adjusting weights from the image, which ignores the significant relationship between the intrinsic semantic information of the image and LUT that is relevant to photographers. In this paper, we propose the Cross Attention Network (CANet), a new framework that formulates image enhancement as a parallel learning process based on the image and LUT features. To better learn the adjustment weights for both global color and intrinsic semantics, we propose a cross attention architecture that connects low-level (color, edge and outline) and high-level (semantic) features of the image and color transform LUT features to generate appropriate adjustment weights. Meanwhile, we employ a LUT-Aware Module (LAM) to construct the channels and spatial attention for refining the LUT features. Since these modules have a more powerful representational capacity, they can better capture the intrinsic relationship between image semantics and LUT features. The extensive evaluations on standard benchmarks, including FiveK and HDR datasets, show that CANet achieves better performance compared to state-of-the-art methods.
