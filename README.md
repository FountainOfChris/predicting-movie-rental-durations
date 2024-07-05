# Predicting Movie Rental Durations

Build a regression model to predict DVD rental durations and recommend the best-performing model to a DVD rental company.

## Project Description

Time to put your regression knowledge to the test! A DVD rental company has approached you to make a regression model which will help predict the number of days a customer rents a DVD. The model will hopefully make their inventory planning much more efficient. You decide to help them by running some regression models and recommending the best-performing model to the company.

The data they provided is in the csv file `rental_info.csv`. It has the following features:

- `rental_date`: The date (and time) the customer rents the DVD.
- `return_date`: The date (and time) the customer returns the DVD.
- `amount`: The amount paid by the customer for renting the DVD.
- `amount_2`: The square of `amount`.
- `rental_rate`: The rate at which the DVD is rented for.
- `rental_rate_2`: The square of `rental_rate`.
- `release_year`: The year the movie being rented was released.
- `length`: Length of the movie being rented, in minutes.
- `length_2`: The square of `length`.
- `replacement_cost`: The amount it will cost the company to replace the DVD.
- `special_features`: Any special features, for example, trailers/deleted scenes that the DVD also has.
- `NC-17`, `PG`, `PG-13`, `R`: These columns are dummy variables of the rating of the movie. It takes the value 1 if the movie is rated as the column name and 0 otherwise. For your convenience, the reference dummy has already been dropped.

The objective is to build a regression model that predicts the rental duration (number of days) with a mean squared error (MSE) of 3 or less on the test set.

## Getting Started

### Prerequisites

- Python 3.x
- Jupyter Notebook
- Libraries: pandas, numpy, scikit-learn, matplotlib, seaborn
