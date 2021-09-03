# nlp-machine-transalation
## Introduction
Here you will build a deep neural network that functions as part of an end-to-end machine translation pipeline. This pipeline will accept English text as input and return the French translation.

# Setup

This project requires GPU acceleration to run efficiently.

## Installation
- Python 3
- NumPy
- TensorFlow 1.x
- Keras 2.x

## Below are the step
- Create (and activate) a new environment with Python 3.5 and the numpy package.

`conda create --name nlp-machine-transalation python=3.5 numpy`
`source activate nlp-machine-transalation`

- Install/Update TensorFlow`
`pip install tensorflow==1.1 -U

- Install/Update Keras
`pip install keras -U`

- Switch Keras backend to TensorFlow.
`KERAS_BACKEND=tensorflow python -c "from keras import backend"`