
Goal: Predict Trend of Indianapolis housing prices by zip code using Zillow data pulled from Quandl.

Process: Monthly housing statistics pulled from the data source were cleaned and formatted by various statistics, such as number of bedrooms and square feet, and were used to train a neural network to predict housing prices through 2020. Gaps in data were filled using linear regression tools from SKLearn's library for the purpose of providing the neural network a full dataset to train on. For the purpose of the demonstration, data from 4 zip codes were used and data from 2010 through 2019 was used to train the neural net. The resulting 2020 data as well as source data was plotted using tableau and embedded our accompanying website. Finally, the prediction data was plugged into a prediction model in which a user inputs the month they are buying, the number of bedrooms, and the intended zipcode, which would then return predicted average prices for that month.

Results: The resulting 2020 predictions were continuous and lined up well with where the training data had ended, however given the lack of granularity of the source data (monthly as opposed to individual listings) and an apparently lack of the expected seasonal fluctuations, it seems as though a simple linear regression model may have served as both a simpler and perhaps even more accurate predictor for this specific dataset. That said, the resulting data seemed to result in good predictions (which will unfortunately be difficult to confirm given current events), and if more granular data were to be found it could be implemented relatively easily and could result a very clean model that could be implemented accross larger areas with more tweaking and similarly granular data from different areas.
