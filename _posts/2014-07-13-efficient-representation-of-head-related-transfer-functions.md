---
layout: post
comments: false
description: "Majdak et al. - Efficient representation of head-related transfer
functions using spatially oriented format for acoustics"
author: "P Majdak, H Ziegelwanger, H Wierstorf, M Noisternig"
title: "Efficient representation of head-related transfer functions using
spatially oriented format for acoustics"
proceedings: "Proceedings of the 21st International Congress on Sound and
Vibration (ICSV)"
short: "ICSV"
year: "2014"
paper: "majdak_et_al-2014-efficient_representation_of_head-related_transfer_functions.pdf"
presentation: 
published: true
---

### Bibtex

```latex
@inproceedings{Majdak2014,
  	title = {Efficient representation of head-related transfer functions using spatially oriented format for acoustics},
    author = {Majdak, Piotr and Ziegelwanger, Harald and Wierstorf, Hagen and Noisternig, Markus},
    booktitle = {Proceedings of the 21st International Congress on Sound and Vibration (ICSV)},
    address = {Beijing, China},
    month = {July},
    year = {2014},
}
```

### Abstract

Head-related transfer functions (HRTFs) describe the spatial filtering of the
incoming sound by the head, pinna, and torso of a listener. Transformed to the
time domain, HRTFs are referred to as head-related impulse responses (HRIRs).
While usually measured under free-field conditions, HRIRs are referred to as
binaural room impulse responses (BRIRs) when room effects are considered
additionally. HRIRs and BRIRs have been measured by a number of laboratories and
are usually stored using the labs' own file formats, which often complicates the
exchange of data due to format incompatibilities. Recently, the “spatially
oriented format for acoustics” (SOFA) has been proposed to unify the
representation of such data.  SOFA provides data compression, network transfer,
file hierarchy, and possibility for a link to complex room geometry data. SOFA
specifications allow to develop application programming interfaces (APIs) for
various programming languages; current implementations include Matlab and
Octave. Within SOFA, the different types of data are represented by different
conventions, i.e., defined sets of variables and attributes. In this
contribution, we introduce the general SOFA specifications and describe SOFA
conventions allowing to store HRIRs.  Currently, in the SOFA database, eight
large databases have been unified offering HRIRs/BRIRs of over 200 listeners
stored in the same format.

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
