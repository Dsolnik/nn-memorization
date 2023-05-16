# Where Neural Nets Memorize
In this project, we try to estimate where (i.e. which layers of a neural network) certain
points are memorization and gain insights into the inner happenings of the network from these
points. 

We use PyTorch to generate ResNet18 models.

In this repo, there are a PDF and 3 notebooks:

## Paper.pdf
This is the paper describing the results of the paper.

## Torch-MemBasic.ipynb
In this notebook, we repeat the experiment done by Feldman, Zhang in "What Neural Networks Memorize and Why: Discovering the Long Tail via Influence Estimation" by training many ResNet18 models on the MNIST data set to indentify memorized 
values.

## Torch_perLayer.ipynb
In this notebook, we generate models to estimate memorization per layer. For each model, we generate 150 models.

## AnalyzeResultsPerLayer.ipynb
In this notebook, we analyze the results from the models produced in "TorchPerLayer.ipynb" to understand
what points are being memorized.

