# offensive_arabic_tweets_classifier
use machine learning models (svm ,random forest ,naive_bayes) to detect offinsive arabic  tweets from OSACT 2022 competition ,models on original tweets ( no preprocessing for tweets)  

--used liberaries--

  -sklearn (tf-idf ,train_test_split ,classification report ,confusion matrix ,svm ,random forest ,naive_bayes)
  -pandas
  -numpy

--files description--

  -tf-idf_on_original_data (apply tf-idf and models) 
  -NLP_preprocessing  (apply preprocessing and data cleaning) 
  -HT4.csv  (saved preprocessed data)  
  -nlp_ht   (original data from OSACT 2022)

 
--preprocessing-- 

  -convert txt file to csv
  -deal with null values
  -convert string labels to numbers (OFF ,VIO ,VLG)->[0,1] (HS)->one-hot encoding



--in process for 2nd version--

  -deal with emojies with keeping its meanings
  -remove stop words
  -limitize words
  -padding tweets to be the same length
  -word embidding
  -use RNN
  -try BERT
