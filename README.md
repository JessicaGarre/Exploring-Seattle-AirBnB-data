# Exploring-Seattle-AirBnB-data

### Motivation:
The objective of this project is to go through, analyze and study Seattle AirBnB dataset, as part of the Udacity Data Scientist Nanodegree program. In order to do that, and after a brief analysis, I found three questions worth to respond which would cover some interesting aspects. The article Ipublished on Medium covers these questions in a non-technical sense and summarizes the main points, while the code provided in this file contains all calculus and technical procedures. 

### Files:
**Seattle_AirBnB_Data.ipynb**
This is the file (Jupyter Notebook) where the technical part of the project is covered. It was divided by the files on the dataset: *Calendar*, *Reviews* and *Listings*, following the same producedure in each of them. First, I took a brief look at the data and retrieved some general information, and then a deeper analysis was carried out. It is worth mentioning that there was no need to process missing values since they were due to absence of people responses in comments, reviews, descriptions, etc., which is very normal in this kind of data. To process categorical variables that needed a deeper treatment, a function was created that converted those to numeric values so that they can be included in the studies and calculus.

The questions aforementioned were responded according to the sections needed to do it. 

### Libraries:
pandas, numpy and matplotlib

### Setup required:
You need to download all required files (listings.csv, reviews.csv, calendar.csv) in the same folder where you created your Notebook, and have all libraries required installed. 

### Results:
Through the project I looked mainly at three different points, one covered by the calendar dataset while the remaining two by the listings dataset. From them I obtained that December is the most expensive month to rent a spare room/house in Seattle, probably associated to the Christmas holidays, while January and February are the cheapest ones, again, probably due to the fact that are the dates just after Christmas. I also concluded that people can take an idea of the neighborhood vibes looking at the listings description, since there is information about the area the apartment is located into, but it is better to look at other variables too, like the transit and the neighborhood overviews, in order to get proper information. Finally, it was concluded that it is more benefitial from an economical point of view to do the renting by weeks or months instead of daily since you usually get considerable discounts. 

### Author:
Jessica Garre Morales

### Resources:
It is fundamental to mention that I used other resources to get ideas on how to proceed with the analysis and to get some inspiration, mainly: 
* Josh Bernhard's blog on comparing AirBnB homes in Seattle and Boston
* Pandas and matplotlib documentation 
* Stack Overflow and other forums 
