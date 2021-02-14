# Transformer_tensorflow_Keras

**[Spainish-English Translator](https://colab.research.google.com/drive/1--zREhsilfCk8too4Wj6NR_a5u1AQ0q_#scrollTo=H7uxoHSxzh6C)**

This notebook implements a simple ML model to translate from Spainish to English with the [**Transformer**](https://arxiv.org/abs/1706.03762) architecture. The basic pipeline for this notebook is similar to the two official Tensorflow tutorials:     
+ [Neural Machine Translation](https://www.tensorflow.org/tutorials/text/nmt_with_attention)
+ [Transformer model for Languge Understanding](https://www.tensorflow.org/tutorials/text/transformer)

but we re-structure and re-implement several critical sections to follow typical keras-styles. 


We download the [Spain-to-English](http://storage.googleapis.com/download.tensorflow.org/data/spa-eng.zip) corpus, standardize and tokenize the texts, encode and decode input-output pairs with the **transformer** architecture, and translate some simple Spanish sentences. 


**Spanish**: *esta es mi vida .*     
**English**: *this is my life .*
