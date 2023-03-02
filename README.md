# DIAMOND PRICE PREDICTION
Diamond Price Prediction is an application to predict the price of diamond by their properties.

# Features
- Carat : Carat weight of the Diamond.
- Cut : Describe cut quality of the diamond. Quality in increasing order Fair, Good, Very Good, Premium, Ideal .
- Color : Color of the Diamond. from J (worst) to D (best)
- Clarity : Diamond Clarity refers to the absence of the Inclusions and Blemishes. In order from worst to best :- I1,SI2, SI1, VS2, VS1, VVS2, VVS1, IF
- Depth : The Height of a Diamond, measured from the Culet to the table, divided by its average Girdle Diameter.
- Table : The Width of the Diamond's Table expressed as a Percentage of its Average Diameter.
- Price : the Price of the Diamond.

# DATA CATEGORY'S
- Qualitative Features (Categorical) : Cut, Color, Clarity.
- Quantitative Features (Numerical) : Carat, Depth , Table , Price.


# Tools used
- python 3.8
- anaconda - jupyter notebook
- backend api: flask
- frontend : HTML,CSS & JAVASCRIPT
- webscraping - beautifulsoap(bs4)

# MODEL USED
Random Forest Regressor

# Accuracy
The accuaracy of model is 96.74

# Input
Fill the Information about diamond required by model in web app's UI

# Output
The model will predict the price of diamond in dollars($) , it is converted into INR using webscraped dollar value and dispayed in output page
