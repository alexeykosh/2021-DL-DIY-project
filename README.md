## Deep Learning DIY project: Neural Network  Acceptability Judgments replication with transformers
#### *Alexey Koshevoy*

### Description:

In this project I tried to replicate this [paper](https://direct.mit.edu/tacl/article/doi/10.1162/tacl_a_00290/43528) using transformers (GPT2, BERT and ELECTRA). I trained these models using the data from the [CoLA corpus](https://nyu-mll.github.io/CoLA/). The best results are achieved with ELECTRA model (in-domain test set: accuracy -- 0.8408, MCC -- 0.6029). This performance is comparable with human annotators benchmark in the original paper (in-domain test set: accuracy: -- 0.850, MCC -- 0.644).

### Code:

Most of the code in this project is based on [this](https://mccormickml.com/2019/07/22/BERT-fine-tuning/) tutorial.

All of the code can be found [here](https://github.com/alexeykosh/2021-DL-DIY-project/blob/main/results.ipynb).
