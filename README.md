# Web-based-Crop-Guidance

The website developed by us has the following features:
  * A portal for the farmers to login/signup.
  * Predicts the soil contents based on the farmer's location.
  * Suggests crops to the farmers, based on the predicted soil contents and crop season.
  * Suggests pesticides to the farmer based on the crop choosen.
  * Sending weather updates to the farmer through SMS.
  * A modest page for farmers to keep track of their loans.
  * Scrapping tweets from agriculture related twitter accounts and displaying it in the webpage to ensure the farmer stays up to date with agriculture related news.

The webpage was primarily built using Flask and sqlite database is used to store the details of farmers as well as the list of pesticides.
'Website.py' consists of the code to run the website in localhost. The other python files uploaded serves to run the individual features of the website in a stand-alone manner. The datasets used ('soil.csv', 'monsoon.csv') are also uploaded.

This project is a modest/humble attempt of my friends and I to explore various (new) domains.

 
