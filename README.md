# MiniSOM_tutorial
MiniSOM Tutorial for 2-D Atmospheric Data and Example Using Mean Sea Level Pressure Data 

This repository covers the process of taking 2-D Atmospheric Data and generating a Self-Organizing Map, SOM, out of that data. Self-organizing Maps, SOMs, are a form of unsupervised learning that utilizes a competitive neural network to cluster alike data. SOMs are like the clustering technique used in K-means. SOMs take multidimensional data and reduce it to a two-dimensional array that can be easily visualized. Patterns that share similar characteristics are grouped adjacent to one another; whereas patterns that share minimal similarities are grouped on opposing sides of the SOM.

The first step of this tutorial is to reduce the dimensions of the selected atmospheric data. For this example, mean sea level pressure (MSLP) data will be used. The data itself is 3-D data. The code will reduce that data to 2-D, and place the data into a format that the MiniSOM code can utilize to generate SOMs.


The second step of this tutorial is the generation of the SOMs themselves and the visualization of the SOM output. Frequency and Sammon Plots will be generated for each SOM. The MSLP anomaly SOMs will be made as well to easily visualize the data.
All files output from this tutorial are included within the repository as well as the MSLP NCEP/DOE Reanalysis II file used as the atmospheric data. 

# Selected Required Packages
This is not exhaustive list of all packages reuqired to run both notebooks

[xarray](https://docs.xarray.dev/en/stable/)

[minisom](https://github.com/JustGlowing/minisom)

[cartopy](https://scitools.org.uk/cartopy/docs/latest/)

There are other python SOM packages, but minisom is one of the more well used ones, and is updated often. Sklearn-som (not affiliated with scikit-learn project, just similar API) is another option, but has not has an updated in 2+ years. 

# License

*license information will go here*
