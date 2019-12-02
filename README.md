# UMTRA on Mini-Imagenet

This is the code for applying unsupervised meta-learning [UMTRA](https://arxiv.org/abs/1811.11819) algorithm on Mini-Imagenet dataset. We build this on top of the code for [Model-Agnostic Meta-Learning for Fast Adaptation of Deep Networks (Finn et al., ICML 2017)](https://arxiv.org/abs/1703.03400).


### Dependencies
This code requires the following:
* python 2.\* or python 3.\*
* TensorFlow v1.0+
* Tensorflow-Hub (pip install --upgrade tensorflow-hub==0.7.0)

### Data
For the MiniImagenet data, see the usage instructions in `data/miniImagenet/proc_images.py`.
For applying UMTRA on other datasets use [this link](https://github.com/siavash-khodadadeh/MetaLearning-TF2.0). 

### Usage
To run the code, see the usage instructions at the top of `main.py`.
Use train=True for training and then after train is finished set train=False and test_set=True in order to use test set.
Notice that this code uses UMTRA algorithm for train.

### Contact
To ask questions or report issues, please open an issue on the [issues tracker](https://github.com/cbfinn/maml/issues).

