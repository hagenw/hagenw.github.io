---
layout: post
comments: false
description: "Derington et al. - Testing Speech Emotion Recognition Machine Learning Models"
author: "A Derington, H Wierstorf, A Özkil, F Eyben, F Burkhardt, BW Schuller"
title: "Testing Correctness, Fairness, and Robustness of Speech Emotion Recognition Models"
journal: "IEEE Transactions on Affective Computing"
journalshort: "IEEE TAC"
pages: "1-14"
volume:
number:
year: "2025"
link: "https://arxiv.org/abs/2312.06270"
paper: "derington_et_al-2025-testing-speech-emotion-recognition-machine-learning-models.pdf"
presentation: 
published: true
---

### Bibtex

```latex
@article{Derington2025a,
    title   = {Testing Correctness, Fairness, and Robustness of Speech Emotion Recognition Models},
    author  = {Derington, Anna and Wierstorf, Hagen and \"{O}zkil, Ali
               and Eyben, Florian and Burkhardt, Felix and Schuller, Bj\"{o}rn W.},
    journal = {IEEE Transactions on Affective Computing},
    year    = {2025},
    doi     = {10.1109/TAFFC.2025.3547218}
}
```

### Abstract

Machine learning models for speech emotion recognition (SER) can be trained for
different tasks and are usually evaluated based on a few available datasets per task.
Tasks could include arousal, valence, dominance, emotional categories, or tone of voice.
Those models are mainly evaluated in terms of correlation or recall, and always show
some errors in their predictions. The errors manifest themselves in model behaviour,
which can be very different along different dimensions even if the same recall or
correlation is achieved by the model. This paper introduces a testing framework to
investigate behaviour of speech emotion recognition models, by requiring different
metrics to reach a certain threshold in order to pass a test. The test metrics can be
grouped in terms of correctness, fairness, and robustness. It also provides a method for
automatically specifying test thresholds for fairness tests, based on the datasets used,
and recommendations on how to select the remaining test thresholds. We evaluated a
xLSTM-based and nine transformer-based acoustic foundation models against a
convolutional baseline model, testing their performance on arousal, valence, dominance,
and emotional category classification. The test results highlight, that models with high
correlation or recall might rely on shortcuts -- such as text sentiment --, and differ
in terms of fairness.

### Supplementary material

The software used for the tests is available at
[https://github.com/audeering/ser-tests](https://github.com/audeering/ser-tests)
and results are available at
[https://audeering.github.io/ser-tests/](https://audeering.github.io/ser-tests/).
