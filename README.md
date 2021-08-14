# Neural-Machine-Translation
The goal of this project is to build an English-to-German neural machine translation (NMT) model using Long Short-Term Memory (LSTM) networks with attention.

Machine translation is an important task in natural language processing and could be useful not only for translating one language to another but also for word sense disambiguation (e.g. determining whether the word "bank" refers to the financial bank, or the land alongside a river). Implementing this using just a Recurrent Neural Network (RNN) with LSTMs can work for short to medium length sentences but can result in vanishing gradients for very long sequences. To solve this, an attention mechanism can be added to allow the decoder to access all relevant parts of the input sentence regardless of its length. 

### The Neural-Machine-Translation model that is implemented:

![Alt Text](https://github.com/saeedkhaki92/Neural-Machine-Translation/blob/main/NMTModel.png)



## Getting Started

### Dependencies

Following packages should be installed on python 3:

- Trax
- numpy
- random

<a href="https://github.com/google/trax" target="_blank">Trax</a> is an end-to-end library for deep learning that focuses on clear code and speed. It is actively used and maintained in the Google Brain team. It is faster than Tensorflow and Pytorch and also the codes are more clear. It also supprts both TPUs and GPUs.




## Dataset

We will use a small dataset from `Opus`, a growing collection of translated texts from the web. Particularly, we will get an English to German translation subset specified as opus/medical which has medical related texts. ` Tensorflow Datasets (TFDS)` also has German to English dataset.




## Instructions

You can train the model from scrath using the Google Colab notebooks. Please use `Neural-Machine-Translation.ipynb` for Trax version.


