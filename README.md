# CIFAR-10 - Object Recognition in Images


CIFAR-10  is an established computer-vision dataset used for object recognition. It is a subset of the 80 million tiny images dataset and consists of 60,000 32x32 color images containing one of 10 object classes, with 6000 images per class. It was collected by Alex Krizhevsky, Vinod Nair, and Geoffrey Hinton.

Kaggle is hosting a CIFAR-10 leaderboard for the machine learning community to use for fun and practice. You can see how your approach compares to the latest research methods on Rodrigo Benenson's classification results page.

![CIFAR-10](https://storage.googleapis.com/kaggle-competitions/kaggle/3649/media/cifar-10.png)


## Deploy Instructions:

**Tested successfully on: Ubuntu 16.04, Python 3.5, CUDA-8.0**

Download cifar10 data:

Download Data from Kaggle, you will get **train.7z** and **test.7z**, put the two file into **/data** directory, uncompress them.

Install requirements:

``` python
pip install -r requirements
```

Mxnet need Nvidia cuda 8.0, if your computer doe not have Nvidia GPU plese comment on the line

``` python
mxnet-cu80==1.5.0
```

Running train function in the project folder:

```python
Python main.py
```

The output is a csv file contains 30,000 labels of test dataset.

