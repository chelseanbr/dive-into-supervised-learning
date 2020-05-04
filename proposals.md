# Project Idea #1: 
### Topic (Title): 
  Between the Lines of Amazon Product Reviews
### High Level Description: 
  I will build models to predict the product categories and ratings/sentiment of Amazon reviews.
### My Approach: 
  I plan to use natural language processing and algorithms like Naive Bayes to make product category and rating predictions on Amazon review data from 2018. The data is separated into separate json files by product category, so I can label the product categories before joining the data to build a product category classification model. The data also includes star ratings, which I can use as the target to build a classification model for predicting star ratings (1-2 stars = negative, 3 stars = neutral, 4-5 stars = positive) based on sentiment analysis.
### How people will interact with my work:
  I would like people to be able to interact with my work through a flask dashboard. I want them to be able to try uploading their own product review text to try out my finished product category classifier and rating predictor. In the future, I would like to try to build a product recommender system based on my learnings.
### Data Source(s): 
  I will use a smaller dataset (https://nijianmo.github.io/amazon/index.html).
Only if there is time after I have finished my pipeline & modeling, I will try to incorporate the full dataset: http://deepyeti.ucsd.edu/jianmo/amazon/index.html

___

# Project Idea #2: 
#### Topic (Title): 
  Finding Hot Hotels
#### High Level Description: 
  I will build classifier models to predict hotel ratings of TripAdvisor hotel reviews through sentiment analysis.
#### My Approach: 
  I plan to use natural language processing and algorithms like Naive Bayes to do sentiment analysis and make hotel rating predictions on TripAdvisor hotel review data. The data is separated into separate text files for reviews by hotel and the data also includes hotel ratings in csv files for hotel info by city. 
#### How people will interact with my work:
		I would like people to be able to interact with my work through a flask dashboard. I want them to be able to try uploading their own hotel review text to try out my finished hotel rating predictor and see if the rating my classifier predicts matches with what rating they would give based on the review. In the future, I would like to try to build a hotel recommender system based on my learnings.
#### Data Source(s): 
		The data I will use includes ~259,000 reviews of hotels in 10 different cities: Dubai, Beijing, London, New York City, New Delhi, San Francisco, Shanghai, Montreal, Las Vegas, and Chicago. There is a separate text file for each hotel with lines per review containing a date, review title and full review text. Along with the text files containing the reviews, there are also csv files for each city with hotel info (name, url, location info, number of reviews, and ratings (for cleanliness, room, service, location, value, and comfort, and overall) per row. I can join the review text file and hotel csv data by an ID called “doc_id.”
		http://kavita-ganesan.com/entity-ranking-data/#.Xq9nnRNKigT


___

# Project Idea #3: 
#### Topic (Title): 
  Benign vs Malignant Mole Classification
#### High Level Description: 
  I will build a model to classify images of moles as either benign or malignant.
#### My Approach: 
  I plan to train a Convolutional Neural Network to classify images of moles as benign or malignant.
How people will interact with my work:
		I would like people to be able to interact with my work through a flask dashboard. I want them to be able to try uploading their own mole pictures to try out my finished mole classifier.
#### Data Source(s): 
		I plan to use the International Skin Imaging Collaboration (ISIC, website: https://www.isic-archive.com/#!/topWithHeader/wideContentTop/main) Archive REST API: https://isic-archive.com/api/v1/ to get over 20,000 labeled mole images.
