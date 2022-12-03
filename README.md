# Programming for Data Analysis Project

### Introduction
The point of this project is to analyse and simulate real-world data using Python, its package Numpy.random and Jupyter Notebooks.

### Description
-	Choose a Dataset based on a real-world phenomenon.
-	Using Python and Jupyter Notebooks model and clean the Dataset
-	Analyse the variables on this dataset and their distributions.
-	Based on this analysis, simulate, and synthesize a new dataset matching its proprieties.
-	Present the new dataset on a output cell and detail your research

## Setup/Installation Requirements

To run this project locally you are going to need Python(and its packages: Numpy, Pandas, Seaborn, Scipy and MatplotLib) and Jupyter Notebook as well. You can gey both of Python and Jupyter by downloading [Anaconda]( https://www.anaconda.com/products/distribution).
You may need to install/update some of the Python's packages.

You can use the code below to install/update your packages:
```
pip install numpy
```
```
pip install pandas
```
```
pip install seaborn
```
```
pip install scipy
```
```
pip install matplotlib
```

## What to expect

A simulated dataset based on real world data. The dataset used as basis was The dataset used was the [Finger Print Dataset](https://repository.lboro.ac.uk/articles/dataset/Height_weight_and_fingerprint_measurements_collected_from_200_participants/7539206) from the University of Loughtborough, authored by **Beth McMurchie**, **George TorrensGeorge Torrens** and **Paul Kelly**. This dataset was used as its authors states that the height and weights from the participants were measured, and it was real world data. 

Cleaning of the dataset leaving only the relevant data for this project. Which is the height and weight of the participants.

Calculation of the BMI for each participant using the information their height and weight.

Showcase of the correlation between the BMI and height and weight and distribution of those variables for males and females participants.

A new dataset created using Python’s Numpy random and the real-world data as basis, creation of plots to show the distribution of the new dataset for male and females.

Comparison between the real-world dataset and the simulated one.

## References

- https://docs.scipy.org/doc/scipy/reference/generated/scipy.stats.skewnorm.html
- https://numpy.org/doc/stable/reference/random/generated/numpy.random.Generator.normal.html
- https://www.math.arizona.edu/~rsims/ma464/standardnormaltable.pdf
- https://www.statisticshowto.com/probability-and-statistics/z-score/
- https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.concat.html
- https://www.cdc.gov/obesity/basics/adult-defining.html
- http://www.math.iup.edu/~clamb/class/math217/3_1-normal-distribution/
- https://plus.maths.org/content/normal-distribution
- https://en.wikipedia.org/wiki/Normal_distribution#cite_note-49
