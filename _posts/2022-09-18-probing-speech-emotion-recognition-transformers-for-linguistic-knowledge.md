---
layout: post
comments: false
description: "Triantafyllopoulos et al. - Probing speech emotion recognition transformers for linguistic knowledge"
author: "A Triantafyllopoulos, J Wagner, H Wierstorf, M Schmitt, U Reichel, F Eyben, F Burkhardt, BW Schuller"
title: "Probing speech emotion recognition transformers for linguistic knowledge"
proceedings: "Proceedings Interspeech 2022"
short: "Interspeech"
year: "2022"
paper: "triantafyllopoulos_et_al-2022-probing-speech-emotion-recognition-transformers-for-linguistic-knowledge.pdf"
published: true
---

### Bibtex

```latex
@proceedings{Triantafyllopoulos2022a,
    title     = {Probing speech emotion recognition transformers
                 for linguistic knowledge},
    author    = {Triantafyllopoulos, Andreas and Wagner, Johannes
                 and Wierstorf, Hagen and Schmitt, Maximilian
                 and Reichel, Uwe, and Eyben, Florian
                 and Burkhardt, Felix, and Schuller, Björn W.},
    booktitle = {Proceedings Interspeech 2022},
    publisher = {ICSA},
    address   = {Incheon, Korea},
    month     = {September},
    pages     = {146--150},
    doi       = {10.21437/Interspeech.2022-10371},
    year      = {2022}
}
```

### Abstract

Large, pre-trained neural networks consisting of self-attention layers
(transformers) have recently achieved state-of-the-art results on several speech
emotion recognition (SER) datasets. These models are typically pre-trained in
self-supervised manner with the goal to improve automatic speech recognition
performance -- and thus, to understand linguistic information. In this work, we
investigate the extent in which this information is exploited during SER
fine-tuning. Using a reproducible methodology based on open-source tools, we
synthesise prosodically neutral speech utterances while varying the sentiment of
the text. Valence predictions of the transformer model are very reactive to
positive and negative sentiment content, as well as negations, but not to
intensifiers or reducers, while none of those linguistic features impact arousal
or dominance. These findings show that transformers can successfully leverage
linguistic information to improve their valence predictions, and that linguistic
analysis should be included in their testing.
