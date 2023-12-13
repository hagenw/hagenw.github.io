---
layout: post
comments: false
description: "Burkhardt et al. - Speech-based Age and Gender Prediction with Transformers"
author: "F Burkhardt, J Wagner, H Wierstorf, F Eyben, BW Schuller"
title: "Speech-based Age and Gender Prediction with Transformers"
proceedings: "15th ITG Conference on Speech Communication"
short: "ITG"
year: "2023"
link: "https://arxiv.org/abs/2306.16962"
paper: "burkhardt_et_al-2023-speech-based-age-and-gender-prediction-with-transformers.pdf"
published: true
---

### Bibtex

```latex
@proceedings{Burkhardt2023a,
    title     = {Speech-based Age and Gender Prediction with Transformers},
    author    = {Burkhardt, Felix and Wagner, Johannes and Wierstorf, Hagen
                 and Eyben, Florian and Schuller, Björn W.},
    booktitle = {15th ITG Conference on Speech Communication},
    publisher = {VDE},
    address   = {Aachen, Germany},
    month     = {September},
    year      = {2023}
}
```

### Abstract

We report on the curation of several publicly available datasets for age and
gender prediction. Furthermore, we present experiments to predict age and gender
with models based on a pre-trained wav2vec 2.0. Depending on the dataset, we
achieve an MAE between 7.1 years and 10.8 years for age, and at least 91.1% ACC
for gender (female, male, child). Compared to a modelling approach built on
handcrafted features, our proposed system shows an improvement of 9% UAR for age
and 4% UAR for gender. To make our findings reproducible, we release the best
performing model to the community as well as the sample lists of the data
splits.

### Supplementary material

ONNX versions of the 24-layer and 6-layer model are available at
[https://doi.org/10.5281/zenodo.7761387](https://doi.org/10.5281/zenodo.7761387),
together with the defined test splits from the paper.
For an introduction how to use it,
take a look at
[How to use our public age and gender model](https://github.com/audeering/w2v2-age-gender-how-to).
