# Emotion-Recognition-Based-Voice-Chatbot

This is Emotion Recognition based Voice chatbot using Transformer model. The Transformer model is a type of deep neural network architecture that has revolutionized the field of natural language processing (NLP).
It was first introduced in a paper called "Attention is All You Need" by Vaswani et al. in 2017. 

The reference for transformer model is here https://blog.tensorflow.org/2019/05/transformer-chatbot-tutorial-with-tensorflow-2.html .
This project demonstrates how Emotion can play vital role in generation of human-like responses of the transformer model.


1. Run transformer\Emotion-Aware Transformer to generate tokenizer.tf and mymodel.h5.
Here, mymodel.h5 is pretrained transformer model to generate reply.
The data for training transformer model is collected from kaggle https://www.kaggle.com/datasets/atharvjairath/empathetic-dialogues-facebook-ai .
And necessary data preprocessing is done to obtain cleaneddata.csv.

2. Add models from given links
   emotion_model\Emotion_Model.h5 is pretrained model to detect Emotion from voice.
   Text_emotion.sav is pretrained model to detect Emotion from text


Install requirements.txt for merged.ipynb to work
