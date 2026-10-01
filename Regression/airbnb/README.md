# AirBnB Regression Analysis

A regression problem for predicting the price of AirBnB listings based on features such as location (longitude/latitude), availability, number of reviews, etc.

## Project Structure
```text
airbnb/
├── data/
│   └── airbnb_data.csv          # Raw dataset
├── Airbnb_analysis.ipynb        # Complete analysis
└── README.md
```

## Data Structure

The AirBnB data, contained in ```airbnb_data.csv``` possesses the following features:
|column| details|
|-|-|
|id| Unique id for each row|
|name| Listing name|
|host_id| Unique host id|
|host_name| Host name|
|neighbourhood_group| Neighbourhood group name (e.g. Brooklyn, Queens, etc.)|
|neighbourhood| Specific neighbourhood|
|latitude| Location latitude|
|longitude| Location longitude|
|room_type| Type of room available (e.g. Private room, entire home, etc.)|
|price| Daily room price|
|minimum_nights| Minimum number of nights for stay|
|number_of_reviews| Number of reviews for listing|
|reviews_per_month| Number of reviews per month|
|calculated_host_listing_count| Number of listings for given host|
|availability_365| Number of days per year listing is available|


## Data Processing & Analysis

A number of columns were found to have heavily skewed data, these include:
- minimum_nights
- number_of_reviews
- reviews_per_month
- calculated_host_listings_count

Significantly, the price target variable was heavily skewed, which played into the resulting analysis.

The baseline model was chosen to be simple Linear Regression, which resulted in a fit with an R2 score of ```0.132 ± 0.021```. In an effort to improve this result, we tested:
- Including polynomial features (up to 4th order)
- Transforming skewed variables (log, sqrt, cbrt, robust)
- Regularization (Ridge and Lasso)

**None** of the above tweaks were found to improve the result significantly. Therefore, we moved on to a set of alternative models:
- Decision Tree Regressor
- Random Forest Regressor
- K-Nearest Neighbors
- Support Vector Machine Regression

From this, it was found that the Random Forest model 

The best model after tuning was found to be the **Random Forest** model, which achieved a final performance on the test set data of:
- Accuracy: 0.860
- Precision: 0.806
- Recall: 0.841
- F1: 0.823
- AUC 0.899

Best GridSearchCv parameters: {'max_depth': 10, 'min_samples_leaf': 2, 'min_samples_split': 7, 'n_estimators': 40}


## Key Findings
1. **Random Forest was the best performing model** with a tuned accuracy of 0.86 and F1 score of 0.82
2. **Sex** was by far the most important feature for predicting survival (~74% female survival, ~19% male survival)
3. **Overall survival rate** was only ~38%
4. **Lower fare reduced survival rate**, those with the lowest fare had a significantly lower chance of survival
5. **Larger family size improved survival rate**
6. **Passenger class** significantly impacted survival rate, with upper class having a survival percentage of ~63%, and lower class of ~24%


## How To Run This Project
1. Clone repository into relevant project folder
2. Ensure jupyter notebook is installed, along with all relevant libraries (contained at the top of the jupyter notebook files)
3. Run ```Airbnb_analysis.ipynb``` notebook
