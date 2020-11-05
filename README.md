This is the replication of original work created using TorchMoji model [here](https://github.com/huggingface/torchMoji)

Here in this report, we will explain about our reproducible research based on a paper that used millions of emoji occurrences to study any domain illustrations in order to detect sentiment, emotion and sarcasm underlying.

# 😇 TorchMoji

TorchMoji is a [pyTorch](http://pytorch.org/) implementation of the [DeepMoji](https://github.com/bfelbo/DeepMoji) model developped by Bjarke Felbo, Alan Mislove, Anders Søgaard, Iyad Rahwan and Sune Lehmann.

This model trained on 1.2 billion tweets with emojis to understand how language is used to express emotions. Through transfer learning the model can obtain state-of-the-art performance on many emotion-related text modeling tasks.

Try the online demo of DeepMoji [http://deepmoji.mit.edu](http://deepmoji.mit.edu/)! See the [paper](https://arxiv.org/abs/1708.00524), [blog post](https://medium.com/@bjarkefelbo/what-can-we-learn-from-emojis-6beb165a5ea0) or [FAQ](https://www.media.mit.edu/projects/deepmoji/overview/) for more details.

## Overview
* [Source Code replication.ipynb/] contains all the underlying code needed to successfully install the code.
* [Score Prediction.ipynb/] contains short code snippets showing how to calculate the scores.
* [Original dataset Evaluation.ipynb/] contains the accuracy score generated through benchmark dataset.
* [New Dataset creation and evaluation.ipynb/]contains new data creation and evaluation


Please consider citing the [paper](https://arxiv.org/abs/1708.00524) of DeepMoji if you use the model or code (see below for citation).

