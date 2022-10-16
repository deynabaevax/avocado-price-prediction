<img width="700px" src="https://blogs.sap.com/wp-content/uploads/2020/03/avocado-prices-prediction.jpg">

# Introduction
It is not a surprise that avocados have great taste, versatility and are loaded with health benefits. They are a great source of healthy monounsaturated fats, potassium, fiber and an abundance of nutrients that are essential for the persons' optimal health. How could you not love them, right?
As an avocado lover, I decided to make it my topic for the semester 4 in Artificial Intelligence at Fontys University of Applied Sciences.

# The Data
This data has been taken from Kaggle's website and contains records from 4 January 2015 up to 17 May 2020.
Link to the dataset <a href="https://www.kaggle.com/timmate/avocado-prices-2020">https://www.kaggle.com/timmate/avocado-prices-2020</a>.
The dataset comprises of 33045 observations of 13 columns. Below is a table showing names of all the columns and their description.

- The regions, which have been included in this observations are in the USA.
- The price is mesured in US Dollars.
- The quantity of the bags in measured in counting the bags.
- 4046, 4225, 4770 stands for the PLU code (Price look-up code)
- Small/Medium Hass Avocado (~3-5oz avocado) | #4046
- Large Hass Avocado (~8-10oz avocado) | #4225
- Extra Large Hass Avocado (~10-15oz avocado) | #4770

# The Model
The model, which I used for this challenge was ARIMA/SARIMAX time series forecasting. Below, you can observe the prediction from the model.
<br>

![download (1)](https://user-images.githubusercontent.com/64732465/196043382-15025e99-be32-473f-9864-e4b8ba0b6696.png)
