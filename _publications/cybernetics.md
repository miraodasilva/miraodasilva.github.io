---
title: "End-to-End Video-to-Speech Synthesis using Generative Adversarial Networks"
collection: publications
permalink: /publications/endtoendvts
venue: "IEEE Transactions on Cybernetics"
authors: "<b>Rodrigo Mira</b>, Konstantinos Vougioukas, Pingchuan Ma, Stavros Petridis, Björn W Schuller, Maja Pantic"
date: 2022-04-19
teaser: /files/teaser/cybernetics.png
---

[[project page](https://sites.google.com/view/video-to-speech/home)] [[paper](https://ieeexplore.ieee.org/document/9760273)] [[bib](/files/bib/end-to-end-vts.bib)]

## Abstract
Video-to-speech is the process of reconstructing the audio speech from a video of a spoken utterance. Previous approaches to this task have relied on a two-step process where an intermediate representation is inferred from the video and is then decoded into waveform audio using a vocoder or a waveform reconstruction algorithm. In this work, we propose a new end-to-end video-to-speech model based on generative adversarial networks (GANs) which translates spoken video to waveform end-to-end without using any intermediate representation or separate waveform synthesis algorithm. Our model consists of an encoder-decoder architecture that receives raw video as input and generates speech, which is then fed to a waveform critic and a power critic. The use of an adversarial loss based on these two critics enables the direct synthesis of the raw audio waveform and ensures its realism. In addition, the use of our three comparative losses helps establish direct correspondence between the generated audio and the input video. We show that this model is able to reconstruct speech with remarkable realism for constrained datasets such as GRID, and that it is the first end-to-end model to produce intelligible speech for Lip Reading in the Wild (LRW), featuring hundreds of speakers recorded entirely "in the wild". We evaluate the generated samples in two different scenarios - seen and unseen speakers - using four objective metrics which measure the quality and intelligibility of artificial speech. We demonstrate that the proposed approach outperforms all previous works in most metrics on GRID and LRW.