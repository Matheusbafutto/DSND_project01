# Udacity data Scientist Nanodegree - Project 01

This repository contains the notebook and its outputs from my exploration of [Airbnb's Seattle dataset](https://www.kaggle.com/datasets/airbnb/seattle) (kindly shared by Udacity and Airbnb).

 ## Motivation

I use Airbnb as a guest very often and sometimes I wonder if I would want to become a host myself one day. With that in mind, my exploration focused on things like what influences perceived quality of a listing, also how quality correlates to price and vancancy (and ultimately income of the host).

## File structure

|–– visualizations - folder with output images from the analysis

|–– Capstone project 01.ipynb - jupyter file where the analysis was made

## Stack

- [Jupyter notebooks](https://jupyter.org/)
- [python library matplotlib](https://matplotlib.org/)
- [python library seaborn](https://seaborn.pydata.org/)
- [python library pandas](https://pandas.pydata.org/)
- [python library numpy](https://numpy.org/)

## Summary of results

Quality was found to have stronger lineasr correlations with the type of property and quality of the bed. Elements associated with host commitment (response time and cancelation policy) also correlated strongly with our metric for quality.

Increasing quality hinted at higher listing price on average. We also found that higher quality listings tended to have lower vacancies over the year on average. All listings correborated with these conclusions except the ones on the 85 to 95 range. More investigatioon is needed to understand the reasons of this anomaly.

Here are some of the visualizations produced in this analysis:

![average price by rating bin](./visualizations/avgprice_by_ratingbin.png)

![vacancy_by_rating_bin](./visualizations/vacancy_by_ratingbin.png)


