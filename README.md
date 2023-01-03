[![PyPI](https://img.shields.io/pypi/v/CausalEGM)](https://pypi.org/project/CausalEGM/)
[![Travis (.org)](https://img.shields.io/travis/kimmo1019/CausalEGM)](https://app.travis-ci.com/github/kimmo1019/CausalEGM)
[![Documentation Status](https://readthedocs.org/projects/causalegm/badge/?version=latest)](https://causalegm.readthedocs.io)

CausalEGM - A general causal inference framework by encoding generative modeling
================================================================================

<img align="left" src="https://github.com/SUwonglab/CausalEGM/blob/main/model.jpg" width="300">
   
**CausalEGM** is a general causal inference framework for estimating causal effects by encoding generative modeling, which can be applied in both discrete and continuous treatment settings. 

CausalEGM simultaneously decouples the dependencies of confounders on both treatment and outcome and maps the confounders to the low-dimensional latent space. By conditioning on the low-dimensional latent features, CausalEGM can estimate the causal effect for each individual or the average causal effect within a population.

CausalEGM was developed with Python and TensorFlow, we provide a **console program** to run CausalEGM directly without running any Python script. For more information, checkout the **Document [here](https://causalegm.readthedocs.io/)**.

Note that a GPU is recommended for accelerating the model training. However, GPU is not a must, CausalEGM can be installed on any personal computer (e.g, Macbook) or computational cluster with CPU only.


## Main Reference

If you find CausalEGM useful for your work, please consider citing our [paper](https://arxiv.org/abs/2212.05925):

Qiao Liu, Zhongren Chen, Wing Hung Wong. CausalEGM: a general causal inference framework by encoding generative modeling[J]. arXiv preprint arXiv:2212.05925, 2022.

## Support

Found a bug or would like to see a feature implemented? Feel free to submit an [issue](https://github.com/SUwonglab/CausalEGM/issues/new/choose). Have a question or would like to start a new discussion? You can also always send us an [e-mail](mailto:liuqiao@stanford.edu?subject=[GitHub]%20CausalEGM%20project). Your help to improve CausalEGM is highly appreciated! For further information visit [https://causalegm.readthedocs.io/](https://causalegm.readthedocs.io/).

