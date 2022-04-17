# School_District_Analysis
Pandas Practice

Using Pandas and Jupyter Notebook to edit read, edit, format, and explore data.

## Overview of Project

The idea of this project was to first build a dataframe that was inclusive of all the data regarding reading and math scores across multiple districts. Once we were told there was bad data, we then had to use Pandas and Numpy within Jupyter Notebook in order to cut the data down to what we wanted to look at. From there we cut the data in a handful of ways in order to best support the board in this exercise.

### Purpose

The purpose of this project was to get some hands on practice within Pandas. Without having to open up a CSV file and write code, we can simply use some Pandas commands within Jupyter notebook in order to quickly quantify all of our data. We can also get an idea of if there is any missing data or not, which can obviously skew an analysis depending on how these datapoints are treated.

## Analysis and Challenges

The findings of my analysis can be found [here](https://github.com/jtspingler/School_District_Analysis), as well as presented below:

#### How is the district summary affected?

The district summary is affected by a decreased in both the overall percentage as well as the math percentage.
![This is an image](https://github.com/jtspingler/School_District_Analysis/blob/main/Resources/dist%20summ%201.PNG) 

#### How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
* Average math scores dropped by less than 1%
* Average reading scores were unaffected
* Overall passing rate dropped -1%

### How does replacing the ninth-grade scores affect the following:
#### Math and reading scores by grade
* Math and reading scores did not change for any of the other schools
#### Scores by school spending
* Scores by school spending changed in the $600-$650 range
   * % math passing (-6%)
   * % reading passing (-7%)
   * % Overall passing (-7%)
#### Scores by school size
* Medium-sized Schools
   * % math passing (-9%)
   * % reading passing (-6%)
   * % Overall passing (-6%)
#### Scores by school type
* Charter schools performed better than District schools
   * % math passing (-4%)
   * % reading passing (-4%)
   * % Overall passing (-3%)

![This is an image](https://github.com/jtspingler/School_District_Analysis/blob/main/Resources/df1.PNG) 

![This is an image](https://github.com/jtspingler/School_District_Analysis/blob/main/Resources/summary%20df.PNG) 

![This is an image](https://github.com/jtspingler/School_District_Analysis/blob/main/Resources/loc%20example.PNG)
