# MEG FOOOF

Project repository, part of the `parameterizing neural power spectra` project. 

This repository applies spectral parameterization to MEG data.

[![Paper](https://img.shields.io/badge/Paper-nn10.1038-informational.svg)](https://doi.org/10.1038/s41593-020-00744-x)

## Overview

This repository applies the [spectral parameterization](http://github.com/fooof-tools/fooof) algorithm to MEG data.

Analyses include:
- applying power spectrum parameterization to a large dataset of resting state MEG data
- exploring the spectral parameters across the cortex with source projected data

## Project Guide

You can follow along with this project by looking through everything in the `notebooks`.

## Reference

The analyses in this repository were done as part of the
[`parameterizing neural power spectra`](https://doi.org/10.1038/s41593-020-00744-x) paper.

A guide to all the analyses included in this paper is available
[here](https://github.com/fooof-tools/Paper).

## Requirements

This project was written in Python 3 and requires Python >= 3.7 to run.

Dependencies include 3rd party scientific Python packages:
- [numpy](https://github.com/numpy/numpy)
- [scipy](https://github.com/scipy/scipy)
- [matplotlib](https://github.com/matplotlib/matplotlib)

In addition to general scientific Python packages, this analysis requires:
- [omapping](https://github.com/voytekresearch/omapping)
- [fooof](https://github.com/fooof-tools/fooof) == 1.0.0

## Repository Layout

This project repository is set up in the following way:
- `notebooks/` is a collection of Jupyter notebooks that step through the project and create the figures

## Data

This project uses magnetoencephalograpy (MEG) data, from the HCP project.
