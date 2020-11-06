This is the replication of original work created using TorchMoji model [here](https://github.com/huggingface/torchMoji)

Here in this research, we will replicate a work that used millions of emoji occurrences to study any domain illustrations in order to detect sentiment, emotion and sarcasm underlying. TorchMoji is a [pyTorch](http://pytorch.org/) implementation of the [DeepMoji](https://github.com/bfelbo/DeepMoji) model developped by Bjarke Felbo, Alan Mislove, Anders Søgaard, Iyad Rahwan and Sune Lehmann. 

This model trained on 1.2 billion tweets with emojis to understand how language is used to express emotions. Through transfer learning the model can obtain state-of-the-art performance on many emotion-related text modeling tasks.


## Description

* Source Code replication.ipynb contains the output of source replication.
* Score Prediction.ipynb contains short code snippets showing how to calculate the scores.
* Original dataset Evaluation.ipynb contains the accuracy score generated through benchmark dataset.
* New Dataset creation and evaluation.ipynb contains new data creation and evaluation


## Citation
```
@inproceedings{felbo2017,
  title={Using millions of emoji occurrences to learn any-domain representations for detecting sentiment, emotion and sarcasm},
  author={Felbo, Bjarke and Mislove, Alan and S{\o}gaard, Anders and Rahwan, Iyad and Lehmann, Sune},
  booktitle={Conference on Empirical Methods in Natural Language Processing (EMNLP)},
  year={2017}
}
```

