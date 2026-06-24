This repository contains the analysis code and supporting files used to study the effect of Mars-analog dust coatings on visible to shortwave infrared reflectance spectra of mineral powders.

The main analysis scripts are written to work with a NetCDF dataset containing laboratory bidirectional reflectance spectra measured under multiple illumination-viewing geometries for uncoated and dust-coated mineral samples. Users who wish to run the full analysis will need to provide the corresponding NetCDF file separately, or adapt the input paths in the code to their own dataset.

The analysis code is designed for a laboratory dataset containing spectra for a suite of Mars-relevant minerals measured using a spectrogoniometer across the VIS–SWIR wavelength range. Each mineral was measured under three surface conditions: uncoated, lower dust coating, and higher dust coating. The code uses measurements collected across multiple incidence, emission, and azimuth angles to evaluate how optical geometry influences spectral contrast, absorption-band masking, and dust-related changes in reflectance.

The expected NetCDF structure includes raw replicate spectra, processed reflectance spectra, experimental dust-loading spectra, phase-angle information, and dust areal-density values for each mineral coating. These variables are used in the scripts to reproduce the spectral analysis, examine wavelength-dependent dust attenuation, compare coated and uncoated spectra, and test geometry-dependent spectral behaviour.

In addition to the analysis scripts, this repository includes supporting photographs used by the plotting and analysis code. Thermogravimetric analysis (TGA) data for the MGS-1 dust analogue are also provided in CSV format.
