# Cats_vs_Dogs

## Architecture
The architecture of the model has 2 blocks for feature extraction in which each has :
1) Convolution Layer
2) BatchNormalizing Layer
3) Pooling Layer
4) Dropout Layer
Following which is a 64 Neuron Fully Connected layer with 2 output Neurons

## Compilation
For complilation :-
1) Optimizer = Adam
2) Loss = categorical_crossentropy
3) Metrics = accuracy

## Using EarlyStopping
Early stopping is a method that allows you to specify an arbitrary large number of training epochs and stop training once the model performance stops improving on a hold out validation dataset.

## Reducing Learning Rate on Plateau
ReduceLROnPlateau will adjust the learning rate when a plateau in model performance is detected, e.g. no change for a given number of training epochs. This callback is designed to reduce the learning rate after the model stops improving with the hope of fine-tuning model weights.

## Dataset
link : https://drive.google.com/file/d/1ZSwg45cvA5KaEXmWk-OUxIeoMKY-8hs4/view?usp=sharing
