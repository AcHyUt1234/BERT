## Natural Language Processing (NLP) with BERT

**Overview**

The project performs semantic analysis on movie reviews using data from one of the most visited websites in the world: IMDB! The semantic analysis is done using the low-code Python library, Ktrain.

Not only is BERT (Bidirectional Encoder Representations from Transformers) a framework that has been pre-trained with the biggest data set ever used, it is also remarkably easy to adapt to different NLP applications, by adding additional output layers. This allows users to create sophisticated and precise models to carry out a wide variety of NLP tasks.

**Learnings:**

- Natural Language Processing
- How to implement the BERT model
- Sentiment Analysis

The code workflow will unfold as follows:

*Part 1: Data Preprocessing*
- Loading the IMDB dataset
- Creating the training and test sets

*Part 2: Building the BERT model*

*Part 3: Training and evaluating the BERT model*
- Getting the learner instance
- Training and evaluating the BERT model

**About BERT & Transformer:**

BERT is a deep learning framework, developed by Google, that can be applied to NLP. 

*Bidirectional (B)*

This means that the NLP BERT framework learns information from both the right and left side of a word (or token in NLP parlance). This makes it more efficient at understanding context. 

For example, consider these two sentences:

Jimmy sat down in an armchair to read his favorite magazine.

Jimmy took a magazine and loaded it into his assault rifle. 

Same word – two meanings, also known as a homonym. As BERT is bidirectional it will interpret both the left-hand and right-hand context of these two sentences. This allows the framework to more accurately predict the token given the context or vice-versa.

*Encoder Representations (ER)*

This refers to an encoder which is a program or algorithm used to learn a representation from a set of data. In BERT’s case, the set of data is vast, drawing from both Wikipedia (2,500 millions words) and Google’s book corpus (800 million words). 

The vast number of words used in the pretraining phase means that BERT has developed an intricate understanding of how language works, making it a highly useful tool in NLP.

*Transformer (T)*

This means that BERT is based on the Transformer architecture.

To put it simply, Transformer is a deep machine learning model that was released in 2017, as a model for NLP.

Transformer performs a similar job to an RNN, i.e. it processes ordered sequences of data, applies an algorithm, and returns a series of outputs. Unlike RNNs, the Transformer model doesn’t have to analyze the sequence in order. Therefore, when it comes to natural language, the Transformer model can begin by processing any part of a sentence, not necessarily reading it from beginning to end.

The unordered nature of Transformer’s processing means it is more suited to parallelization (performing multiple processes simultaneously). For this reason, since the introduction of the Transformer model, the amount of data that can be used during the training of NLP systems has rocketed. 
