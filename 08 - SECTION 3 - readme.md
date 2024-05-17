## SECTION 3 - DATA PROCESSING

### Data Processing Necessity

<p>As seen above, the lightcurves are time-series data with light flux being the variable which evolves over time. This data is not readily inputtable into machine learning models for several reasons: most models apart from a few primitive ones (such as K-Nearest Neighbours) cannot deal with time-series data that is not of equal length; and the same goes for the NaNs present in the data. Additionally, there are long-term trends arising from dying stars and other phenomena which may affect the readings, as well as outliers in the data. All of this means processing the data is necessary. </p>

### Processing Methodolgy
<p> To end up with correctly formatted data, 2 approaches were undertaken. </p>

<ol>
  <li> Global View: This meant following the approach outlined in this paper to generate a global view: https://arxiv.org/pdf/1712.05044.pdf, which was implemented in python with the Lighkurve package based on this tutorial: https://docs.lightkurve.org/tutorials/3-science-examples/exoplanets-machine-learning-preprocessing.html. <img align="middle" src="https://docs.lightkurve.org/_images/tutorials_3-science-examples_exoplanets-machine-learning-preprocessing_19_0.png"> </li>
  <li> Raw View: The idea behind this approach is to take the raw lighcurves, and apply the lowest levels of processing that allow it to be inputted into machine learning models. This involves removing outliers and converting the curves into equally spaced time-steps.</li>
</ol>
