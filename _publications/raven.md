---
title: "Jointly Learning Visual and Auditory Speech Representations from Raw Data"
collection: publications
permalink: /publications/raven
venue: "ICLR"
authors: "Alexandros Haliassos, Pingchuan Ma, <b>Rodrigo Mira</b>, Stavros Petridis, Maja Pantic"
date: 2023-05-01
teaser: /files/teaser/raven.png
---

[[paper](https://arxiv.org/abs/2212.06246)] [[bib](/files/bib/raven.bib)]

## Abstract
One of the most pressing challenges for the detection of face-manipulated videos is generalising to forgery methods not seen during training while remaining effective under common corruptions such as compression. In this paper, we examine whether we can tackle this issue by harnessing videos of real talking faces, which contain rich information on natural facial appearance and behaviour and are readily available in large quantities online. Our method, termed RealForensics, consists of two stages. First, we exploit the natural correspondence between the visual and auditory modalities in real videos to learn, in a self-supervised cross-modal manner, temporally dense video representations that capture factors such as facial movements, expression, and identity. Second, we use these learned representations as targets to be predicted by our forgery detector along with the usual binary forgery classification task; this encourages it to base its real/fake decision on said factors. We show that our method achieves state-of-the-art performance on cross-manipulation generalisation and robustness experiments, and examine the factors that contribute to its performance. Our results suggest that leveraging natural and unlabelled videos is a promising direction for the development of more robust face forgery detectors.