# Perth-House-Price-Prediction

## House Price Prediction in Perth, Australia

This repository contains a project that focuses on predicting house prices in Perth, Australia. The project involves exploratory data analysis (EDA), data cleaning, preprocessing, and the implementation of two different regression models: Linear Regression and Random Forest Regression. The goal is to provide accurate predictions of house prices based on various features associated with the properties.

### Dataset

[Perth House Prices](https://www.kaggle.com/datasets/syuzai/perth-house-prices)
The dataset used in this project contains historical data on house prices in Perth, Australia. It includes a range of features such as the number of bedrooms, bathrooms, square footage, location, and other relevant characteristics of the properties. The dataset has been preprocessed to ensure data quality and consistency.
- ADDRESS: Physical address of the property (will be set as the index)
- SUBURB: Specific locality in Perth
- PRICE: Price at which a property was sold (AUD)
- BEDROOMS: Number of bedrooms
- BATHROOMS: Number of bathrooms
- GARAGE: Number of garage places
- LAND_AREA: Total land area (m^2)
- FLOOR_AREA: Internal floor area (m^2)
- BUILD_YEAR: Year in which the property was built
- CBD_DIST: Distance from the centre of Perth (m)
- NEAREST_STN: The nearest public transport station from the property
- NEAREST_STN_DIST: The nearest station distance (m)
- DATE_SOLD: Month & year in which the property was sold
- POSTCODE: Local Area Identifier
- LATITUDE: Geographic Location (latitude) of ADDRESS
- LONGITUDE: Geographic Location (longitude) of ADDRESS
- NEAREST_SCH: Location of the nearest School
- NEAREST_SCH_DIST: Distance to the nearest school
- NEAREST_SCH_RANK: Ranking of the nearest school


### Project Structure

The project follows a structured approach, with the following main components:

1. **Exploratory Data Analysis (EDA)**: This initial step involves exploring and visualizing the dataset to gain insights into the distribution, relationships, and patterns of the variables. The EDA phase helps in identifying any missing values, outliers, or data quality issues that need to be addressed during the data cleaning process.

2. **Data Cleaning and Preprocessing**: In this phase, the dataset is cleaned and preprocessed to ensure its suitability for building the regression models. This involves handling missing values, creating new features. The data is transformed and prepared for training and testing the models.

3. **Linear Regression Model**: A linear regression model is implemented to predict house prices based on the selected features. The model is trained using the preprocessed dataset, and the performance is evaluated using root mean squared error (RMSE) and R-2 Score.

4. **Random Forest Regression Model**: A random forest regression model is implemented as an alternative approach for predicting house prices. This ensemble model utilizes multiple decision trees to make accurate predictions. Similar to the linear regression model, the performance is assessed using suitable evaluation metrics.

5. **Results and Conclusion**: The predictions obtained from both models are compared and analyzed. The Random Forest Model performed better than Linear Regression model.
