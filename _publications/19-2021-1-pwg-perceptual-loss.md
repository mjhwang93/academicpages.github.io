---
title: "Improved Parallel WaveGAN Vocoder with Perceptually Weighted Spectrogram Loss"
collection: publications
permalink: /publication/2021/01/19-2021-1-pwg-perceptual-loss
authors: **<var>Min-Jae Hwang</var>**
date: 2021/01/19
venue: 'IEEE SLT Workshop 2021'
paperurl: 'https://arxiv.org/abs/2101.07412'
---
This paper proposes a spectral-domain perceptual weighting technique for Parallel WaveGAN-based text-to-speech (TTS) systems. The recently proposed Parallel WaveGAN vocoder successfully generates waveform sequences using a fast non-autoregressive WaveNet model. By employing multi-resolution short-time Fourier transform (MR-STFT) criteria with a generative adversarial network, the light-weight convolutional networks can be effectively trained without any distillation process. To further improve the vocoding performance, we propose the application of frequency-dependent weighting to the MR-STFT loss function. The proposed method penalizes perceptually-sensitive errors in the frequency domain; thus, the model is optimized toward reducing auditory noise in the synthesized speech. Subjective listening test results demonstrate that our proposed method achieves 4.21 and 4.26 TTS mean opinion scores for female and male Korean speakers, respectively.
