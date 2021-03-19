

# Air-BnB-project
This project was done in a Jupyter notebook using Python. The libraries used in this project are numpy, seaborn, matplotlib, sci-kit learn, and pandas. The motivation for this project is to get practice and experience working with real world data where the following business questions are answered:

1. What features of an Air BnB listing determine the market value price of a nightly rental?
2. What data is missing from the data set?
3. How accurately can the price be predicted once a linear model is developed?

This project is an assignment for the Data Science Nanodegree program through Udacity. The file used for this project is a .csv file called 'listings_data'. It includes over thirty columns of data for each listing and 3818 rows of data or listings for Air BnB rentals in Seattle, Wa. Another .csv data set was briefly looked at called 'calendar_data' but it was not used because it only gave information about the availability of the listings based on the dates.

The findings of this project were that there were the main numerical features that determined the price were  the number of people the listing accommodates, the number of bathrooms it has, the number of bedrooms, number of beds, the cleaning fee they must pay, and if they are allowed guests. This was done by looking at heat map visualizations that show the correlations. Additionally there were categorical variables that were converted to to dummy variables. These features included how responsive the host is (host_response_time), the neighborhood, the property type, and the cancellation policy. How strongly these categorically features did correlate to the price of listing was not explored specifically in this project. As for the second question, "What data is missing", it was found that there were many missing values for the cleaning fee. These values were handled by imputing the average value for a similar accommodation. There were also some missing values for the property type, and number of bathrooms and number of bedrooms. Again they were imputed with the most likely number for a similar listing. No rows of data were deleted. The final question answered on the model accuracy was that the r2 value on the test data was about 0.58. This is decent for linear model. Decent is considered to be above 0.50. Perhaps the model could be improved using a more advanced machine learning models such as neural network.

The project also included a blog post designed for non-technical readers that can found at: https://bryanchambers-25994.medium.com/what-makes-an-air-bnb-listing-profitable-4917224801dc


Acknowledgements: The data set was provided by Kaggle, guidance for this project was provided by Udacity through the Data Science Nanodegree program.
