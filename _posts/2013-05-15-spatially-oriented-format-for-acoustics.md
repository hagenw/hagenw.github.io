---
layout: post
comments: false
description: "Majdak et al. - Spatially Oriented Format for Acoustics: A Data
Exchange Format Representing Head-Related Transfer Functions "
author: "P Majdak, T Carpentier, R Nicol, M Parmentier, A Roginska, Y Suzuki,
K Watanabe, H Wierstorf, H Ziegelwanger, M Noisternig"
title: "Spatially Oriented Format for Acoustics: A Data Exchange Format
Representing Head-Related Transfer Functions"
inproceedings: "Audio Engineering Society Convention 134"
papernumber: "8880"
year: "2013"
url: "http://www.aes.org/e-lib/browse.cfm?elib=16781"
paper: "majdak_et_al-2013-spatially_oriented_format_for_acoustics.pdf"
presentation: 
published: true
---

### Bibtex

```latex
@inproceedings{Majdak2013,
  	title = {Spatially Oriented Format for Acoustics: A Data Exchange Format Representing Head-Related Transfer Functions},
    author = {Majdak, Piotr and Iwaya, Yukio and Carpentier, Thibaut and Nicol, Rozenn and Parmentier, Matthieu and Roginska, Agnieszka and Suzuki, Yoiti and Watanabe, Kankji and Wierstorf, Hagen and Ziegelwanger, Harald and Noisternig, Markus},
    booktitle = {Audio Engineering Society Convention 134},
    year = {2013},
    url = {http://www.aes.org/e-lib/browse.cfm?elib=16781}
}
```

### Abstract

Head-related transfer functions (HRTFs) describe the spatial filtering of the
incoming sound. So far available HRTFs are stored in various formats, making an
exchange of HRTFs difficult because of incompatibilities between the formats. We
propose a format for storing HRTFs with a focus on interchangeability and
extendability. The spatially oriented format for acoustics (SOFA) aims at
representing HRTFs in a general way, thus, allowing to store data such as
directional room impulse responses (DRIRs) measured with a microphone-array
excited by a loudspeaker array. SOFA specifications consider data compression,
network transfer, a link to complex room geometries, and aim at simplifying the
development of programming interfaces for Matlab, Octave, and C++. SOFA
conventions for a consistent description of measurement setups are provided for
future HRTF and DRIR databases.

### Supplementary material

The SOFA HRTF format has become an AES standard in the meantime, see
http://www.aes.org/publications/standards/search.cfm?docID=99

For more information on the format and available data bases, see
https://www.sofaconventions.org

Implementations of an API in Matlab/Octave and C++ can be found at
https://github.com/sofacoustics
