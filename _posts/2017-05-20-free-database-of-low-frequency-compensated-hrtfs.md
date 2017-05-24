---
layout: post
comments: false
description: "Erbes, Geier, Wierstorf, and Spors - Free database of low-frequency corrected head-related transfer functions and headphone compensation filters"
author: "V Erbes, M Geier, H Wierstorf, S Spors"
title: "Free database of low-frequency corrected head-related transfer functions and headphone compensation filters"
proceedings: "142nd Convention of the Audio Engineering Society"
short: "AES"
ebriefnumber: "325"
year: "2017"
link: "http://www.aes.org/e-lib/browse.cfm?elib=18700"
paper: "erbes_et_al-2017-free_database_of_low-frequency_compensated_hrtfs.pdf"
published: true
---

### Bibtex

```latex
@inproceedings{Erbes2017a,
  	title = {Free database of low-frequency corrected head-related transfer
    functions and headphone compensation filters},
    author = {Erbes, Vera and Geier, Matthias and Wierstorf, Hagen and Spors, Sascha},
    booktitle = {142nd Convention of the Audio Engineering Society},
    address = {Berlin, Germany},
    pages = {eBrief 325},
    month = {May},
    year = {2017},
    url = {http://www.aes.org/e-lib/browse.cfm?elib=18700}
}
```

### Abstract

A database of publicly available head-related transfer functions (HRTFs) of a
KEMAR manikin together with headphone compensation filters for various headphone
types is presented. The HRTFs are based on previously published data from
Wierstorf et al. (2011) that have additionally been corrected for low
frequencies. This compensates for missing information due to low excitation
energy in this frequency range during the measurement and allows for shorter
impulse responses. A further benefit is demonstrated by the interpolation of
HRTFs via magnitude and phase that is only possible with consistent phase
information. Both the low-frequency correction as well as the generation of the
headphone compensation filters are accompanied by Matlab code to document the
processing.

### Supplementary material

The low frequency corrected HRTF database is available under
[10.5281/zenodo.401041](https://doi.org/10.5281/zenodo.401041).
The headphone compensation filters are available under
[10.5281/zenodo.401042](https://doi.org/10.5281/zenodo.401042).
Note, that the compensation filters are not suited for the low-frequency
corrected HRTF data as the microphone positions varied between the two used
KEMAR heads, but they can be used with the BRIR measurement of a rectangular
loudspeaker array available under
[10.14279/depositonce-87.6](https://doi.org/10.14279/depositonce-87.6).
For the low frequency corrected HRTFs there are headphone compensation filters
available with the original - non low frequency corrected - release of the data
at [10.5281/zenodo.55418](https://doi.org/10.5281/zenodo.55418).
