# Siamese-Manhattan-LSTM-MaLSTM-
Siamese Manhattan LSTM for quora similar question-pair checking.

Manhattan LSTM (MaLSTM) — a Siamese deep network and its appliance to Kaggle’s Quora Pairs competition.The data will be  downloaded internally in colab, you have to change few paths, only as this was connected to my google drive.

ABOUT MALSTM:
Siamese networks are networks that have two or more identical sub-networks in them.
Siamese networks seem to perform well on similarity tasks and have been used for tasks like sentence semantic similarity, recognizing forged signatures and many more.

In MaLSTM the identical sub-network is all the way from the embedding up to the last LSTM hidden state.
This notebook is about implementing the MaLSTM model (http://www.mit.edu/~jonasm/info/MuellerThyagarajan_AAAI16.pdf) on Kaggle's Quora Question Pairs data.

Code is inspired from Medium blog post(https://medium.com/mlreview/implementing-malstm-on-kaggles-quora-question-pairs-competition-8b31b0b16a07) and git repo from Elior Cohen
