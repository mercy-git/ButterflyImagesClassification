# ButterflyImagesClassification

Link to the dataset:
https://drive.google.com/drive/folders/1sli-5EqmzWFBlL998sHk9tqKLnM_7n12?usp=sharing

The different species are
'zebra long wing',
 'sootywing',
 'metalmark',
 'indra swallow',
 'gold banded',
 'copper tail'
 
 Basic Model:
 We built a CNN Model to classify the chess images with the specified conditions. 

The total parameters used is 294296 which is < 300000.
Totally 3 layers are used as mentioned:
* 2 Convolution Layers
* 1 Dense Layer

We have used Adam optimizer which is the best optimizer for CNN. 

We have got the training accuracy as 81% , validation accuracy as 76% and test accuracy as 64.9% with 12 epochs. The overfitting is in acceptable range.

Advanced Model With Checkpoint and Early Stopping:
We built an advanced CNN model with 2 Convolution layers having 128 filters each and a dense layer layer having 50 hidden neurons. We have utilized 650212 parameters. We have used 10 epochs. We have also constructed the model using Checkpoint and Early stopping.

We have achieved a test accuracy of 84%.

Inference
- Built a Basic Model - 64.9% Test Accuracy
- Built an Advanced Model - 73.5% Test Accuracy
- Used Data Augmentation with the Advanced Model - 77.5% Test Accuracy
- Used Checkpoint & Early Stopping with the Advanced Model - 84% Test Accuracy
- Used Data Augmentation & Checkpoint & Early stopping together with the Advanced Model - 77.5% Test Accuracy

Building the Advanced Model with Checkpoint & early stopping has given the best test accuracy of 84%, hence we choose the same.
