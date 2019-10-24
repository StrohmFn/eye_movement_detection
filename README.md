# Eye Movement Detection
This repository contains all relevant code that is used in this [PAPER](https://github.com/StrohmFn/eye_movement_detection/blob/master/Gaze_Detection.pdf).
The core contributions of the paper are the evaluation of an attention based CNN to classify eye movement types and
an approach for supervised pre-training.

The folder 'preprocessing' contains one jupyter notebook for each used data set.
Download the data sets ([GazeCom](http://michaeldorr.de/smoothpursuit/), [Hollywood2](http://www.coxlab.org/resources/hw2_eye_movement/), [Lund2013](https://github.com/richardandersson/EyeMovementDetectorEvaluation)) and use their respective jupyter notebook to process them for usage.

The folder 'neural_network' contains a jupyter notebook to train fully supervised architectures,  pre-trained models and the autoencoder architectures. The notebook 'neual_networks' just contains different neural network architectures that were used in different experiments of the paper and can be used in the other notebooks for training.
