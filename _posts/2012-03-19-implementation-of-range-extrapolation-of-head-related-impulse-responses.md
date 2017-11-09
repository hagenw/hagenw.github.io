---
layout: post
comments: false
description: "Spors and Wierstorf - On the implementation of range extrapolation of head-related impulse responses by virtual sound field synthesis"
author: "S Spors, H Wierstorf"
title: "On the implementation of range extrapolation of head-related impulse
responses by virtual sound field synthesis"
proceedings: "Fortschritte der Akustik - DAGA 2012"
short: "DAGA"
pages: "311-312"
year: "2012"
paper: "spors_and_wierstorf-2012-implementation_of_range_extrapolation_of_head-related_impulse_responses.pdf"
presentation: 
published: true
---

### Bibtex

```latex
@inproceedings{Spors2012a,
    title     = {On the implementation of range extrapolation of head-related
                 impulse responses by virtual sound field synthesis},
    author    = {Spors, Sascha and Wierstorf, Hagen},
    booktitle = {Fortschritte der Akustik - DAGA 2012},
    publisher = {DEGA e.V.},
    address   = {Darmstadt, Germany},
    pages     = {311--312},
    month     = {March},
    year      = {2012}
}
```

### Abstract

Recently an approach to the range extrapolation of head-related
impulses responses (HRIRs) has been proposed which is based on
interpreting measured HRIRs as virtual secondary source distribution
which is driven according to a virtual source at the desired distance.
In principle, any sound field synthesis approach can be applied.
However, Wave Field Synthesis allows for a numerical stable and
efficient implementation of the proposed scheme. Its efficiency is
based on pre-filtering the HRIR dataset, and summing up weighted and
delayed versions of the HRIRs. In typical implementations the delay
operation is restricted to multiples of the temporal sampling interval.
In a previous study, these integer delays have been proven to be
suitable for static virtual sources synthesized by typical WFS setups.
Range extrapolation of HRIRs may involve very densely distributed
virtual secondary source distributions. Here integer delays pose limits
with respect to the achievable physical accuracy. The limits and
potential solutions will be discussed in the paper, as well as, the
perceptual consequences in the context of range extrapolation of HRIRs.
