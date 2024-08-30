**DATASET**

The dataset is derived from a kaggle contest 

Link : https://www.kaggle.com/c/jigsaw-toxic-comment-classification-challenge/data

We are provided with a large number of Wikipedia comments which have been labeled by human raters for toxic behavior. The types of toxicity are:

toxic

severe_toxic

obscene

threat

insult

identity_hate



**MODEL**

Our model is a BiLSTM model and achieves a 98% accuracy by using the textvectorization from tensorflow. (70-20-10 train-val-test split) on train.csv available at the link.

**Further scope :-**
1. Use of LLMs in data annotation : We aim to leverage common sense knowledge of LLMs - ChatGPT, LLAMA to annotate data for this purpose and compare results. The idea is to replace the tiring human annotation process.

2. Use TextSpecific Transformer models : BeRT, RoberTa - transformer models have recently produced state of the art results on text processing and can be leveraged here

3. Use different architectures to compare performances.


Note : We just evaluated on toxicity criteria.

**Project** 

We finally deliver an interface using gradio which inputs a sentence and classifies it as toxic or non toxic 
