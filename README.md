
# Seq2Seq Headline Generator

<img align="right" src="https://github.com/alextruesdale/seq2seq-headline-generator/blob/master/repository_media/repo_image.png" alt="Word Length Distribution of Articles" title="Seq2Seq Headline Generator" height="205" />

## Summary

In this repository, you will find the Jupyter Notebook in which all code for this sequence-to-sequence task is organised. The goal herein is to examine the information content of headlines for news articles in their usefulness as inputs for a classification task. Generated headlines from the seq2seq model are compared to the originals within the same scope. The purpose of generating headlines is to consider the possibility that human-written story headlines are written to grab attention rather than convery story content or a summary of a given article – generated headlines are intended to be more neutral, though there is an inherent bias here, considering that they are trained on human-written headlines.

Alongside pursuit of answers to this hypothesis, the simple(r) task of producing a functioning text generation model is central in this notebook. Concessions on model complexity and added or omitted components are made due to time / scoping constraints. In the end, the original hypothesis remains partially untested, but the initial performance of the generation model is encouraging for further development in the interest of this or other use cases.

## Tools & Technology
- Python3
- Google Colab
- Keras / Tensorflow
- scikit-learn
