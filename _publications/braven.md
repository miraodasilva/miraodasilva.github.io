---
title: "BRAVEn: Improving Self-Supervised Pre-training for Visual and Auditory Speech Recognition"
collection: publications
permalink: /publications/braven
venue: "ICASSP"
authors: "Alexandros Haliassos and Andreas Zinonos (equal contribution), <b>Rodrigo Mira</b>, Stavros Petridis, Maja Pantic"
date: 2024-04-14
teaser: /files/teaser/braven.png
---

[[paper](https://cmsworkshops.com/ICASSP2024/view_paper.php?PaperNum=6511)] [[code](https://github.com/ahaliassos/raven)] [[slides](https://sigport.org/sites/all/modules/pubdlcnt/pubdlcnt.php?fid=9674)] [[bib](/files/bib/braven.bib)]

## Abstract
Self-supervision has recently shown great promise for learning visual and auditory speech representations from unlabelled data. In this work, we propose BRAVEn, an extension to the recent RAVEn method, which learns speech representations entirely from raw audio-visual data. Our modifications to RAVEn enable BRAVEn to achieve state-of-the-art results among self-supervised methods in various settings. Moreover, we observe favourable scaling behaviour by increasing the amount of unlabelled data well beyond other self-supervised works. In particular, we achieve 20.0% / 1.7% word error rate for VSR / ASR on the LRS3 test set, with only 30 hours of labelled data and no external ASR models. Our results suggest that readily available unlabelled audio-visual data can largely replace costly transcribed data.