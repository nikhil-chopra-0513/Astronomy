## SECTION 2 - DATA

### Data Sources
<p> There are 3 main types of astronomical observation data, all of which are taken from space telescopes such as NASA's Kepler and TESS missions; these include: target pixel files, lightcurves and stellar information in the form of tabular data. This project used lightcurves as the data is almost in its raw form as extracted from the telescopes and it is in a form that can be loaded into machine learning pipelines with some relatively light processing. 

<p align="center">
  <img src="https://exoplanets.nasa.gov/system/resources/detail_files/280_656348main_ToV_transit_diag.jpg">
</p>

The data was taken and combined from 2 sources: [Kepler Object of Interest (KOI) Activity Tables -  Cumulative Table](https://exoplanetarchive.ipac.caltech.edu/cgi-bin/TblView/nph-tblView?app=ExoTbls&config=cumulative) from which more information is available [here](https://exoplanetarchive.ipac.caltech.edu/docs/KeplerMission.html). This returns a list of all the stars that the Kepler mission has observed, but not the lightcurves themselves. To obtain the lightcurves themselves, the python package [Lightkurve](https://docs.lightkurve.org/) is used. </p> 

