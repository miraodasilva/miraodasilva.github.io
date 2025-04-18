---
title: "Contextual Speech Extraction: Leveraging Textual History as an Implicit Cue for Target Speech Extraction"
collection: publications
permalink: /publications/cse
venue: "ICASSP"
authors: "Minsu Kim and <b>Rodrigo Mira</b> (equal contribution), Honglie Chen, Stavros Petridis, Maja Pantic"
date: 2025-04-07
---

[[paper](https://ieeexplore.ieee.org/document/10887655)] [[project page](https://miraodasilva.github.io/cse-project-page/)] [[code](https://github.com/miraodasilva/contextual-speech-extraction)] [[presentation](https://youtu.be/UAD1EgmGPbE)] [[bib](/files/bib/cse.bib)]

## Abstract
In this paper, we investigate a novel approach for Target Speech Extraction (TSE), which relies solely on textual context to extract the target speech. We refer to this task as Contextual Speech Extraction (CSE). Unlike traditional TSE methods that rely on pre-recorded enrollment utterances, video of the target speaker's face, spatial information, or other explicit cues to identify the target stream, our proposed method requires only a few turns of previous dialogue (or monologue) history. This approach is naturally feasible in mobile messaging environments where voice recordings are typically preceded by textual dialogue that can be leveraged implicitly. We present three CSE models and analyze their performances on three datasets. Through our experiments, we demonstrate that even when the model relies purely on dialogue history, it can achieve over 90 % accuracy in identifying the correct target stream with only two previous dialogue turns. Furthermore, we show that by leveraging both textual context and enrollment utterances as cues during training, we further enhance our model's flexibility and effectiveness, allowing us to use either cue during inference, or combine both for improved performance. [Samples and code available](https://miraodasilva.github.io/cse-project-page/).