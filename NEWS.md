# CruzPlot 1.0 (in development)

### General

* Reorganize CruzPlot tabs and sections for a cleaner display

* Make saved workspace more robust - workspaces saved with past versions of CruzPlot are no longer compatible

### Map

* Make map size dynamic and responsive to window size, and give the user dynamic control of the map window height

* Allow user to specify the resolution of saved map

* Fix bug in tick labels where style '120' did not display negative values

* Add buttons for five default map ranges

* Remove StarterVals.csv - this functionality has been replaced by the default range buttons and being able to save multiple workspaces

* Allow user to control the download and import of bathymetric files for depth shading

### DAS data

* Use [swfscDAS](https://smwoodman.github.io/swfscDAS/) for processing DAS data

* Users can load their own species code file or use default SpCodes.dat

* Sightings can be plotted by event code (S/K/M/G/p). TODO - add s/g events, and ability to symbol-code by event code

* Sightings can be filtered by mode and effort type

* Simplified effort can be filtered by effort type (standard/non-standard/fine)

* Users can now provide colors for color-coding detailed effort by Beaufort

* Cruise number filters now are a dynamic dropdown with the cruise numbers from the DAS data


# CruzPlot 0.1
* Initial version - CruzPlot converted from a collection of scripts to an R package
