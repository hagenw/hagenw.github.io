---
layout: post
comments: false
description: "Majdak et al. - Spatially Oriented Format for Acoustics: A Data
Exchange Format Representing Head-Related Transfer Functions "
author: "P Majdak, T Carpentier, R Nicol, M Parmentier, A Roginska, Y Suzuki,
K Watanabe, H Wierstorf, H Ziegelwanger, M Noisternig"
title: "Spatially Oriented Format for Acoustics: A Data Exchange Format
Representing Head-Related Transfer Functions"
proceedings: "134th Convention of the Audio Engineering Society"
short: "AES"
papernumber: "8880"
year: "2013"
link: "http://www.aes.org/e-lib/browse.cfm?elib=16781"
paper: "majdak_et_al-2013-spatially_oriented_format_for_acoustics.pdf"
published: true
---

### Bibtex

```latex
@inproceedings{Majdak2013,
    title     = {Spatially Oriented Format for Acoustics: A Data Exchange
                 Format Representing Head-Related Transfer Functions},
    author    = {Majdak, Piotr and Iwaya, Yukio and Carpentier, Thibaut and
                 Nicol, Rozenn and Parmentier, Matthieu and Roginska, Agnieszka
                 and Suzuki, Yoiti and Watanabe, Kankji and Wierstorf, Hagen
                 and Ziegelwanger, Harald and Noisternig, Markus},
    booktitle = {134th Convention of the Audio Engineering Society},
    address   = {Roma, Italy},
    month     = {May},
    year      = {2013},
    url       = {http://www.aes.org/e-lib/browse.cfm?elib=16781}
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
[http://www.aes.org/publications/standards/search.cfm?docID=99](http://www.aes.org/publications/standards/search.cfm?docID=99)

For more information on the format and available data bases, see
[https://www.sofaconventions.org](https://www.sofaconventions.org)

API implementations in Matlab/Octave and C++ can be found at
[https://github.com/sofacoustics](https://github.com/sofacoustics)

Two example applications using the API and providing more functionality like
getting the impulse response for a particular listening position and direction
are the [Two!Ears Binaural Simulator](https://github.com/TWOEARS/binaural-simulator)
and the [Sound Field Synthesis Toolbox](https://github.com/sfstoolbox/sfs), in
particular
[`get_ir()`](https://github.com/sfstoolbox/sfs/blob/master/SFS_ir/get_ir.m).
