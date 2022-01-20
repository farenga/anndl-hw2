# ANNDL Homework #2

This repository contains the material related to the 2nd homework of the Artificial Neural Networks and Deep Learning Course, Politecnico di Milano.

Students: Nicola Farenga, Giorgio Longari.

The architectures that have been tested are the following:

1. Base models (SimpleRNN, LSTM, GRU)
2. LSTM Seq2Seq
3. LSTM Seq2Seq + Attention
4. Dilatated causal CNN + LSTM (WaveNet-style)

The notebooks referred to their evaluation and comparisons can be found in the
[`architectures-evaluation`](architectures-evaluation)  folder.

We have performed multiple tests under different hyperparameters combinations, they can be found in the [`hyperparameters-tuning`](hyperparameters-tuning)  folder.

After selecting the models that performed better we have trained those architectures on the complete dataset, the notebooks are stored in the  [`final-training`](final-training) folder.