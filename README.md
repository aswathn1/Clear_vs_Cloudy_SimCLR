# Clear_vs_Cloudy_SimCLR

Binary Classification Model to classify remote sensing imagery as clear or cloudy using the [SimCLRv2](https://github.com/google-research/simclr) approach to learn representations from unlabeled imagery.

### LinearEval Notebook

Enables applying the trained SimCLRv2 encoder for a classification task by training a Linear layer attached to the encoder head.

### ResNet Baseline

Enables training a supervised ResNet model for a binary classification task.

## Installing dependencies

```
$ conda env create --name simclr --file env.yml
$ conda activate simclr
$ python run.py
```

## Config file

Before running SimCLR, make sure you choose the correct running configurations on the ```config.yaml``` file.
