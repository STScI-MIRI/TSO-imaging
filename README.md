# TSO-imaging
calculating the SNR of MIRI imaging as a function of extraction aperture &amp; filter using Pandeia. 

## Description
This repository contains a .json file and jupyter notebook which are used to calculate the signal to noise ratio (SNR) of MIRI imaging, as a function of extraction aperture size, for all MIRI imaging filters. The simulations were performed in response to an SCSB request to provide photometric extraction apertures for MIRI time series imaging.

## How-To
Executing the jupyter notebook requires installation of Pandeia and the Pandeia data package (see the STScI-SSB/pandeia and STScI-SSB/pandeia_data repositories). Installation of Pandeia should automatically install any dependencies.

The .json file can be copied and changes made to run the calculations with different settings. .json files can be opened with a text editor, and the parameters should be self-explanatory for regular ETC users. For further details on input and output options for Pandeia json files, see the entries in [this repository](https://github.com/spacetelescope/pandeia-tutorials/tree/master/reference).

## Author, Date
Sarah Kendrew, sarah.kendrew@esa.int -- March 20th 2018
