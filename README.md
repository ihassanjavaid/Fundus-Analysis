# Fundus Analysis

A deep learning model that predicts fundus diseases

## Model Architecture

> * Base Model: ResNet152V2   
> * Flatten Layer  
> * Dense Layer: 512 Neurons, ReLU activated  
> * Dropout Layer: Rate – 0.5  
> * Dense Layer: 256 Neurons, ReLU activated  
> * Dropout Layer: Rate – 0.3  
> * Dense Layer: 128 Neurons, ReLU activated  
> * Dropout Layer: Rate – 0.5  
> * Flatten Layer  
> * Dense Layer: 3 Neurons, Softmax activated  
