# TMLC-Fellowship-Task-
This is my TMLC Fellowship task 


## 📋 Project Overview
This is my TLMC Fellowship Task for Ecommerce Text Classification to recognize whether the given description is related to Electronics (0), Households (1), Books (2), or Clothing & Accessories (3) products.
<br>
<br>

👩‍##💻Algorithm Used: BERT (Bidirectional Encoder Representations from Transformers)

## BERT is based on the Transformer architecture

ABOUT BERT: Bidirectional Encoder Representations from Transformers is known as BERT. It is intended to jointly condition on both left and right context to pre-train deep bidirectional representations from unlabeled text. With just one additional output layer, the pre-trained BERT model can be improved to produce cutting-edge models for a variety of NLP tasks.


## 🔖 Reason behind using BERT:
In many natural language problems, BERT outperforms the state-of-the-art by assisting machines in learning excellent representations of text in relation to context.
## 🔖 Introduction to Bert :
	
As opposed to directional models, which read the text input sequentially (left-to-right or right-to-left), the Transformer encoder reads the entire sequence of words at once. Therefore it is considered bidirectional, though it would be more accurate to say that it’s non-directional. This characteristic allows the model to learn the context of a word based on all of its surroundings (left and right of the word).
<br>
<br>
The BERT architecture builds on top of Transformer. We currently have two variants available:

BERT Base: 12 layers (transformer blocks), 12 attention heads, and 110 million parameters BERT Large: 24 layers (transformer blocks), 16 attention heads and, 340 million parameters.

<p align="left">
   <a href="#">
	<img src="https://github.com/PriyankaKumari-2002/TMLC-Fellowship-Task-/blob/main/bert_encoder.png?raw=true width="600", height="300" alt="TLMC Fellowship 22"/>
	
	
</a>
</p>
<br>
<br>
To help the model distinguish between the two sentences in training, the input is processed in the following way before entering the model:

A [CLS] token is inserted at the beginning of the first sentence and a [SEP] token is inserted at the end of each sentence.
A sentence embedding indicating Sentence A or Sentence B is added to each token. Sentence embeddings are similar in concept to token embeddings with a vocabulary of 2.
A positional embedding is added to each token to indicate its position in the sequence. 


<p align="left">
   <a href="#">
	<img src="https://github.com/PriyankaKumari-2002/TMLC-Fellowship-Task-/blob/main/bert_emnedding.png?raw=true width="600", height="300" alt="TLMC Fellowship 22"/>
	
	
</a>
</p>
												    

## 💡Note: In practice, the BERT implementation is slightly more elaborate and doesn’t replace all of the 15% masked words.
	
