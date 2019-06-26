---
layout: post
comments: false
description: "Winter et al. - Database of Binaural Room Impulse Responses of an
Apartment-Like Environment"
author: "F Winter, H Wierstorf, A Podlubne, T Forgue, J Manhès, M Herrb,
S Spors, A Raake, P Danès"
title: "Database of Binaural Room Impulse Responses of an
Apartment-Like Environment"
proceedings: "140th Convention of the Audio Engineering Society"
short: "AES"
ebriefnumber: "252"
year: "2016"
link: "http://www.aes.org/e-lib/browse.cfm?elib=18156"
paper: "winter_et_al-2016-database_of_binaural_room_impulse_responses_of_an_apartment-like_environment.pdf"
published: true
---

### Bibtex

```latex
@inproceedings{Winter2016a,
    title     = {Database of Binaural Room Impulse Responses of an
                 Apartment-Like Environment},
    author    = {Winter, Fiete and Wierstorf, Hagen and Podlubne, Ariel
                 and Forgue, Thomas and Manh\`{e}s, J\'{e}rome
                 and Herrb, Matthieu and Spors, Sascha and Raake, Alexander
                 and Dan\`{e}s, Patrick},
    booktitle = {140th Convention of the Audio Engineering Society},
    address   = {Paris, France},
    pages     = {eBrief 252},
    month     = {June},
    year      = {2016},
    url       = {http://www.aes.org/e-lib/browse.cfm?elib=18156}
}
```

### Abstract

We present a database of binaural room impulse responses (BRIRs) measured in an
apartment-like environment. The BRIRs were captured at four different sound
source positions, each combined with four listener positions. A head and torso
simulator (HATS) with varying head-orientation in the range of ± 78 degrees with
2-degrees resolution was used. Additionally, BRIRs of 20 listener positions
along a trajectory connecting two of the four positions were measured, each with
a fixed head-orientation. The data is provided in the Spatially Oriented Format
for Acoustics (SOFA) and it is freely available under the Creative Commons
(CC-BY-4.0) license. It can be used to simulate complex acoustic scenes in order
to study the process of auditory scene analysis for humans and machines.

### Supplementary Material

The data is stored in the [SOFA format](http://sofaconventions.org) and a
corrected version can be freely download at
[10.5281/zenodo.49357](https://doi.org/10.5281/zenodo.49357).

The easiest way to access the BRIRs in the SOFA format is most probably by using
Matlab together with the [SOFA API for
Matlab](https://github.com/sofacoustics/API_MO) and the
[`get_ir()`](https://github.com/sfstoolbox/sfs/blob/master/SFS_ir/get_ir.m)
function from the [Sound Field Synthesis
Toolbox](https://sfs-matlab.readthedocs.io).
