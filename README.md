# Amazon-Reviews-Text-Summarization
Classifying the text reviews using LSTM Bi-GRU 

Consumers buy products from online based on the reviews provided by fellow customers whom earlier purchased the respective products. It becomes difficult for the people to read the entire review and then take a particular decision, in such cases summarizing the review would be very useful for the customers. To solve this problem, a method called Text Summarization can be used.
Text Summarization is a technique that summarizes a long a piece of content with important points outlined that gives an idea of the entire content.
Here, we classify the text data provided by millions of users around the globe into classes like positive, negative and neutral, also on emotions and the intentions of the users towards a particular product available online. We use a text summarization technique called sentinent analysis.

IMPLEMENTATION


The data was first cleaned and pre-processed. The entire dataset was then divided into training and testing data.
LSTM is an artificial recurrent neural network (RNN) architecture used for capturing long-term dependencies. Bidirectional GRU's are a type of bidirectional recurrent neural networks with only the input and forget gates. It allows for the use of information from both previous time steps and later time steps to make predictions about the current state. The pre-process data is fed into the LSTM model with Bi-GRU.

