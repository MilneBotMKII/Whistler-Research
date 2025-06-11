# Andrew Scripts

Scripts and materials used in the Juno Long Dispersion Whistlers project, including a copy of whistler data. Autoplot should be able to run all scripts.

##A summary of contents

FullDataWhistler.csv : A complete list of all whistler data I cataloged, including short dispersion whistlers.

WhistlerData.csv : A truncation of FullDataWhistler.csv, removing short dispersion whistlers. This should be what scripts call for.

whistlerDigitizerFit.jy: Script made by Jeremy Faden to plot Juno's radio spectra and place points to fit whistler features to the dispersion equation. This is the script used to obtain all whistler times and dispersions.

ReproducePlot.jy : Script making log10 dispersion vs. variable plots, with YMD group coloring. Remade from a python jupyter notebook script I had.

ReproduceMap.jy : Script for making footprint maps for whistlers. This includes Io or Europa footprints as well. 

WhistlerNormalization.jy : Script for showing where Juno burst mode data has been taken, where whistlers have been seen, and then a normalized plot showing how likely it is a whistler(start frame) could be seen in any given burst mode snapshot within that range.

NoodlePlot.jy : Script for making the magnetic Rho/Z plots showcasing whistler locations and magnetic field lines. Not sure if there is a more official name for this, I've always called it the noodle plot.

LocalTimePolar.jy : Script for making polar graphs using local time hourangles. 

EventsListMaker.jy : Script for making an events list for use navigating the spectra

PIA07782_hires.jpg : A background image of Jupiter for use in ReproduceMap.jy. Downloaded from https://www.jpl.nasa.gov/images/pia07782-cassinis-best-maps-of-jupiter-cylindrical-map/.
