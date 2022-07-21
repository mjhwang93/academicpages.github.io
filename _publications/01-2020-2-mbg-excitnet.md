---
title: "Neural Text-to-Speech with a Modeling-by-Generation Excitation Vocoder"
collection: publications
permalink: /publication/2020/08/01-2020-2-mbg-excitnet
authors: **<var>Min-Jae Hwang</var>**
date: 2020/08/01
venue: 'INTERSPEECH 2020'
paperurl: 'https://arxiv.org/abs/2008.00132'
---
This paper proposes a modeling-by-generation (MbG) excitation vocoder for a neural text-to-speech (TTS) system. Recently proposed neural excitation vocoders can realize qualified waveform generation by combining a vocal tract filter with a WaveNet-based glottal excitation generator. However, when these vocoders are used in a TTS system, the quality of synthesized speech is often degraded owing to a mismatch between training and synthesis steps. Specifically, the vocoder is separately trained from an acoustic model front-end. Therefore, estimation errors of the acoustic model are inevitably boosted throughout the synthesis process of the vocoder back-end. To address this problem, we propose to incorporate an MbG structure into the vocoder&apos;s training process. In the proposed method, the excitation signal is extracted by the acoustic model&apos;s generated spectral parameters, and the neural vocoder is then optimized not only to learn the target excitation&apos;s distribution but also to compensate for the estimation errors occurring from the acoustic model. Furthermore, as the generated spectral parameters are shared in the training and synthesis steps, their mismatch conditions can be reduced effectively. The experimental results verify that the proposed system provides high-quality synthetic speech by achieving a mean opinion score of 4.57 within the TTS framework.
