This is the replication of original work created using TorchMoji model [here](https://github.com/huggingface/torchMoji)

# 😇 TorchMoji

TorchMoji is a [pyTorch](http://pytorch.org/) implementation of the [DeepMoji](https://github.com/bfelbo/DeepMoji) model developped by Bjarke Felbo, Alan Mislove, Anders Søgaard, Iyad Rahwan and Sune Lehmann.

This model trained on 1.2 billion tweets with emojis to understand how language is used to express emotions. Through transfer learning the model can obtain state-of-the-art performance on many emotion-related text modeling tasks.

Try the online demo of DeepMoji [http://deepmoji.mit.edu](http://deepmoji.mit.edu/)! See the [paper](https://arxiv.org/abs/1708.00524), [blog post](https://medium.com/@bjarkefelbo/what-can-we-learn-from-emojis-6beb165a5ea0) or [FAQ](https://www.media.mit.edu/projects/deepmoji/overview/) for more details.

## Overview
* [torchmoji/](torchmoji) contains all the underlying code needed to convert a dataset to the vocabulary and use the model.
* [examples/](examples) contains short code snippets showing how to convert a dataset to the vocabulary, load up the model and run it on that dataset.
* [scripts/](scripts) contains code for processing and analysing datasets to reproduce results in the paper.
* [model/](model) contains the pretrained model and vocabulary.
* [data/](data) contains raw and processed datasets that we include in this repository for testing.
* [tests/](tests) contains unit tests for the codebase.

To start out with, have a look inside the [examples/](examples) directory. See [score_texts_emojis.py](examples/score_texts_emojis.py) for how to use DeepMoji to extract emoji predictions, [encode_texts.py](examples/encode_texts.py) for how to convert text into 2304-dimensional emotional feature vectors or [finetune_youtube_last.py](examples/finetune_youtube_last.py) for how to use the model for transfer learning on a new dataset.

Please consider citing the [paper](https://arxiv.org/abs/1708.00524) of DeepMoji if you use the model or code (see below for citation).

