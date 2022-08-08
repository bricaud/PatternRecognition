# Code for the lecture

In this folder you can find some coding examples for the Pattern Recognition course. In order to run the code you may either: 

* install Python and Jupyter notebook and run it on your computer. To install Jupyter you can follow the guidelines here [https://jupyter.org/install](https://jupyter.org/install). You need to have Python already installed. The easiest way to install Python and the notebook is with [Anaconda](https://www.anaconda.com/products/individual). 
* run the notebooks online with Binder by clicking on the small icon [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/bricaud/PatternRecognition/HEAD).
* run the notebooks online with [Google Colab](https://colab.research.google.com/). You just need to have a Google account. Colab provides access to GPUs, they are not necessary for the Pattern Recognition course but they may be useful if you want to explore further in the direction of deep learning.
* run the notebooks online using [Kaggle](https://www.kaggle.com/code). You need to register but it is free.

Description of the notebooks available in this folder:
* If you do not know much about Python and Jupyter notebooks, `NotebookTutorial.ipynb` is a tutorial on Jupyter notebook.
* `Training_a_neural_network_for_image_classification.ipynb` provides a short demo for training a (deep) neural network to classify images.
* The file `pretrained_features.ipynb` is a demo notebook explaining how to generate some features from images. It loads a pre-trained network from the TensorFlow library (TensorFlow Hub). A new set of images (Flowers pictures) is fed into the network and the ouput of one of the inner layers of this network is collected. The ouput serves as features representing each image. This notebook is inspired from this [Google Colab example](https://www.tensorflow.org/hub/tutorials/tf2_image_retraining). It is recommended to run it using Colab or your local machine. Binder has troubles with TensorFlow. 
