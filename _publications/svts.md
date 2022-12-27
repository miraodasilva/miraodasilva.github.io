---
title: "SVTS: Scalable Video-to-Speech Synthesis"
collection: publications
permalink: /publications/svts
venue: "Interspeech"
authors: "<b>Rodrigo Mira</b>, Alexandros Haliassos, Stavros Petridis, Björn W Schuller, Maja Pantic"
date: 2022-08-18
---

[[project page](https://sites.google.com/view/scalable-vts)] [[paper](https://arxiv.org/abs/2205.02058)] [[bib](/files/bib/svts.bib)]

## Abstract
Video-to-speech synthesis (also known as lip-to-speech) refers to the translation of silent lip movements into the corresponding audio. This task has received an increasing amount of attention due to its self-supervised nature (i.e., can be trained without manual labelling) combined with the ever-growing collection of audio-visual data available online. Despite these strong motivations, contemporary video-to-speech works focus mainly on small- to medium-sized corpora with substantial constraints in both vocabulary and setting. In this work, we introduce a scalable video-to-speech framework consisting of two components: a video-to-spectrogram predictor and a pre-trained neural vocoder, which converts the mel-frequency spectrograms into waveform audio. We achieve state-of-the art results for GRID and considerably outperform previous approaches on LRW. More importantly, by focusing on spectrogram prediction using a simple feedforward model, we can efficiently and effectively scale our method to very large and unconstrained datasets: To the best of our knowledge, we are the first to show intelligible results on the challenging LRS3 dataset.