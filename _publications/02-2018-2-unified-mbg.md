---
title: "A Unified Framework for the Generation of Glottal Signals in Deep Learning-based Parametric Speech Synthesis Systems"
collection: publications
permalink: /publication/2018/09/02-2018-2-unified-mbg
authors: **Min-Jae Hwang**, Eunwoo Song, Jin-Seob Kim, and Hong-Goo Kang
date: 2018/09/02
venue: 'Interspeech 2018'
paperurl: 'https://www.isca-speech.org/archive_v0/Interspeech_2018/pdfs/1590.pdf'
---
In this paper, we propose a unified training framework for the  generation of glottal signals in deep learning (DL)-based parametric speech synthesis systems. The glottal vocoding-based speech synthesis system, especially the  odeling-by-generation (MbG) structure that we proposed recently, significantly improves the naturalness of synthesized speech by faithfully representing the noise component of the glottal excitation with an additional DL structure.  ecause the MbG method introduces a multistage processing pipeline, however, its training process is complicated and inefficient. To alleviate this problem, we propose a unified training approach that directly generates speech parameters by merging all the required models, such as acoustic, glottal, and noise models, into a single unified network. Considering the fact that noise analysis should be performed after training the glottal model, we also propose    tochastic noise analysis method that enables noise modeling to be included in the unified training process by iteratively analyzing the noise component in every epoch. Both objective and subjective test results verify the superiority of the proposed algorithm compared to conventional methods.
