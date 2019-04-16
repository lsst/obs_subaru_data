# calib_base_data_lsst
A repository for storing versioned calibration data for LSST instruments.


## Introduction
This repository is intended to hold only data and posibly scons configuration files.
These data will then be processed further into calibration products that can be ingested into a calibration repository.

Code to do the processing from base calibration data to ingested calibration products should reside in `obs_base` with possible overrides in the `obs_lsst` package.
