---
title: "Pay Attention to CTC: Fast and Robust Pseudo-Labelling for Unified Speech Recognition"
collection: publications
permalink: /publications/usr2
venue: "ICLR"
authors: "Alexandros Haliassos, <b>Rodrigo Mira</b>, Stavros Petridis"
date: 2026-02-22
teaser: /files/teaser/usr2.gif
---
[[paper](https://arxiv.org/abs/2602.19316)] [[code](https://github.com/ahaliassos/usr2)] [[bib](/files/bib/usr2.bib)]

## Abstract
Unified Speech Recognition (USR) has emerged as a semi-supervised framework for training a single model for audio, visual, and audiovisual speech recognition, achieving state-of-the-art results on in-distribution benchmarks. However, its reliance on autoregressive pseudo-labelling makes training expensive, while its decoupled supervision of CTC and attention branches increases susceptibility to self-reinforcing errors, particularly under distribution shifts involving longer sequences, noise, or unseen domains. We propose CTC-driven teacher forcing, where greedily decoded CTC pseudo-labels are fed into the decoder to generate attention targets in a single forward pass. Although these can be globally incoherent, in the pseudo-labelling setting they enable efficient and effective knowledge transfer. Because CTC and CTC-driven attention pseudo-labels have the same length, the decoder can predict both simultaneously, benefiting from the robustness of CTC and the expressiveness of attention without costly beam search. We further propose mixed sampling to mitigate the exposure bias of the decoder relying solely on CTC inputs. The resulting method, USR 2.0, halves training time, improves robustness to out-of-distribution inputs, and achieves state-of-the-art results on LRS3, LRS2, and WildVSR, surpassing USR and modality-specific self-supervised baselines.