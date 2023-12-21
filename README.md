<a name="readme-top"></a>

<br />
<div align="center">
  <a href="https://github.com/caraka-id/machine-learning">
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width="100" height="100" alt="python-logo"/>
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/opencv/opencv-original.svg"  width="100" height="100"  alt="tensorflow-logo"/>

  </a>

<h3 align="center">Data Pre-Processing</h3>

  <p align="center">
    Cleaning, Resize, and Augmentation on Datasets
  </p>
</div>

<br />

## Overview

<p align="justify">
<img src="images/bali_datasets.png" width=32.5% alt="bali">
<img src="images/sunda_datasets.png" width=32.5% alt="sunda">
<img src="images/lampung_datasets.png" width=32.5% alt="lampung>
  
This repository constitutes an integral component of the machine learning workflow, serving as the primary source of data for training the model. It contains meticulously curated datasets that have undergone thorough cleaning processes.
</p>

## Workflow

<img src="images/Caraka Workflow.png" width=100% alt="workflow">

<br>

* `Gathering and Creating Datasets` :
We gather data from <a href="https://www.kaggle.com/datasets/anggitpambudihutomo/aksara-lampung-handwriting-dataset"> Kaggle </a> and additionally create our own dataset by hand-drawing Indonesian scripts.
* `Image Cleaning`: We employ the OpenCV-Python library to perform data preprocessing tasks such as cleaning, grayscale conversion, binarization, and resizing.
* `Augmentation` : We utilize the `imgaug` library to apply rotation and shear transformations to images within a canvas, adapting the size based on input parameters.
* `Train/Val splits`: We partition the datasets using an 80:20 ratio.

## Contributors

|Name |Bangkit ID| University|
|-----|----------|-----------|
|<a href="https://www.linkedin.com/in/jonekaa">Jonathan Eka     | M244BSY0067| Universitas Kristen Petra|
|<a href="https://www.linkedin.com/in/gathaaa">Agatha Angelina  | M244BSX0068| Universitas Kristen Petra|
|<a href="https://www.linkedin.com/in/edinaalana">Edina Alana   | M296BSX1153| Universitas Pembangunan Nasional Veteran Jawa Timur|
