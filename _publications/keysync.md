---
title: "KeySync: A Robust Approach for Leakage-free Lip Synchronization in High Resolution"
collection: publications
permalink: /publications/keysync
venue: "arXiv"
authors: "Antoni Bigata, <b>Rodrigo Mira</b>, Stella Bounareli, Michał Stypułkowski, Konstantinos Vougioukas, Stavros Petridis, Maja Pantic"
date: 2025-07-01
teaser: /files/teaser/keysync.png
---

[[paper](https://arxiv.org/abs/2505.00497)] [[project page](https://antonibigata.github.io/KeySync/)] [[code](https://github.com/antonibigata/keysync)] [[bib](/files/bib/keysync.bib)]

## Abstract
Lip synchronization, known as the task of aligning lip movements in an existing video with new input audio, is typically framed as a simpler variant of audio-driven facial animation. However, as well as suffering from the usual issues in talking head generation (e.g., temporal consistency), lip synchronization presents significant new challenges such as expression leakage from the input video and facial occlusions, which can severely impact real-world applications like automated dubbing, but are often neglected in existing works. To address these shortcomings, we present KeySync, a two-stage framework that succeeds in solving the issue of temporal consistency, while also incorporating solutions for leakage and occlusions using a carefully designed masking strategy. We show that KeySync achieves state-of-the-art results in lip reconstruction and cross-synchronization, improving visual quality and reducing expression leakage according to LipLeak, our novel leakage metric. Furthermore, we demonstrate the effectiveness of our new masking approach in handling occlusions and validate our architectural choices through several ablation studies. Code and model weights can be found at this [this url](https://antonibigata.github.io/KeySync/).