This repository contains data for quasar host galaxies deb lending. 

* Folder `acs_mosaic_2.0` contains COSMOS HST data in band `F814w`
* Folder `HSC_Images` contains images of the same quasars observed with HSC. It contains images for bands G, R, I, Z and Y from the deep-ultra deep fields of data release 2.
* Folder `HSC_PSF` contains the PSF for each HSC image in each band.
* Folder `Extract` contains the script and files used to query the HSC database and recover the images.


All files begin with a number between 2 and 70, which is used as an identifier for the source. These numbers match between the different observations, such that a given quasar's image in a given survey has the same identifier across surveys. The PSF file names also follow this convention.
