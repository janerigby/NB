Jane's ipython notebooks simple tutorials for using python to do astronomical data
reduction and visualization, in ipython notebook format.  Files:

Example pyds9.ipynb:
A simple tutorial for pyds9, to call ds9 from python.  Includes the
useful feature of plotting numpy arrays that aren't saved to a file.

Example pyds9 and pyregion.ipynb:
Simple tutorial that uses ds9 (not icky imshow), pyds9, and pyregions
to create some ds9 regions files, interact with fits files, and plot
in ds9.

MRD to Pandas to Seaborn plot.ipynb:
This example downloads a machine-readable table from an ApJS journal
article, reads it in with astropy, converts to a Pandas data frame,
filters the data, and then plotsa density plot using Seaborn.

Filter 3D-HST catalog and plot R_e, sersic index.ipynb:

Groovy example of dealing w big astronomical catalogs using Pandas.
Here's what it does:
    * Read the 3D-HST master catalog
    * Filter to a subset of galaxies with given stellar mass and redshift,
    * Read in Arjen's catalogs of morphological parameters fit (using Galfit).
	  Concatenate catalogs for each deep field to a single catalog
    * Grab structural parameters (R_e and sersic index) from Arjen's catalogs
	for the selected objects from the 3D-HST master catalog.  This is easy
	because Arjen and 3D-HST used the same phot_ID = NUMBER for
	each field.  I made a convenience index JRRID that is in common, and
	unique, between the two tables.  It's just field + ID.
   * Plot the results

LUVOIR_SFR.ipynb:
Still in progress.  LUVOIR science case of spectroscopy of outflows from
star-forming regions in distant galaxies.

JRR_NB_example.ipynb:
Ancient example of using ipython notebook.  Probably obselete.








