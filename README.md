# CircleLoss_Keras

Naive implementation of [Circle Loss](https://arxiv.org/pdf/2002.10857.pdf), with Keras(tf backend)

Info:
- Dataset: Mnist
- Model: Keras Mnist Demo
- Optimizer: Naive SGD
- Learning_rate: default
- Feats_dim: 3, 10, 32, 128
- With_model_eval: linear softmax trained on feats
- Without_model_eval: cosine similarity between sample's feat and mean feature vector of each class
