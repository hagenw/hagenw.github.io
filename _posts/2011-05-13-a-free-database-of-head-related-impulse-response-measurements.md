---
layout: post
comments: false
description: "Wierstorf et al. - A Free Database of Head Related Impulse
Response Measurements in the Horizontal Plane with Multiple Distances"
author: "H Wierstorf, M Geier, S Spors"
title: "A Free Database of Head Related Impulse Response Measurements in the
Horizontal Plane with Multiple Distances"
proceedings: "130th Convention of the Audio Engineering Society"
short: "AES"
ebriefnumber: "6"
year: "2011"
link: "http://www.aes.org/e-lib/browse.cfm?elib=16564"
paper: "wierstorf_et_al-2011-a_free_database_of_head-related_impulse_response_measurements.pdf"
poster: "wierstorf_et_al-2011-a_free_database_of_head-related_impulse_response_measurements-poster.pdf"
published: true
---

### Bibtex

```latex
@inproceedings{Wierstorf2011b,
  	title = {A Free Database of Head Related Impulse Response Measurements in
             the Horizontal Plane with Multiple Distances},
    author = {Wierstorf, Hagen Geier, Matthias and and Spors, Sascha},
    booktitle = {130th Convention of the Audio Engineering Society},
    address = {London, UK},
    pages = {eBrief 6},
    month = {May},
    year = {2011},
    url = {http://www.aes.org/e-lib/browse.cfm?elib=16564}
}
```

### Abstract

A freely available collection of Head-Related Impulse Response (HRIR)
measurements is introduced. The impulse responses were acquired in an anechoic
chamber using a KEMAR manikin at four different loud- speaker distances – 3 m, 2
m, 1 m and 0.5 m – reaching from the far field to the near field. The
loudspeaker was positioned at ear height and the manikin was rotated with a
high-precision stepper motor in one degree increments. Besides the raw HRIRs
also datasets are available which have been compensated for the use with
specific headphone models.


### Supplementary Material

The original data base has been converted into the [SOFA
format](http://sofaconventions.org) in the meantime and published under
[10.5281/zenodo.55418](http://dx.doi.org/10.5281/zenodo.55418).

Vera Erbes created a [short version of the 3 m HRTF with low frequency
corrections](https://github.com/spatialaudio/lf-corrected-kemar-hrtfs). This
might be the best data set to start with for daily usage.

The easiest way to access the HRTFs in the SOFA format is most probably by using
Matlab together with the [SOFA API for
Matlab](https://github.com/sofacoustics/API_MO) and the
[`get_ir()`](https://github.com/sfstoolbox/sfs/blob/master/SFS_ir/get_ir.m)
function from the [Sound Field Synthesis
Toolbox](http://matlab.sfstoolbox.org/).
