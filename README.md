# Movie-Review--Bert
we did a sentiment analysis model with bert

Sentiments Classifier using BERT

PROBLEM STAEMENT
In this project we will be building a sentiment classifier using the bert pretained model. The dataset we will be using will be IMDB movie reviews datset.
DESCRIPTION OVERVIEW
The process of computationally identifying and categorizing opinions expressed in a piece of text, especially in order to determine whether the writer's attitude towards a particular topic, product, etc. is positive, negative, or neutral. Understanding people’s emotions is essential for businesses since customers are able to express their thoughts and feelings more openly than ever before. By automatically analyzing customer feedback, from survey responses to social media conversations, brands are able to listen attentively to their customers, and tailor products and services to meet their needs.
Sentiment analysis, however, helps businesses make sense of all this unstructured text by automatically tagging it. Sentiment analysis uses various Natural Language Processing (NLP) methods and algorithms, which we’ll go over in more detail in this section.
The main types of algorithms used include:
	•	Rule-based systems that perform sentiment analysis based on a set of manually crafted rules.
	•	Automatic systems that rely on machine learning techniques to learn from data.
	•	Hybrid systems that combine both rule-based and automatic approaches.

Sentiment analysis can be used for varous applications like :
	•	Social media monitoring
	•	Brand monitoring
	•	Voice of customer (VoC)
	•	Customer service
	•	Market research


TECHNOLOGY USE
Here we will be using  Anaconda Python 3.6 , Pytorch 1.4 with GPU support CUDA 10 with CuDNN 10.

WORKFLOW DIAGRAM


IMPLEMENTATION

1. models :- this folder will keep the model that have been trained on the dataset using BERT architecture.

2.  clientApp.py

This python file will will be used to train/predict.

3. predictionFile.py


prediction file :- this is the file where predicton is done.


TESTING IN LOCAL/API
To do the test testing we need to run the clientApp.py and after that web server will start at http://0.0.0.0:5000/


Enter the review or reviews and click on predict
After clicking predict
<img width="1439" alt="Screenshot 2021-05-27 at 2 53 31 PM" src="https://user-images.githubusercontent.com/55822384/119801492-6249bb00-befb-11eb-8a2d-c4201c7084fd.png">

CONCLUSION
Here we successfully performed sentiment analysis and analyzed the reviews on the given dataset.
COMPARISION
More data or better larger dataset can be used to build a better model. We can also try out better pre trained model with fine tuning to increase the performance.

