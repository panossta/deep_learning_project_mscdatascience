# Text Sentiment Analysis
This is a Sentiment Analysis project using Neural Networks via Tensorflow, created in Python.


## Table of contents
* [Motivation](#Motivation)
* [Information](#Information)
* [Technologies](#Technologies)


### Motivation
The need to “speak computer” is no longer a barrier to leveraging machines. For the first time in history we are able to communicate with computers in the same way we speak to each other. Gone are the days of relying on keywords and specific syntax designed to activate an algorithm. We can talk to virtual assistants in our phones, receive curated purchasing advice from chatbots, and let autocomplete features assist with our searches, write our emails, and ask our questions. All of these are examples of NLP in action. Sentiment analysis is an application of natural language processing (NLP) that reveals the emotional states in human speech or text -- in this case, the speech and text that customers generate. Businesses can use machine-learning-based sentiment analysis software to examine this speech and text for positive or negative sentiment about the brand. With this information, companies have an opportunity to respond meaningfully -- and with greater empathy. The aim is to improve the customer relationship and enhance customer loyalty. As Social Media keep growing the need of knowing what people think about different topics is of great importance since it can help many fields understand what their "targets" are thinking. Sentiment analysis can identify critical issues in real-time, for example is a PR crisis on social media escalating? Is an angry customer about to churn? Sentiment analysis models can help you immediately identify these kinds of situations, so you can take action right away. It’s estimated that people only agree around 60-65% of the time when determining the sentiment of a particular text. Tagging text by sentiment is highly subjective, influenced by personal experiences, thoughts, and beliefs. By using a centralized sentiment analysis system, companies can apply the same criteria to all of their data, helping them improve accuracy and gain better insights.


### Information
This project aims to create a model that predicts sufficiently the sentiment of a sentence. The project was developed on the IMDB Review dataset that contains 50.000 reviews both negative and positive. Many preprocessing strategies have been used in order to clean our data in order to move to the next step which is to transform them into a language that the computer can read. A Neural Network was build containg one Embedding Layer, a Conv1D layer , two LSTM layers , two Dropout layers to reduce overfitting and one Dense layer. Overall, our model achieved an accuracy of 87.5% in the validation set and 98% on the training set. To confirm this accuracy , we first predict some random reviews from our dataset and afterwards, we create our own sentences and markdown its accuracy.



### Technologies
This particular jupyter notebook was done in Python 3.9.12 and the following need to be pip installed:
- pip install tensorflow==2.9.0
- pip install wordcloud
- pip install pydot==1.2.3
- pip install graphviz

T


