# Dipy Workflow Wrapper

This is a Brainlife wrapper App for `dipy_buan_shapes` workflow. This single wrapper is exposed through an apps registered on [Brainlife.io](https://brainlife.io).

- More information about DIPY : [https://dipy.org/](https://dipy.org/)
- More information about the command line `dipy_buan_shapes`: [Command line Reference](https://dipy.org/documentation/1.2.0./interfaces/buan_flow/)

## App Description

 The `dipy_buan_shapes` app finds shape similarity between input bundles of same type across populations. This app implements bundle shape similarity method presented in Bundle analytics, a computational framework for investigating the shapes and profiles of brain pathways across populations paper [1].

## Authors

[Bramsh Chandio](https://github.com/BramshQamar)

### Funding Acknowledgement
DIPY is publicly funded and for the sustainability of the project it is helpful to Acknowledge the use of the software. We kindly ask that you acknowledge the funding below in your publications and code reusing this code.

[![NIH-NIBIB-R01EB027585](https://img.shields.io/badge/NIH_NIBIB-R01EB027585-green.svg)](https://grantome.com/grant/NIH/R01-EB027585-01)
[![NIH-NIMH-RF1MH121868](https://img.shields.io/badge/NIH_NIMH-RF1MH121868-green.svg)](https://grantome.com/grant/NIH/RF1-MH121868-01)
[![NIH-NIMH-R01MH108467](https://img.shields.io/badge/NIH_NIMH-R01MH108467-green.svg)](https://grantome.com/grant/NIH/R01-MH108467-01)
[![NSF-BCS-1734853](https://img.shields.io/badge/NSF_BCS-1734853-blue.svg)](https://nsf.gov/awardsearch/showAward?AWD_ID=1734853)
[![NSF-EEC-1720625](https://img.shields.io/badge/NSF_BCS-1720625-blue.svg)](https://nsf.gov/awardsearch/showAward?AWD_ID=1720625)
[![NSF-OAC-1916518](https://img.shields.io/badge/NSF_OAC-1916518-blue.svg)](https://nsf.gov/awardsearch/showAward?AWD_ID=1916518)
[![NSF-IIS-1912270](https://img.shields.io/badge/NSF_IIS-1912270-blue.svg)](https://nsf.gov/awardsearch/showAward?AWD_ID=1912270)
[![NSF-IIS-1636893](https://img.shields.io/badge/NSF_IIS-1636893-blue.svg)](https://nsf.gov/awardsearch/showAward?AWD_ID=1636893)

## Citations

[1] Chandio, BQ., et al. Bundle analytics, a computational framework for investigating the shapes and profiles of brain pathways across populations. Scientific reports,  10, 17149 (2020).

## Running the App

#### 1. On Brainlife.io

You can see a list of [Dipy Apps currently regsitered on Brainlife](https://brainlife.io/apps#dipy). Find the App that you'd like to run and click "Execute" tab to specify dataset that you'd like to run the App on.

#### 2. On  your machine (Running Locally)

To run this command, you can simply type:

`singularity exec -e docker://brainlife/dipy:1.1.1 dipy_buan_shapes [your_args]`

To see the documentation of all arguments, [go to the following page](https://dipy.org/documentation/1.2.0./interfaces/buan_flow/)

### Dependencies

This app runs on [singularity](https://www.sylabs.io/singularity/).


#### DIPY is licensed under the terms of the BSD license. Please see the [LICENSE file](https://github.com/dipy/dipy/blob/master/LICENSE).

