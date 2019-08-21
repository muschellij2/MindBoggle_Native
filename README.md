
<!-- README.md is generated from README.Rmd. Please edit that file -->

# MindBoggle

<!-- badges: start -->

[![License: CC
BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)
<!-- badges: end -->

The goal of the `MindBoggle` repositories is to host data from
<https://mindboggle.info/> in a format that allows users to download
specific subjects and not the entire data set.

# How the data is organized

All the data was downloaded by MindBoggle Release 3 from the Open
Science Framework page: <https://osf.io/9ahyp/>, from the
`Mindboggle101_volumes` folder. Each tarball was downloaded and
unzipped. The `Extra-18` tarball was reorganized to be consistent with
the other studies. The format is that the top-level folder is the
“study” and each subfolder is a subject with the root being the
study name and then a hyphen and an index for the subject of that study.
To find the orignal source of the data, please see the README from
<https://osf.io/9ahyp/>.

The `DKT` stands for the Desikan-Killiany-Tourville protocol. The
`+aseg` refers to the FreeSurfer’s wmparc + aseg non-cortical (+ white
matter) labeling procedure. Please see
<https://mindboggle.readthedocs.io/en/latest/labels.html> for more
information.

The files include labeled surfaces and structures and unlabeled heads
and brains. Each subject folder has the following files.:

  - t1weighted.nii.gz - T1-weighted image
  - t1weighted\_brain.nii.gz - T1-weighted image with brain extracted
  - labels.DKT31.manual.nii.gz - Desikan-Killiany-Tourville labeled
    brain
  - labels.DKT31.manual+aseg.nii.gz - Desikan-Killiany-Tourville labeled
    brain with Freesurfer labels
  - t1weighted\_brain.MNI152.affine.txt - affine transformation from
    native space image to MNI152

# Licensing

As per the README from <https://osf.io/9ahyp/>:

Please cite the following article and website when making use of these
data or the labeling protocol:

“101 labeled brain images and a consistent human cortical labeling
protocol” Arno Klein, Jason Tourville. Frontiers in Brain Imaging
Methods. 6:171. DOI: 10.3389/fnins.2012.00171
<http://www.frontiersin.org/Brain_Imaging_Methods/10.3389/fnins.2012.00171/full>

Copyright 2012, Mindboggle team (<http://mindboggle.info>), Creative
Commons License (<http://creativecommons.org/licenses/by/4.0>)
[![License: CC
BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)
