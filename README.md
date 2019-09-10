# Adversarial Attacks on Neural Automated Essay Scoring Systems 
# Michael Lee & Micah Nickerson

# Harvard University Summer
# CSCI-S-89A- FINAL PROJECT

We evaluate the success of NLP Adversarial Techniques against an Automated Essay Scoring System "Black Box."

**Part 1 - Creating a Dual Scoring CNN system, as a Black Box to test.**
* See:
    * AES Blackbox- Dual CNN.ipynb

**Part 2 - Generating Adversarial Attacks.**
* See:
    * Adversarial Attack Perturbation Creator.ipynb
    * Anchor Model using AES CNN Model.ipynb

**Part 3 - Applying the attacks, and evaluating the results.**
* See last section of:
    * AES Blackbox- Dual CNN.ipynb

### Prerequisites

* All libraries required are listed in built with below.

* GloVe Embedding Vector sets (by Stanford University) must be downloaded into Data set/GloVe

### Installing

* Final Blackbox H5 models are available upon request

* Recommended to run code on Google colab

* Notebook *"AES Blackbox..."* is designed to both train the black box, evaluate the black box, and adversarially attack the black box.
The input line specifying this function is in FIRST code section of notebook *"AES Blackbox..."*.

## Built With

* [Python 3.7.3](https://www.python.org/downloads/release/python-370/) - Interpreted language utilized 
* [Google Colab](https://colab.research.google.com) - Neural Network written and Trained on GPU at Google Colab
* [Keras 1.14.0](https://keras.io/) - Deep Learning Neural Network Architecture
* [Tensorflow 2.0](https://www.tensorflow.org/) - Neural Network Backend by Google 
* [Anaconda 3](https://www.anaconda.com/distribution/) - Primary distribution, library sources used
* [Jupyter Notebook](https://jupyter.org/) - Local Notebook Host
* [Matplotlib](https://matplotlib.org/) - Visualization library
* [Numpy](https://numpy.org/) - Array and matrix library
* [Pandas](https://pandas.pydata.org/) - Data Frame library

## Contributing

Please contact us for details on our code of conduct, and the process for submitting pull requests to us.

## Versioning

Versioning has not been established - project is to be published once.

## Authors

* **Michael Lee** - *Initial work* - mil726@g.harvard.edu - [cello1357](https://github.com/cello1357) -  Harvard University Extension
* **Micah Nickerson** - *Initial work* - min021@g.harvard.edu - [mjnickerson](https://github.com/mjnickerson/) - Harvard University Extension

## License

This project is licensed under the MIT License.

## Acknowledgments

* Thank you to Professor Zoran Djordjevic and the TA staff of Harvard University Summer CSCI-S89A for their input and support.

* This project is based on a foundational paper by David Lang and Klint Kanopka at Stanford University. 

    *  Lang, K. K. a., Adversarial Examples for Neural Automatic Essay Scoring Systems. Stanford University cs224n/15720509, (2019).

* Also thanks to Yoon Kim for his work on classifying sentences with CNN, which was a primary reference.

    * Kim, Yoon. Convolutional neural networks for sentence classification. arXiv preprint
      arXiv:1408.5882, (2014).
