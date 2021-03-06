# TODO

a, b, c = rank by current importance (a > b)
1, 2, 3 = rank by difficulty (1 > 2)

## Code:
* (3c) Move this TODO list to git issue tracker
* (3a) Make mag_1_field more consistent (propogate 'g','r','i' throughout)
* (2a) Switch to astropy for coordinate conversion, etc.
* (2c) Change name of ugali.utils.projector to ugali.utils.coords (obsolete with astropy)
* (2c) Consistent naming convention for pix vs. pixel
* (2c) Be careful with spatialBin function when objects fall outside of ROI (CHECK!)
* (1b) Residual maps / how to deal with gradients in background (important mainly for LMC region)
* (1c) Compute observable fraction including photometric errors
* (2c) Check for numerical issues with very small Plummer radii, sampling kernel (ADD WARNING)
* (1b) Investigate large kernel fitting accuracy, what is largest size?
* (1c) Add alternative IMFs
* (2c) Compute the absolute visual magnitude in addition to bolometric luminosity
* (3b) FNAL, Midway, SLAC config files (better to make batch-system independent)
* (2b) Merge config file with default config or store defaults in objects (probably the latter)
* (2b) Revist healpix map format; is this really what we want?
* (1c) Precompute HEALPix pixel for each object and avoid creating full HEALPix maps
* (2b) Consider updating DES isochrones
* (2b) Connect isochrone.observableFraction and mask.restrictCatalogToObservableSpace
* (2b) CMD should be masked array not clipped and pushed
* (2b) Rewrite catalog reader to use fitsio
* (2b) Compress isochrone data to easy distribution and allow for more extensive isochrone set
* (1b) Fully incorporate completeness in isochrone fitting and simulation

## DONE
* (1c) Collector function to find peaks (in 3D)
* (2c) Save stellar mass instead of richness?
* (3b) Switch to new kernel
* (2b) SDSS mask
* (2b) SDSS isochrones
* (2b) Have config read yaml files
* (2a) Elliptical kernels
* (2a) Horizontal branch dispersion
* (2b) Subclass the pipeline scripts (at least the argument parsers)
* (3c) Pass 'chatter' argument to logger
* (2a) Config file option for likelihood evaluation radius
* (3b) Rename PDF in kernels
* (3c) Farm should write out config file for future reference
* (3b) Search multiple ROIs in same batch job
* (3b) Distinguish between 'debug' (output verbosity) and 'dryrun' (don't do anything)
* (2b) Speed up observableFraction (used broadcasting)
* (3c) Consistently make use of angToPix and pixToAng
* (2b) Automated data processing to get mangle masks and catalogs from DESDM
* (2b) Separate analysis from plotting
* (2b) SVA1 data products
* (2b) Restructure and subclass isochrone
* (1b) Create true composite isochrone (subclassing isochrone) rather than container of isochrones
