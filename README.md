# Bayesian Optimization for real-time, automatic design of face stimuli in human-centred research
[![MIT license](http://img.shields.io/badge/license-MIT-brightgreen.svg)](https://github.com/PedroFerreiradaCosta/FaceFitOpt/blob/master/LICENSE)
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/PedroFerreiradaCosta/FaceFitOpt/blob/master/FaceFitOpt_Github.ipynb#scrollTo=CO8OenmZGlZE) 
[![View the notebook](https://img.shields.io/badge/render-nbviewer-orange.svg)](https://nbviewer.jupyter.org/github/PedroFerreiradaCosta/FaceFitOpt/blob/master/FaceFitOpt_Github.ipynb)

Official script for the paper "Bayesian Optimization for real-time, automatic design of face stimuli in human-centred research".
This work is dependent from code from the [stylegan](https://github.com/NVlabs/stylegan) and the [stylegan-encoder](https://github.com/Puzer/stylegan-encoder).

![Paper Figure](./Figures/Figure2.png)

## Abstract
Investigating the cognitive and neural mechanisms involved with face processing is a fundamental
task in modern neuroscience and psychology. To date, the majority of such studies
have focused on the use of pre-selected stimuli. The absence of personalized stimuli presents
a serious limitation as it fails to account for how each individual face processing system is
tuned to cultural embeddings or how it is disrupted in disease. In this work, we propose
a novel framework which combines generative adversarial networks (GANs) with Bayesian
optimization to identify individual response patterns to many different faces. Formally,
we employ Bayesian optimization to efficiently search the latent space of state-of-the-art
GAN models, with the aim to automatically generate novel faces, to maximize an individual
subject's response. We present results from a web-based proof-of-principle study,
where participants rated images of themselves generated via performing Bayesian optimization
over the latent space of a GAN. We show how the algorithm can efficiently locate an
individual's optimal face while mapping out their response across different semantic transformations
of a face; inter-individual analyses suggest how the approach can provide rich
information about individual differences in face processing.

## Run our proof-of-concept online.
[Click here to go to GUI shared with participants](https://colab.research.google.com/github/PedroFerreiradaCosta/FaceFitOpt/blob/master/FaceFitOpt_Github.ipynb)\
You will need a webcam to run the framework. For optimal results use as a browser Google Chrome.\
Please consider staring the repo if you found it interesting.


## Citation
If you find this code useful for your research, please cite:

    @misc{costa2020bayesian,
    title={Bayesian optimization for automatic design of face stimuli},
    author={Pedro F. da Costa and Romy Lorenz and Ricardo Pio Monti and Emily Jones and Robert Leech},
    year={2020},
    eprint={2007.09989},
    archivePrefix={arXiv},
    primaryClass={cs.LG}
}
