---
title: "Lookahead Anchoring: Preserving Character Identity in Audio-Driven Human Animation"
collection: publications
permalink: /publications/lookahead-anchoring
venue: "arXiv"
authors: "Junyoung Seo, <b>Rodrigo Mira</b>, Alexandros Haliassos, Stella Bounareli, Honglie Chen, Linh Tran, Seungryong Kim, Zoe Landgraf, Jie Shen"
date: 2025-10-27
teaser: /files/teaser/lookahead-anchoring.png
---

[[paper](https://arxiv.org/abs/2510.23581v1)] [[project page](https://lookahead-anchoring.github.io/)] [[code](https://github.com/j0seo/lookahead-anchoring)] [[bib](/files/bib/lookahead-anchoring.bib)]

## Abstract
Audio-driven human animation models often suffer from identity drift during temporal autoregressive generation, where characters gradually lose their identity over time. One solution is to generate keyframes as intermediate temporal anchors that prevent degradation, but this requires an additional keyframe generation stage and can restrict natural motion dynamics. To address this, we propose Lookahead Anchoring, which leverages keyframes from future timesteps ahead of the current generation window, rather than within it. This transforms keyframes from fixed boundaries into directional beacons: the model continuously pursues these future anchors while responding to immediate audio cues, maintaining consistent identity through persistent guidance. This also enables self-keyframing, where the reference image serves as the lookahead target, eliminating the need for keyframe generation entirely. We find that the temporal lookahead distance naturally controls the balance between expressivity and consistency: larger distances allow for greater motion freedom, while smaller ones strengthen identity adherence. When applied to three recent human animation models, Lookahead Anchoring achieves superior lip synchronization, identity preservation, and visual quality, demonstrating improved temporal conditioning across several different architectures. [Video results are available](https://lookahead-anchoring.github.io/).