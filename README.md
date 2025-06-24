# Pricing-WebScraper


This repository contains a web scraper to price images from Fashion Products (small) dataset from Kaggle

Here is the link:

https://www.kaggle.com/datasets/paramaggarwal/fashion-product-images-small

To set up, download the dataset and put in to a folder called images (if you like to make your own directory you'll have to change the script)

In the script you'll need to input the path to the dataset

This script was performed on Microsoft Edge and will start out waiting for a captcha message, I gave about 20 seconds to complete this. 

You will also need to define the path to Edge in the script

If you're looking to fully automate the task look into Oxylabs or SerpiApi which allows you to mine data without receiving the captcha message.

This is the intial data processing part to my Image Classification Model.

After training the model and using opencv I am able to predict Brand Name, Article Type, and Pricing when showing an item of clothing to the camera. 

I tested this with scraping for the first 500 images out of the 440000. To do the full set you'll need to change or remove the image counter in the web scraper. 
