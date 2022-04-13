# Machine-Learning-projects

A collection of small ML projects in Notebook form

- Bigmarket https://portfolio-apps-ashna.herokuapp.com/jpn?page=big_market
  Big Market sales prediction and Data exploration.
  Use following Regressors for triaining  - LinearRegression, Ridge, DecisionTreeRegressor, XGBRegressor
  The performance of each model is then compared using RMSE and cross value Scores.
  Missing values are imputed
  
- covid_articles https://portfolio-apps-ashna.herokuapp.com/jpn?page=related_articles
  Projects works on clustering of related articles so that it is easy to search for articles that answer a particluar query
  LatentDirichletAllocation is used to classify all articles under 50 broad groups
  A clear division was obtained in such a grouping
  The parameters from the topic grouping is then used to identify the most similar articles using jensenshannon divergence
  
- covid_eda https://portfolio-apps-ashna.herokuapp.com/jpn?page=covid_eda
  Covid Exploratory analysis of data from JOHN HOPKIND repository
  Mainly regional classification of data is done
  Regional classification based on worst affected places, highest mortality rate, Test count, Positive rate is explored

- melanoma_classification https://portfolio-apps-ashna.herokuapp.com/jpn?page=melanoma
  Project classifies Melanoma (Skin Cancer) Image Dataset using various Image processing Techniques
  Taining Data set is prepared by passing through Transformation piplines for  RandomResizedCrop, HorizontalFlip, VerticalFlip, Change HueSaturation, RandomBrightnessContrast
  Resnet50Netwrok and EfficientNetwork model is used to trained on the prepared data to identify whether the given image show Melanoma or not
  
- sentiment_text_extraction https://portfolio-apps-ashna.herokuapp.com/jpn?page=sentiment_spacy
  Project to extract Emotion (abstract of text which best represents emotion) in Text tweets with existing sentiment labels.
  Named Entity Recognition is used to train the texts for deriving abstract'
  3 different models are tained for POsitive and Negative labels
  For neutral models above 95% has full text as abstract in train data, so no model is trained
  
  
