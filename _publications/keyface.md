---
title: "KeyFace: Expressive Audio-Driven Facial Animation for Long Sequences via KeyFrame Interpolation"
collection: publications
permalink: /publications/keyface
venue: "CVPR"
authors: "Antoni Bigata, Michał Stypułkowski, <b>Rodrigo Mira</b>, Stella Bounareli, Konstantinos Vougioukas, Zoe Landgraf, Nikita Drobyshev, Maciej Zieba, Stavros Petridis, Maja Pantic"
date: 2025-06-11
---

[[paper](https://arxiv.org/abs/2503.01715)] [[project page](https://antonibigata.github.io/KeyFace/)] [[code](https://github.com/antonibigata/keyface_cvpr)] [[bib](/files/bib/keyface.bib)]

## Abstract
Current audio-driven facial animation methods achieve impressive results for short videos but suffer from error accumulation and identity drift when extended to longer durations. Existing methods attempt to mitigate this through external spatial control, increasing long-term consistency but compromising the naturalness of motion. We propose KeyFace, a novel two-stage diffusion-based framework, to address these issues. In the first stage, keyframes are generated at a low frame rate, conditioned on audio input and an identity frame, to capture essential facial expressions and movements over extended periods of time. In the second stage, an interpolation model fills in the gaps between keyframes, ensuring smooth transitions and temporal coherence. To further enhance realism, we incorporate continuous emotion representations and handle a wide range of non-speech vocalizations (NSVs), such as laughter and sighs. We also introduce two new evaluation metrics for assessing lip synchronization and NSV generation. Experimental results show that KeyFace outperforms state-of-the-art methods in generating natural, coherent facial animations over extended durations, successfully encompassing NSVs and continuous emotions.