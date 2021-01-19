# Overfitting-Problem
 A model that learns the training dataset too well, performing well on the training dataset but does not perform well on a hold out sample.
 
 In this repository i will show how the overfitting problem occur in neural network and how model perform excellent on training dataset but worst on validation dataset.
 
 <b>Here is the dataset</b><br>
 This is the sklearn moon dataset with 0.26 noise 
 
 <p align="center">
  <img src="https://github.com/vedantgoswami/Overfitting-Problem/blob/main/Overfitting/dataset.png"> 
  </p>
  
  <b> Model Summery:</b>
  <p align="center">
  <img src="https://github.com/vedantgoswami/Overfitting-Problem/blob/main/Overfitting/model.PNG"> 
  </p>
  
  <b> Now after training this model after 4000 epochs we have the following trend of training and validation dataset</b>
    <p align="center">
  <img src="https://github.com/vedantgoswami/Overfitting-Problem/blob/main/Overfitting/overfitting.png"> 
  </p>

 <p align="center"> The above Plot clearly shows that the model had a very low loss on training dataset but for validation dataset the loss increases after 500 epochs.This proofs that model was overfitting.</p>
  
