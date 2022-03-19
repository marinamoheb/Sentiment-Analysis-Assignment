# Sentiment-Analysis-Assignment
Description:  Used Dataset  We used an 'Arabic tweets dataset avaliable trough kaggle' it consists of 45275 tweets(22761 "Positive", 22514 "Negative").

We splitted the data (20% testing "tt_data, tt_label", 80% trainning "t_data, t_label" ). Data Preprocessing Arabert preprocessor to remove(emojies, tashkeel, tatweel, ...etc). 

NLTK's RegexpTokenizer to tokenize any sentence to words only. NLTK's stopwords('arabic') to remove any stop words from tokens if existed. Feature Extraction we used

CountVectorizer to convert the sentences to matrix of token counts. Used Classification Models MultinomialNB "Accuracy : 78%". LinearSVC "Accuracy : 78%". 

RandomForestClassifier "Accuracy: 76%"
