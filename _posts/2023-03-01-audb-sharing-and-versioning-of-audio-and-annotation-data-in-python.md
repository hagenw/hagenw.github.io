---
layout: post
comments: false
description: "Wierstorf et al. - audb -- Sharing and Versioning of Audio and Annotation Data in Python"
author: "H Wierstorf, J Wagner, F Eyben, F Burkhardt, BW Schuller"
title: "audb -- Sharing and Versioning of Audio and Annotation Data in Python"
journal: "preprint arXiv:2303.00645"
journalshort: "arXiv"
pages:
volume:
number:
year: "2023"
link: "https://arxiv.org/abs/2303.00645"
paper: "wierstorf_et_al-2023-audb-sharing-and-versioning-of-audio-and-annotation-data-in-python.pdf"
presentation: 
published: true
---

### Bibtex

```latex
@article{Wierstorf2023a,
    title   = {audb -- Sharing and Versioning of Audio and Annotation Data in Python},
    author  = {Wierstorf, Hagen and Wagner, Johannes and Eyben, Florian
               and Burkhardt, Felix and Schuller, Bj\"{o}rn W.},
    journal = {arXiv preprint arXiv:2303.00645},
    year    = {2023},
    url     = {https://arxiv.org/abs/2303.00645}
}
```

### Abstract

Driven by the need for larger and more diverse datasets to pre-train and
fine-tune increasingly complex machine learning models, the number of datasets
is rapidly growing. audb is an open-source Python library that supports
versioning and documentation of audio datasets. It aims to provide a
standardized and simple user-interface to publish, maintain, and access the
annotations and audio files of a dataset. To efficiently store the data on a
server, audb automatically resolves dependencies between versions of a dataset
and only uploads newly added or altered files when a new version is published.
The library supports partial loading of a dataset and local caching for fast
access. audb is a lightweight library and can be interfaced from any machine
learning library. It supports the management of datasets on a single PC, within
a university or company, or within a whole research community.

### Supplementary material

audb is available at
[https://github.com/audeering/audb](https://github.com/audeering/audb).
