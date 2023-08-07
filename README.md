# Clasification-X-ray-pneumonia

Classification of chest x-ray images with pneumonia and normal using the [kaggle](https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia) dataset [Chest X-Ray Images (Pneumonia)](https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia), in which in this case tensorflow is used, the model is saved in .h5 and .tflite and the model is evaluated. 

<p align="center">
  <img src="README-images\evaluation-model.PNG" alt="Step2">
</p>


<p align="justify">
Google Colab is used to train the model where to download the dataset from Google Colab, as it is in Kaggle, you must first go to the configuration of the Kaggle account and click on the API "Create New Token" where a file "kaggle.json" will be downloaded. This file must be saved in a folder where you want to download the dataset.
</p>

<p align="center">
  <img src="README-images\kaggle-api.PNG" alt="Step2">
</p>

<p align="justify">
To download the dataset copy the API command to be able to download it 
</p>

<p align="center">
  <img src="README-images\api-dataset.PNG" alt="Step2">
</p>

<p align="justify">
Indicate the folder where the kaggle.json is located and download it with the api command of the dataset
</p>

<p align="center">
  <img src="README-images\kaggle-download.PNG" alt="Step2">
</p>

<p align="center">
  <img src="README-images\colab_directory.PNG" alt="Step2">
</p>

<p align="justify">
loss and accuracy are observed
</p>

<p align="center">
  <img src="README-images\accuracy-loss.PNG" alt="Step2">
</p>

<p align="justify">
The confusion matrix is observed 
</p>

<p align="center">
  <img src="README-images\confusion-matrix.PNG" alt="Step2">
</p>


The model is evaluated
<p align="center">
  <img src="README-images\evaluation-model.PNG" alt="Step2">
</p>

## Steps to implement it

1. Use Dockerfile 
2. Use virtual enviroments and apply  requirements.txt 
```python
pip install -r requirements.txt
```