---
layout: post
comments: false
description: "Wagner et al. - Dawn of the transformer era in speech emotion recognition: closing the valence gap"
author: "J Wagner, A Triantafyllopoulos, H Wierstorf, M Schmitt, F Burkhardt, F Eyben, BW Schuller"
title: "Dawn of the transformer era in speech emotion recognition: closing the valence gap"
journal: "IEEE Transactions on Pattern Analysis and Machine Intelligence"
journalshort: "IEEE TPAMI"
pages: "10745-10759"
volume: "45"
number: "9"
year: "2023"
link: "https://arxiv.org/abs/2203.07378v4"
paper: "wagner_et_al-2023-dawn-of-the-transformer-era-in-speech-emotion-recognition.pdf"
presentation: 
published: true
---

### Bibtex

```latex
@article{Wagner2023a,
    title   = {Dawn of the transformer era in speech emotion recognition:
               closing the valence gap},
    author  = {Wagner, Johannes and Triantafyllopoulos, Andreas
               and Wierstorf, Hagen and Eyben, Florian
               and Schuller, Bj\"{o}rn W. and Burkhardt, Felix},
    journal = {IEEE Transactions on Pattern Analysis and Machine Intelligence},
    volume  = {45},
    number  = {9},
    pages   = {10745--10759},
    year    = {2023},
    doi     = {10.1109/TPAMI.2023.3263585}
}
```

### Abstract

Recent advances in transformer-based architectures
which are pre-trained in self-supervised manner
have shown great promise in several machine learning tasks.
In the audio domain,
such architectures have also been successfully utilised
in the field of speech emotion recognition (SER).
However,
existing works have not evaluated
the influence of model size and pre-training data
on downstream performance,
and have shown limited attention to generalisation,
robustness,
fairness,
and efficiency.
The present contribution conducts a thorough analysis
of these aspects on several pre-trained variants of wav2vec 2.0
and HuBERT
that we fine-tuned on the dimensions arousal,
dominance,
and valence of MSP-Podcast,
while additionally using IEMOCAP and MOSI
to test cross-corpus generalisation.
To the best of our knowledge,
we obtain the top performance for valence prediction
without use of explicit linguistic information,
with a concordance correlation coefficient (CCC)
of .638 on MSP-Podcast.
Furthermore, our investigations reveal
that transformer-based architectures
are more robust to small perturbations
compared to a CNN-based baseline and fair
with respect to biological sex groups,
but not towards individual speakers.
Finally, we are the first to show
that their extraordinary success on valence
is based on implicit linguistic information
learnt during fine-tuning of the transformer layers,
which explains why they perform on-par
with recent multimodal approaches
that explicitly utilise textual information.
Our findings collectively paint the following picture:
transformer-based architectures constitute the new state-of-the-art
in SER, but further advances are needed
to mitigate remaining robustness and individual speaker issues.
To make our findings reproducible,
we release the best performing model to the community.

### Supplementary material

An ONNX version of the best performing model is available at
[10.5281/zenodo.6221127](https://doi.org/10.5281/zenodo.6221127).
For an introduction how to use it,
take a look at
[How to use our public dimensional emotion model](https://github.com/audeering/w2v2-how-to).
