# dHCP - modified for surface extraction

!This is a modified version of the dHCP pipeline! It's adapted for inner and pial surface reconstruction using labels that aren't
Draw-EM's.

The dHCP structural pipeline performs structural analysis of neonatal brain
MRI images (T1 and T2) and consists of:

* cortical and sub-cortical volume segmentation
* cortical surface extraction (white matter and pial surface)
* cortical surface inflation and 
* projection to sphere

It is described in detail in:

A. Makropoulos, E. C. Robinson et al. *"The Developing Human Connectome
Project: a Minimal Processing Pipeline for Neonatal Cortical Surface
Reconstruction"* [link](http://biorxiv.org/content/early/2017/04/07/125526)

### Developers

**Antonios Makropoulos**: main author, developer of the structural pipeline,
and segmentation software. [more](http://antoniosmakropoulos.com)

**Andreas Schuh**: contributor, developer of the cortical surface extraction,
and surface inflation software. [more](http://andreasschuh.com)

**Robert Wright**: contributor, development of the spherical projection
software.

### License

The dHCP structural pipeline is distributed under the terms outlined in
[LICENSE.txt](LICENSE.txt).

