This project implements ["Graph Convolutional Networks for Text Classification. Yao et al. AAAI2019."](https://arxiv.org/abs/1809.05679) in PyTorch.

This implementation highly based on official code [yao8839836/text_gcn](<https://github.com/yao8839836/text_gcn>).

## Require

* Python 3.6
* PyTorch 1.0

## Running training and evaluation

1. run 'Data preparation+ Building corpus.ipynb' file for data preprocessing and building graph (word - word relation, word-doc relation)
2. run 'text_gcn_implementation_Goggles' for training and testing.