# Methodology Assignment 5, Task 2
**Name:** Kenneth Hidayat
**Email:** khidayat@ucsd.edu

**1. What is the most interesting topic covered in your domain this quarter?**
The most interting topic covered is working with geospatial data involving different geospatial formats including lines points, multi-polygons in which I was able to plot conductor spans, weather station locations and vegetations areas within San Diego. Moreover, it is interesting because I get to work with Big Data involving more than 700,000 rows of data which involves heavy computations with GPUs.

**2. Describe a potential investigation you would like to pursue for your Quarter 2 Project.**
A possible investigation that I would possibly persue is to investigate whether there are alternative methods to determine risks of wildfires to a particular grid area other than PSPS probabilities. This would involve further data exploration to discover deep correlations between weather data and grid data. However, this investigation is bound to change depending on our findings for the Quarter 1 Project.


**3. What is a potential change you’d make to the approach taken in your current Quarter 1 Project?**
So far we are working on utilzing raw geospatial data and weather data to determine PSPS probabilties of grids while considering probabilistic dependence between conductor spans(electrical grids) to manually calculate the risk. However, I would me more interesting in using supervised learning models to determine the risk through historic data rather than calculating the probabilities manually.


**4. What other techniques would you be interested in using in your project?**
I would be interested in SVD models using various weather stations data features to predict the risk of wildifres instead of comptuting the dependency of PSPS probabilities among weather stations and the conductor spans. In other words, we are both still trying to assess wildfire risk through a wildfire score riskscore but instead of computing the probabilities manually we use an SVD model to predict the probability risk for us.

This is about as **barebones** as a Jekyll site can be. All I've done is embed a plotly plot here.

<iframe src="assets/example-map.html" width=800 height=600 frameBorder=0></iframe>
