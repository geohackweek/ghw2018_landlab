# Project Title: Advanced Geo-spatial-temporal research software curriculum: Developing Landlab Modules to teach open source methods

[Paragraph describing the need and benefits to open source research software education in earth sciences]

Application Example and Motivation
[Landlab group on HydroShare using CI to train new students on a science domain specidfic modeling framework - How would we do that in other domains? 

Sample Application and Rubric
[Rose - Georgia Tech example - EdX; IDE for Python Enthought;  Decribe rubric as compared to online tutorials e.g. ESRI certificated, CUAHSI Virtual Classroom]

Specific Questions (breaking up of the project task)
The project contains two main parts: designing the framework for new modules and development of individual modules 

Landlab Background Links:

[Background on the model grid data model used in Landlab](https://nbviewer.jupyter.org/github/landlab/tutorials/blob/master/grid_object_demo/grid_object_demo.ipynb)

[Teach yourself Landlab](https://github.com/landlab/landlab/wiki/Teach-Yourself-Landlab!)


## 1. The Framework
The repository contains curriculum developed for geo-spatio-temporal analysis using open source research software.

### Start to Finish Tutorial building for Geo-spatio-temporal education and research
We are developing a framework for research software development that applies to a range of examples usable in the classroom. 

### Common Workflow Tools

_Github_  - describe why, how

_HydroShare_  This JupyterHub is one way to launch

_Landlab_

_JupyterNotebooks_

_UserExperience_

_Formal Publication_

_Distribution Channel Strategies_

_Component based software design_

_Contribute to an Open Source Project_

## 2. Modules
Each modules uses common workflow tools that we share developing, using and teaching each other.  Each module uses existing open source code and explores advancing this code with at least one new component. 

### Steven's Module
This project is a modification of a Landlab tutorial illustrating use of Python and Jupyter for landslide hazard estimation.  It uses factors feeding into the infinite slope factor of safety equation, which predicts the ratio of stabilizing to destabilizing forces on a hillslope plane. The properties are assumed to represent an infinte plane, neglecting the boundary conditions around the landslide location.  The Jupyter notebook, which is hosted and runs on Hydroshare, is a Monte Carlo simulation for the Fisher Creek watershed in the North Cascades; the exercise is adapted from work by Stauch et al. (https://www.hydroshare.org/resource/a5b52c0e1493401a815f4e77b09d352b/).

The goal is/was to explore possible teaching resources for graduate level students in the Department of Earth and Space Sciences, many of whom conduct research on landslide hazards in western Washington.  The open source geospatial analysis and modeling tools afforded through Python (and ease of their teaching and use through Jupyter notebooks) is extremely valuable.

**Link to the tutorial github repository:** https://github.com/swalt826/Landlab---Landslide-Hazards 


###  Rose's Module

This tutorial is an introduction on how to use spectrogram cross-correlation to detect blue whale calls. This tutorial is meant primarily for individuals with at least an introductory understanding of Python to familiarize themselves with the one of the processes used in acoustic signal detection. 

**Workflow tools in the tutorial:**

-Python: Numpy, Scipy, and Matplotlib libraries

-Jupyter notebook

-Github

**Key tutorial outcomes:**

-Experimentation with key scientific python libraries

-Introduction to timeseries analysis

-Familiarization with spectrograms

-Understand basic reasoning behind signal detection

**Link to the tutorial github repository:** https://github.com/rosehilmo/whale-detection 


### Helen Xarray Module

Tutorial link:https://github.com/hydrogeohc/Xarray

Extra file in and out function by using Xarray.

Load time series Geotiff raster files

Create Xarray data structure 

Save it as netCDF files format

Export the point of interest for this netCDF file

### Christina's Modules

[Background on the model grid data model used in Landlab](https://nbviewer.jupyter.org/github/landlab/tutorials/blob/master/grid_object_demo/grid_object_demo.ipynb)

[Teach yourself Landlab](https://github.com/landlab/landlab/wiki/Teach-Yourself-Landlab!)

Test the Modules from this HydroShare Resource (requires HydroShare UserID to use the cloud compute resources to run interactive models from CUAHSI JupyterHub). 
[Lowering the barriers to Computational Modeling of the Earth Surface](https://www.hydroshare.org/resource/70b977e22af544f8a7e5a803935c329c/)

Sign in/Sign up at www.hydroshare.org. Go to Collaborate. Search for the Landlab Group. Join. Go to Resources. 

Click on the resource above. Use blue upper right button to 'OPEN WITH'. Select JupyterHub. 

Execute Welcome to connect to HydroShare. Click on Jupyter Notebook of interest.  


