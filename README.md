# Road Segmentation with U-Net Over Aerial Image

This dataset is taken from [Kaggle]([https://pages.github.com/](https://www.kaggle.com/datasets/balraj98/massachusetts-roads-dataset))

###### Data Explanation

The Massachusetts Roads Dataset consists of 1171 aerial images of the state of Massachusetts. Each image is 1500×1500 pixels in size, covering an area of 2.25 square kilometers. We randomly split the data into a training set of 1108 images, a validation set of 14 images and a test set of 49 images. 


You can get the dataset with Kaggle and Colab integration by matching Colab with your Drive.
###### Usage

The study was developed over Colab. In order to avoid the error caused by the python version in Colab, the following lines of code should be run in the run:

```
!pip install --upgrade opencv-python
!pip install --upgrade albumentations

```

