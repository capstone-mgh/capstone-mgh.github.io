![logos](images/logo5.png)

# Machine Learning

Our ML contribution consists of two parts:

- An ML pipeline implemented in Keras and Theano that allows for live ML predictions of nodule segmentations.
- A convolutional neural network model (informally called ShapeNet) that generates malignancy scores based on the user-inputed segmentation shape. 

## ML Pipeline

![ml-pipeline](images/ml/3.png)


## ShapeNet: a shape-based ConvNet for Malignancy Prediction

### Generated Masks

![gif-1](images/ml/1.gif)
![gif-2](images/ml/2.gif)



### Convolutional Network Architecture

![ml-architecture](images/ml/1.png)

### Loss across Epochs
![loss](images/ml/2.png)

### Residual Plot of ShapeNet
![loss-shapenet](images/ml/residual_plots_CNN_2.png)

### Residual Plot of Random Noise
![loss-noise](images/ml/residual_plots_CNN.png)

[Next](http://sakeviewer.com/demo.html)
