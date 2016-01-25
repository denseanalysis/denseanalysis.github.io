---
layout: default
title: Home
---

## Introduction

Welcome to the DENSEanalysis developer group. This group is dedicated to
developing software to analyze DENSE MRI images. The software is currently
developed on MATLAB and will allow the user to

* Easily navigate DICOM and DENSE images and cine sequences
* Define regions of interest for DENSE analysis
* View and export all sorts of DENSE derived physiological information.
* View and access multi-slice data for the left- and right- ventricular motion. 


## Getting Started

### System Requirements

In order to run properly, DENSEanalysis requires:

* Matlab
* Matlab Image Analysis Toolbox
* Matlab Spline Toolbox
* Matlab C-compiler

### Prior to Installation

* If haven't compiled a mex-file in MATLAB before, run mex-setup in the MATLAB
command window to select a compiler on your machine.
* If you have a previous installation of DENSEanalysis, make sure to remove any existing
search paths point to that insallation and restart MATALB (from the MATLAB File Menu, Choose
Set Path and remove folders referring to the previous installation).

### Installation

1. Download the zip file of the updated development version from [Github]("https://github.com/denseanalysis/denseanalysis/archive/master.zip").
and unzip it into your install directory.
2. Open MATLAB and navigate to the DENSEanalysis folder.
3. Run the `DENSEsetup` command in MATLAB.

### Startup

1. Open MATLAB and navigate to the DENSEanalysis folder.
2. Run DENSEms from the MATLAB command prompt.

## What to Cite

## Additional Documention

During the transition to the new documentation format, the old documention is still available:

* [DENSEanalysis manual]({{ site.baseurl }}docs/DENSEanalysis_manual.pdf)
* [DENSEms manual]({{ site.baseurl }}docs/DENSEms_manual.pdf)
* [RV features manual]({{ site.baseurl }}/docs/RV_manual.pdf)

## Contributors

* [Andrew Gilliam](http://www.adgilliam.com/)
* [Jonathan Suever](https://github.com/suever)

    

