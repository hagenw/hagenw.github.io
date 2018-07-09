---
layout: post
comments: false
description: "Grais et al. - Multi-Resolution Fully Convolutional Neural
Networks for Monaural Audio Source Separation"
author: "EM Grais, H Wierstorf, D Ward, MD Plumbley"
title: "Multi-Resolution Fully Convolutional Neural Networks for Monaural Audio
Source Separation"
proceedings: "Latent Variable Analysis and Signal Separation (LVA/ICA)"
short: "LVA/ICA"
pages: "340-350"
year: "2018"
link: "https://doi.org/10.1007/978-3-319-93764-9_32"
published: true
---

### Bibtex

```latex
@inproceedings{Grais2018a,
    title     = {Multi-Resolution Fully Convolutional Neural Networks for
                 Monaural Audio Source Separation},
    author    = {Grais, Emad M. and Wierstorf, Hagen and Ward, Dominic and
                 Plumbley, Mark D.},
    booktitle = {Latent Variable Analysis and Signal Separation (LVA/ICA)},
    address   = {Guildford, UK},
    month     = {June},
    year      = {2018},
    doi       = {10.1007/978-3-319-93764-9_32},
    url       = {https://doi.org/10.1007/978-3-319-93764-9_32}
}
```

### Abstract

In deep neural networks with convolutional layers, all the neurons in each layer
typically have the same size receptive fields (RFs) with the same resolution.
Convolutional layers with neurons that have large RF capture global information
from the input features, while layers with neurons that have small RF size
capture local details with high resolution from the input features. In this
work, we introduce novel deep multi-resolution fully convolutional neural
networks (MR-FCN), where each layer has a range of neurons with different RF
sizes to extract multi-resolution features that capture the global and local
information from its input features. The proposed MR-FCN is applied to separate
the singing voice from mixtures of music sources. Experimental results show that
using MR-FCN improves the performance compared to feedforward deep neural
networks (DNNs) and single resolution deep fully convolutional neural networks
(FCNs) on the audio source separation problem.
