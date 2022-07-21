---
title: "ExcitGlow: Improving a WaveGlow-based Neural Vocoder with Linear Prediction Analysis"
collection: publications
permalink: /publication/2020/12/07-2020-4-excitglow
authors: Suhyeon Oh, Hyungseob Lim, Kyungguen Byun, **Min-Jae Hwang**, Eunwoo Song, Hong-Goo Kang
date: 2020/12/07
venue: 'APSIPA ASC 2020'
paperurl: 'https://sewplay.github.io/cv/papers/2020/apsipa_0000831.pdf'
---
In this paper, we propose ExcitGlow, a vocoder that incorporates the source-filter model of voice production theory into a flow-based deep generative model. By targeting the distribution of the excitation signal instead of the speech waveform itself, we significantly reduce the size of the flow-based generative model. To further reduce the number of parameters, we apply a parameter sharing technique in which a single affine coupling layer is used for several  low layers. To avoid quality degradation, we also introduce a closed-loop training framework to optimize the flow model for both the speech and excitation signal generation processes. Specifically, we choose negative log-likelihood (NLL) loss for the excitation signal and multi-resolution spectral distance for the speech signal. As a result, we are able to reduce the model size from 87.73M to 15.60M parameters while maintaining the perceptual quality of synthesized speech.
