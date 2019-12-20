## Domain Classification with Keras / Tensorflow 2.0


This project is about a Deep Learning model, that classifies domain names into 15 categories.

e.g. For the input, nytimes.com should predict the category sport
Besides the domains, no further information is given to the model. 


The model contains an LSTM layer, that processes a sequence of characters. 
It is trained with a categorical cross-entropy loss function.



### Results 

The accuracy is 52% which is not bad if you consider that with random guessing it would be 6.6%.
Not much time was put into fine-tuning. The performance could probably be improved, e.g. by adding another LSTM layer or experimenting with hyper-parameters.
