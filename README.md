This is the replication of original work created using TorchMoji model [here](https://github.com/huggingface/torchMoji)

Here in this research, we will replicate a work that used millions of emoji occurrences to study any domain illustrations in order to detect sentiment, emotion and sarcasm underlying. TorchMoji is a [pyTorch](http://pytorch.org/) implementation of the [DeepMoji](https://github.com/bfelbo/DeepMoji) model developped by Bjarke Felbo, Alan Mislove, Anders Søgaard, Iyad Rahwan and Sune Lehmann. This model trained on 1.2 billion tweets with emojis to understand how language is used to express emotions. Through transfer learning the model can obtain state-of-the-art performance on many emotion-related text modeling tasks.


## Overview
* [Source Code replication.ipynb/](Source Code replication) contains the output of source replication.
* [Score Prediction.ipynb/](Score Prediction) contains short code snippets showing how to calculate the scores.
* [Original dataset Evaluation.ipynb/](Original Dataset Evaluation) contains the accuracy score generated through benchmark dataset.
* [New Dataset creation and evaluation.ipynb/](New Dataset Creation and Evaluation) contains new data creation and evaluation


Please consider citing the [paper](https://arxiv.org/abs/1708.00524) of DeepMoji if you use the model or code (see below for citation).

