---
title: "LiRA: Learning Visual Speech Representations from Audio through Self-Supervision"
collection: publications
permalink: /publications/lira
venue: "Interspeech"
authors: "Pingchuan Ma and <b>Rodrigo Mira</b> (equal contribution), Stavros Petridis, Björn W. Schuller, Maja Pantic"
date: 2021-08-30
teaser: /files/teaser/lira.png
---

[[paper](https://www.isca-speech.org/archive/interspeech_2021/ma21c_interspeech.html)] [[3-minute video introduction](https://www.superlectures.com/interspeech2021/lira-learning-visual-speech-representations-from-audio-through-self-supervision-3-minutes-introduction)] [[bib](/files/bib/lira.bib)]

## Abstract
The large amount of audiovisual content being shared online today has drawn substantial attention to the prospect of audiovisual self-supervised learning. Recent works have focused on each of these modalities separately, while others have attempted to model both simultaneously in a cross-modal fashion. However, comparatively little attention has been given to leveraging one modality as a training objective to learn from the other. In this work, we propose Learning visual speech Representations from Audio via self-supervision (LiRA). Specifically, we train a ResNet+Conformer model to predict acoustic features from unlabelled visual speech. We find that this pre-trained model can be leveraged towards word-level and sentence-level lip-reading through feature extraction and fine-tuning experiments. We show that our approach significantly outperforms other self-supervised methods on the Lip Reading in the Wild (LRW) dataset and achieves state-of-the-art performance on Lip Reading Sentences 2 (LRS2) using only a fraction of the total labelled data.