# Context-Aware-Question-Answering-System
Develop a Python-based system that, given a document, can respond to user queries by extracting relevant information from the document using Natural Language Processing techniques.

This repository contains implementations of some of the most important papers for Question Answering. The implementations are in the form of tutorials and are roughly annotations of the said papers. This repository might be helpful for those who know the basics of deep learning and NLP, want to get started with reading slightly complex papers and see how they are implemented. This repository also assumes some familiarity with PyTorch basics, although I have tried my best to break everything down in simple terms.

**In My program I given textfile of Sport Crickets details and based on that I asked the question and program give answer from document.Currently My programe take Document which is file has ".txt" format.**

# PyTorch
PyTorch is a fully featured framework for building deep learning models, which is a type of machine learning that's commonly used in applications like image recognition and language processing. Written in Python, it's relatively easy for most machine learning developers to learn and use.

# Hugging Face
Hugging Face is a machine learning (ML) and data science platform and community that helps users build, deploy and train machine learning models. It provides the infrastructure to demo, run and deploy artificial intelligence (AI) in live applications.

# bert-large-uncased-whole-word-masking-finetuned-squad
BERT is a transformers model pretrained on a large corpus of English data in a self-supervised fashion. This means it was pretrained on the raw texts only, with no humans labelling them in any way (which is why it can use lots of publicly available data) with an automatic process to generate inputs and labels from those texts. More precisely, it was pretrained with two objectives:

Masked language modeling (MLM): taking a sentence, the model randomly masks 15% of the words in the input then run the entire masked sentence through the model and has to predict the masked words. This is different from traditional recurrent neural networks (RNNs) that usually see the words one after the other, or from autoregressive models like GPT which internally mask the future tokens. It allows the model to learn a bidirectional representation of the sentence.
Next sentence prediction (NSP): the models concatenates two masked sentences as inputs during pretraining. Sometimes they correspond to sentences that were next to each other in the original text, sometimes not. The model then has to predict if the two sentences were following each other or not.

# ScreenShot

![assignment_1](https://github.com/parthmodi2712/Context-Aware-Question-Answering-System/assets/69354693/b9e4c826-12fd-466e-9433-89fee2ce5cd9)

![assignment_2](https://github.com/parthmodi2712/Context-Aware-Question-Answering-System/assets/69354693/cef5c5db-7fb1-4b6b-8e5e-d5405ca11ffc)

![assignment_3](https://github.com/parthmodi2712/Context-Aware-Question-Answering-System/assets/69354693/f4af4307-29e2-411a-a712-8d7342eeb864)

![assignment_4](https://github.com/parthmodi2712/Context-Aware-Question-Answering-System/assets/69354693/22af3670-b508-4f28-b23a-919a6a442338)




