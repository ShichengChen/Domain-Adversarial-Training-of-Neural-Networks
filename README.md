# my code is first inspired by
    https://github.com/CuthbertCai/pytorch_DANN
# Domain-Adversarial Training of Neural Networks
    https://arxiv.org/pdf/1505.07818.pdf
    implement Domain-Adversarial Training of Neural Networks by pytorch

# Dataset
- mnist
- mnist_m
- download from https://github.com/fungtion/DANN

# result
|| original paper |my implementation |
|--| ------ | ------ |
| Source only  | 0.52 |0.5|
| DANN | 0.766 |0.82~0.83|

# TODO
- try to tune toy example better
- use less parameters to train the model