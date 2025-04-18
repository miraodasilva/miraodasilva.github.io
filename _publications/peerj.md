---
title: "Automated composition of Galician Xota—tuning RNN-based composers for specific musical styles using deep Q-learning"
collection: publications
permalink: /publications/peerj
venue: "PeerJ Computer Science"
authors: "<b>Rodrigo Mira</b>, Eduardo Coutinho, Emilia Parada-Cabaleiro, Björn W Schuller"
date: 2023-05-15
teaser: /files/teaser/peerj.png
---

[[paper](https://peerj.com/articles/cs-1356/)] [[code](https://github.com/miraodasilva/GalicianXotaComposer)] [[bib](/files/bib/peerj.bib)]

## Abstract
Music composition is a complex field that is difficult to automate because the computational definition of what is good or aesthetically pleasing is vague and subjective. Many neural network-based methods have been applied in the past, but they lack consistency and in most cases, their outputs fail to impress. The most common issues include excessive repetition and a lack of style and structure, which are hallmarks of artificial compositions. In this project, we build on a model created by Magenta—the RL Tuner—extending it to emulate a specific musical genre—the Galician Xota. To do this, we design a new rule-set containing rules that the composition should follow to adhere to this style. We then implement them using reward functions, which are used to train the Deep Q Network that will be used to generate the pieces. After extensive experimentation, we achieve an implementation of our rule-set that effectively enforces each rule on the generated compositions, and outline a solid research methodology for future researchers looking to use this architecture. Finally, we propose some promising future work regarding further applications for this model and improvements to the experimental procedure.