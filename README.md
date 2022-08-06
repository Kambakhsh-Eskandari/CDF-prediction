# CDF-prediction
A deep learning model to predict the cdf of an image

  The architecture of the model is represented by the image down below,
  keep in mind that since the cdf of a grayscale image has 256 values thus we expect a model which gives us a vector of 256 values as output.
  ![image_2022_01_16T10_00_32_319Z](https://user-images.githubusercontent.com/83129774/183244900-e07a4efd-9ca5-4941-8d97-79ec505663a8.png)

this model is train on a costume dataset and we should keep in mind that tensorflow only accepts data as tensors thus our data should always be represented as 
(B, W, H, C). 
