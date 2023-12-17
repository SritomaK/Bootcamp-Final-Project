# Zomato Success Prediction
## Overview
The primary objective of this project was to unravel the factors driving the success of restaurants in the city of Bangalore, India using data from Zomato. My endeavour focused on two main goals: firstly, to identify the crucial elements influencing a restaurant's popularity and customer satisfaction on Zomato; and secondly, to develop a predictive model capable of estimating the potential success of new restaurants on the platform. This exploration aimed to provide valuable insights for restaurant owners and Zomato, facilitating informed decision-making and strategic planning in the competitive culinary landscape of Bangalore.
## Data Source
The dataset was sourced from -
https://www.kaggle.com/datasets/absin7/zomato-bangalore-dataset/data
## Project Components
- Data Collection: Restaurant data from Zomato was obtained, focusing on key attributes like ratings, location, cuisine, and price range.

- Data Preprocessing: The dataset underwent cleaning, normalization, and transformation to prepare it for analysis.

- Exploratory Data Analysis (EDA): Conducted thorough EDA to understand the distribution of data and identify patterns.

- Feature Engineering: Created new features that could potentially influence a restaurant's success.

- Model Building: Several predictive models were built and evaluated to forecast the success of a restaurant.

- Evaluation: The models were assessed using metrics like accuracy, precision, recall, and F1-score.

- Model Validation with New Restaurant Data: To ensure the robustness and practical applicability of our models, they were validated using a separate dataset of newly established restaurants. This step was crucial to test the model's predictive power in real-world scenarios and to refine it for better accuracy in forecasting the success of new entries in the market.
## Technologies Used
- Python
- Pandas, NumPy (Data Manipulation)
- Matplotlib, Seaborn (Data Visualization)
- Scikit-learn (Model Building and Evaluation)
- Jupyter Notebook (Development Environment)
## Results
The project's investigation into the Zomato dataset yielded insightful outcomes, particularly regarding the predictors of restaurant success. Key findings are summarized as follows:

Highly Predictive Factors: The model identified cost for two, cuisine type, and services like online order and table booking as the most influential factors in determining a restaurant's success on Zomato. These elements showed a significant correlation with customer popularity and satisfaction.

Model Performance: The predictive model Random Forest, leveraging these key determinants, exhibited fairly strong accuracy in estimating a restaurant's potential success. Their performance was particularly notable in scenarios involving the introduction of new restaurants on the platform.

