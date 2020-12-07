# Kings Count Housing Price Prediction

Flatiron School Phase 2 Project Submission
Submitted by Steven Yan

<img src="images/cover_photo.jpg">

<span>Photo by <a href="https://unsplash.com/@tierramallorca?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText">Tierra Mallorca</a> on <a href="https://unsplash.com/s/photos/real-estate?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText">Unsplash</a></span>

# Background

The following notebook presents the steps involved in and the thought process we used in predicting house prices based on multiple features using regression analysis. We were presented with a dataset preprocessed for instructional purposes and derived from the dataset provided in the former Kaggle competition to predict housing sale price using regression.

If you would like to explore the original competition on Kaggle, please follow the link below:
https://www.kaggle.com/harlfoxem/housesalesprediction/discussion/92376

Names and descriptions of the columns in the provided King County dataset:
* **id** - unique ID for a house
* **date** - Date day house was sold
* **price** - Price is prediction target
* **bedrooms** - Number of bedrooms
* **bathrooms** - Number of bathrooms
* **sqft_living** - square footage of the home
* **sqft_lot** - square footage of the lot
* **floors** - Total floors (levels) in house
* **waterfront** - Whether house has a view to a waterfront
* **view** - Number of times house has been viewed
* **condition** - How good the condition is (overall)
* **grade** - overall grade given to the housing unit, based on King County grading system
* **sqft_above** - square footage of house (apart from basement)
* **sqft_basement** - square footage of the basement
* **yr_built** - Year when house was built
* **yr_renovated** - Year when house was renovated
* **zipcode** - zip code in which house is located
* **lat** - Latitude coordinate
* **long** - Longitude coordinate
* **sqft_living15** - The square footage of interior housing living space for the nearest 15 neighbors
* **sqft_lot15** - The square footage of the land lots of the nearest 15 neighbors

# Business Problem

Our client representing a cohort of foreign investors has expressed interest in becoming involved in the Seattle area housing market. By gaining better insight into the prediction models for housing prices, they hope to become major players in the market. They have partnered with us to learn how applying supervised machine learning analysis to predict housing prices in the King County.

We set out to answer a few questions for our client:

1. Do renovated properties have a higher selling price than unrenovated properties?
2. Does the number of times a property is viewed have any effect on selling price?
3. Does the grade given to the housing unit have an overall effect on the selling price?

Through the use of statistical tests during our EDA process, we will be able to provide the essential information needed for our clients in their new business venture.


# Directory and File Structure

- README.md - brief overview of project
- final.ipynb - location of final project report
- /data - folder of data files
--- housing_preds_Steven_Yan.csv - CSV of housing predictions
--- kc_house_data_test_features.csv - CSV of project testing dataset 
--- kc_house_data_train.csv - CSV of project holdout set
--- model.pickle - pickle file 
--- scaler.pickle - pickle file
- /images - folder of data visualization files
--- df_boxplot.png - box plots of categorical variables
--- df_corr.jpg - correlation matrix of variables
--- df_countplot.png - bar plots of categorical variables
--- df_distplot.jpg - distribution plots of continuous variables
--- df_regplot.png - regression plots of categorical variables 
--- df_scatter.png - scatterplots of categorical variables
--- df_target_2.png - boxplot of target variable
