# Covid-19-Sentiment-analysis-on-Twiteer
Unveiling COVID-19 Sentiments on Twitter: Advanced Natural language processing(NLP) and Deep learning Sentiment Analysis

Text-based conversations provide a challenge to sentimental identification since they lack body speech and language variations. The key goal of this project is to use the tweets on the coronavirus (COVID-19) to determine the sentiment related to the pandemic using advanced NLP technique and deep learning model RNN (Recurrent Neural Network) for classifying twitter sentiments into positive, negative, and neutral classes. The study evaluates the interpretability and practical applicability of the model in addition to metrics such as accuracy and confidence score. 

##########################Workflow##################
1. The first phase of the project is to collect a large COVID-19 tweets dataset and the dataset is unlabelled which contains 179109 rows and 13 columns.
2. Pre-processing work is done in the second phase to turn the raw data into data that can be used for feature extraction and modeling.
3. Third phase is to perform NLP task for feature extraction and identify sentiments as positive and negative and neutral.
4. Fourth step is to split the data into training, validation, and testing tests.
5. Next step is to perform training of the data on deep learning model.
6. To determine the accuracy of the models, the test dataset is tested against the trained models in the sixth phase.
7. Last phase is to evaluate accuracy and efficiency of deep learning model RNN and classify the tweets sentiments as positive, negative, and neutral.
![image](https://github.com/user-attachments/assets/9cf5671e-4a6d-47c6-8163-bd5f38f79b33)

![image](https://github.com/user-attachments/assets/11e2470a-2261-4042-90a2-69332253739f)

Demo:
![image](https://github.com/user-attachments/assets/e3c3cb2e-9b08-41d5-bb21-9a0a5099d814)
![image](https://github.com/user-attachments/assets/cd12f7bc-75b4-4e67-90bd-2644d319a334)
Textblob:
![image](https://github.com/user-attachments/assets/3cec35f4-6810-45cd-95e7-47856b3965c2)

Sentiments Idenfied out of tweets:
The count of sentiments is given below:
Neutral     74862
Positive    74636
Negative    29610
![image](https://github.com/user-attachments/assets/fa715c25-59c0-4c09-b8c9-56571ddf4750)

![image](https://github.com/user-attachments/assets/571de00e-3ce9-4aff-92fb-d9f41701667d)

WordCloud:
![image](https://github.com/user-attachments/assets/ced5119a-9c4a-4681-a7ba-c5e61fc4b834)

Recurrent Neural Network Classification:
![image](https://github.com/user-attachments/assets/0c9dfae2-078a-47c5-9511-656dcefcc0f2)
![image](https://github.com/user-attachments/assets/994adf39-dd85-4ca6-8e17-e702e2697e43)
![image](https://github.com/user-attachments/assets/12b1dba8-9a1a-4017-ba80-af6711d8bb53)

Conclusion:
NLP successfully determined the sentiments(positive, negative, neutral) from unlabeled covid-19 tweets dataset.
The unlabeled dataset was successfully preprocessed by NLP such as removing special characters, stop words, punctuations, tokenization and stemming.
Accuracy achieved by RNN model is 49% for text classification![image](https://github.com/user-attachments/assets/258a7482-1bda-4cc8-934e-7a650fe2524c)










