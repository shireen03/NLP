# NLP project

A comparative analysis between SVM and Neural network LSTM for predicting sentiment movie reviews.

Firstly, the dataset was preprocessed to eliminate noise. Then the data was converted into index document frequencies, using TF-IDF. The language models used to predict whether the movie review is positive or negative include: SVC and LSTM. Finetuning the parameters and different preprocessing techniques were used to optimize our accuracy, precision, recall and f1-score. Moreover we used Mc Nemar's test to determine the p-value and test statistic of the two models. We evaluated that we can not reject the null hypothesis, therefore the two models behave similarly in terms of performance.
