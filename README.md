## Spectroscopy of SN 1987A

### Introduction and history
This repository provides data and a basic analysis walkthrough for spectroscopy measurements of the SN 1987A event, taken by the Bochum telescope at the European Southern Observatory (ESO) site of La Silla, Chile. The Astronomisches Institut of Ruhr-Universität Bochum had an experienced observer doing spectroscopic work on Be stars when the supernova exploded.

The observing campaign was conducted by the group lead by Theodor Schmidt-Kaler (1930-2017). The spectroscopic measurement were at the centre of Dr. R. Hanuschik's habilitation thesis. R. Hanuschik later conceived this experiment that has been offered for years as a *F-Praktikum* (laboratory for bachelor students) at the Astronomisches Institut of Ruhr-Universität Bochum (thanks to Prof. Thomas Luks for providing the data and background information).

The original data come in the BDF format used in the ESO MIDAS software. The files in their current form date back to 1995 and it seems they cannot be read with more recent version of MIDAS. They have been exported to FITS in order to allow the use of modern and portable analysis tools. 

### Outline of the experiment
- fit Planck blackbody curves to the measured spectra in order to determine the supernova temperature at days 2, 5, 10, 20, ... 100 since the explosion;
- alternatively, determine the temperature using Wien's displacement law;
- identify P-Cygni profiles of known spectral lines (H, Na, Fe, Ba) and measure their Doppler shift (that in turn can be converted to a radial velocity / absorption radius);
- determine the bolometric luminosity using Stefan-Boltzmann law, and estimate the supernova distance exploiting absorption radiuses.

### Try with Binder
 - Data inspection: [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/nkorzoun/sn1987a-spectroscopy/HEAD?labpath=notebooks%2F01_data_inspection.ipynb)
 - Data analysis walkthrough: [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/nkorzoun/sn1987a-spectroscopy/HEAD?labpath=notebooks%2F02_data_analysis.ipynb)
