
#### Dataset Link: https://www.kaggle.com/datasets/alikalwar/uae-used-car-prices-and-features-10k-listings

### About Dataset
---
#### Dataset Overview
This dataset contains 10,000+ used car listings from the UAE market with detailed features, pricing, and conditions. Whether you're analyzing market trends, building price prediction models, or training AI models for car valuation, this dataset is designed to provide real-world insights.

#### Key Features
✔ 10,000+ used car records from the UAE 🇦🇪
✔ Includes Make, Model, Year, Mileage, Price, Body Type, Transmission, Fuel Type, and Color
✔ Realistic price variations based on UAE market conditions
✔ Includes damage reports and custom descriptions
✔ Ideal for Machine Learning, Data Analysis, and AI-powered price prediction

#### Potential Use Cases
🔹 Car Price Prediction using Machine Learning
🔹 Car Market Trends Analysis in the UAE

🔹 AI-powered Auction Pricing Models
🔹 Car Resale Value Estimation

#### Dataset Features

Dataset contains 11 Features

| Feature      | Description                                                   | Data Type |
|--------------|---------------------------------------------------------------|-----------|
| Make         | Brand of the car (e.g., Toyota, Nissan)                       | string    |
| Model        | Specific model of the car (e.g., Camry, Altima)               | string    |
| Year         | Manufacturing year of the car                                 | integer   |
| Price        | Selling price of the car in AED (United Arab Emirates Dirham) | integer   |
| Mileage      | Distance the car has traveled (in kilometers)                 | integer   |
| Body Type    | Car type classification (e.g., Sedan, SUV)                    | string    |
| Cylinders    | Number of engine cylinders                                    | string    |
| Transmission | Type of transmission (Automatic/Manual)                       | string    |
| Fuel Type    | Type of fuel used (e.g., Gasoline, Diesel, Hybrid)            | string    |
| Color        | Exterior color of the car                                     | string    |
| Location     | City where the car is available (e.g., Dubai, Abu Dhabi)      | string    |
| Description  | Additional details about the car (features, condition)        | string    |

### dataset pre processing steps
---
#### 1. handle missing values (ex-:Cylinders)
#### 2. remove duplicates
#### 3. handle outliers (ex-:Price)
#### 4. Feature Engineering
#### 5. encode categorical variables
#### 6. normalize numerical features
#### 7. remove irrelevant columns

### Data Analysis
---
- ##### Summary statistics for numerical features
- ##### Distribution of categorical features
- ##### Price distribution using histogram and box plot
- ##### Log transformed price distribution using histogram
- ##### Manufature year distribution using histogram
- ##### Mileage distribution using histogram and box plot
- ##### Mileage per year distribution using histogram and box plot
- ##### Cylinders distribution using bar chart
- ##### Summary statistics for categorical features
- ##### Body , vehical make, model analysis using bar chart
- ##### Transimission analysis using pie chart
- ##### Fuel Type, Color analysis using bar chart
- ##### Mileage vs Price analysis using scatterplot
- ##### Manufactured year vs Price anaysis using scatterplot
- ##### Average Price per Age with standard deviation
- ##### Price distribution by body type using box plots
- ##### Price distibution by top 10 Make using box plots
- ##### Price distribution by Transmission using box plots
- ##### Price distribution by Fuel Type using box plots
- ##### Price distibution by top 10 Colors using box plots
- ##### Correlation between numerical features
- ##### K-means clustering to identify clusters based on Mileage, Car Age and No of Cylinders compare to Price

### Selling Price Prediction using Regression
---
- ##### Train linear regresssion using standardized and encoded features as predictors
- ##### Evaluate regresssion model using r squared score, MAE, MSE and RMSE
- ##### Compare actual prices and predicted prices

### Project Setup
---

#### Prerequisites

Ensure you have the following installed on your system:

- Python (>= 3.8)

- Git
- pip (optional)
- Kaggle API credentials (for dataset access)

#### Cloning the Repository

```
git clone https://github.com/DinithKumudikaIS4116---Business-Intelligence-Systems---Assingnment-2.git

cd IS4116---Business-Intelligence-Systems---Assingnment-2
```

#### Setting Up Kaggle Hub Credentials

1. Log in to Kaggle and navigate to Account settings.
2. Scroll down to the API section and click Create New API Token.
3. This will download a kaggle.json file containing your API credentials.
4. Move this file to the appropriate directory
5. create .env file following .env.example add username and key