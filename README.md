# Machine-Translation-Spanish---English

Machine translation is the method of utilizing Artificial Intelligence, namely deep learning mechanisms (i.e., neural network architectures), to effectively convert the translation of one language into another with relatively high accuracy and low errors (loss, in other terms). 

Sequence to Sequence modeling is one of the best approaches to solving tasks related to machine translation. It was one of the earlier methods that were previously used in Google Translate to obtain desirable results.


# Sequence To Sequence Models
The Sequence To Sequence models usually consists of an encoder and decoder model. 

The encoder and decoder are two big individual components that work together to produce desirable results while performing computations. The encoder and decoder models together form the sequence-to-sequence models. The process of taking in the input sequences is done by the encoder, and the decoder has the function of producing the respective target sequences.


## Encoder Decoder Architecture
![ED](https://user-images.githubusercontent.com/20738202/193803243-a4282a35-ad83-42fe-ac45-4a107686bd4f.png)


# Significance of Attention
While working with sequence to sequence models, it sometimes becomes significant to distinguish between the essential components in a particular task.

I will state an example for a computer vision and NLP task. For a computer vision task, let us consider an image of a dog walking on the ground. The sequence to sequence model can identify the following fairly easily. But with the help of the attention mechanism, we can add more weightage to the essential component in the image, which is the dog. Similarly, for an NLP task, we need to focus on particular words more than others to understand the context better. Attention is useful even in these scenarios.


![Attention](https://user-images.githubusercontent.com/20738202/193803495-249ca140-da1d-4b3a-abe6-a3f68573cc9c.png)


# Summary:

•	Used GloVe vectors for word embedding and the Teacher Forcing method for training the LSTM network using Keras efficiently. 

•	Implemented an encoder-decoder system to build a Seq2Seq model and an Attention model to convert English text messages into Spanish with an accuracy score of 75%.
