Early stopping is a form of regularization used to avoid overfitting on the training dataset. Early stopping keeps track of the validation loss, if the loss stops decreasing for several epochs in a row the training stops.


Underneath is a plot from the example notebook, which shows the last checkpoint made by the EarlyStopping object, right before the model started to overfit. It had patience set to 20.

![image](https://github.com/saakshiappanna/dl_assignment/assets/107665369/b66dca8b-26a5-4171-a8bf-c85417642fdf)
