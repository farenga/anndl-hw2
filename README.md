# ANNDL Homework #2

This repository contains the material related to the 2nd homework of the Artificial Neural Networks and Deep Learning Course, Politecnico di Milano.

Students: Nicola Farenga, Giorgio Longari.

The folder [`data-exp-preprocessing`](data-exp-preprocessing)  contains two notebooks concerning data exploration, preprocessing and loading.

The architectures that have been tested are the following:

1. Base models (SimpleRNN, LSTM, GRU)
2. LSTM Seq2Seq
3. LSTM Seq2Seq + Attention
4. Dilated causal CNN + LSTM (WaveNet-style)

They are all listed in the [`models.ipynb`](models.ipynb) notebook and the notebooks referred to their evaluation and comparisons can be found in the
[`architectures-evaluation`](architectures-evaluation)  folder.

We have performed multiple tests under different hyperparameters combinations, they can be found in the [`hyperparameters-tuning`](hyperparameters-tuning)  folder.

After selecting the best models we have retrained them on the complete dataset, the notebooks are stored in the  [`final-training`](final-training) folder.