Analysis and visualization of spectroscopic imaging data.

Contents
------

See the project homepage [here](http://openmsi.nersc.gov/).
More information about the file-format, API, and tools can be found [here](https://openmsi.nersc.gov/site_media/openmsi/openmsi-tk-doc/index.html).

The below chapters are rendered via the *nbviewer* at
[nbviewer.ipython.org/](http://nbviewer.ipython.org/), and is read-only and rendered in real-time.
Interactive notebooks + examples can be downloaded by cloning this repo. 

* [**Chapter 1: Getting Started**](http://nbviewer.ipython.org/urls/raw.github.com/BenBowen/openmsi-programmatic-access/master/Chapter1/Chapter1_GettingStarted.ipynb)
    Introduction to the methods available and described. Examples include:
    - Plotting a spectra for a location
    - Showing an image for a range of m/z
    
* [**Chapter 2: Digging into the data**](http://nbviewer.ipython.org/urls/raw.github.com/BenBowen/openmsi-programmatic-access/master/Chapter2/Chapter2_DiggingIntoTheData.ipynb)
    Description of some frequently used analysis. Examples include:
    - Averaging spectra for a region around a position
    - Plotting a difference spectrum
    - Image analysis of two different ions
    
* [**Chapter 3: Adding an analysis**](http://nbviewer.ipython.org/urls/raw.github.com/BenBowen/openmsi-programmatic-access/master/Chapter3/Chapter3_AddingAnAnalysis.ipynb)
    Adding one of the OpenMSI analysis entries to a file. Examples include:
    - TIC normalization
    - Factorizations
    - Clustering
    
* [**Chapter 4: Matrix Factorizations**](http://nbviewer.ipython.org/urls/raw.github.com/BenBowen/openmsi-programmatic-access/master/Chapter4/Chapter4_MatrixFactorizations.ipynb)
    Because matrix factorizations are so widespread in spectral analysis, a chapter is dedicated to them.  Examples include:
    - Calculation of the CX/CUR factorization from the full SVD
    
* [**Chapter 5: Describing an Experiment**](http://nbviewer.ipython.org/urls/raw.github.com/BenBowen/openmsi-programmatic-access/master/Chapter5/Chapter5_DescribingAnExperiment.ipynb)
    Adding metadata describing samples, experiments, and instrumentation.  Examples include:
    - Get a file's metadata
    - Edit a file's metadata
    
* [**Chapter 6: Hilbert Space Filling Curve**](http://nbviewer.ipython.org/urls/raw.github.com/BenBowen/openmsi-programmatic-access/master/Chapter6/Chapter6_HilbertSpaceFillingCurve.ipynb)
    Alternate visualization of dense spectra. Examples include:
    - Comparing the spectra at two locations
    
* [**Chapter 7: Access to private data**](http://nbviewer.ipython.org/urls/raw.github.com/BenBowen/openmsi-programmatic-access/master/Chapter7/Chapter7_AccessToPrivateData.ipynb)
    A quick tutorial on how to authenticate and login. Examples include:
    - logging in

* [**Chapter 8: Convert Data to OpenMSI Format**](http://nbviewer.ipython.org/urls/raw.github.com/BenBowen/openmsi-programmatic-access/master/Chapter8/Chapter8_convertDataToOpenMSI.ipynb)
    A quick tutorial on how to convert files. Examples include:
    - mzML, imzML, and img formated data
    - adding metadata
    - adding analysis tasks to the initial file conversion

* [**Chapter 9: Kinetic Mass Spectrometry Imaging (kMSI) **](http://nbviewer.ipython.org/urls/raw.github.com/BenBowen/openmsi-programmatic-access/master/Chapter9/Chapter9_kMSI.ipynb)
    For deuterium adminstration, how to make and analyze kinetic images. Examples include:
    - Ratio images for isotopologues
    - Dealing with overlapping isotopic patterns
    - Chemical Formulae, Isotopic Pattern Estimation, and Fitting
