# Retina OCT image classification
Course project for ECE 228, group 3. In this project, we trained and evaluated three models on the OCTMNIST dataset: modified AlexNet, ResNet18 and vision transformer. We compared the performance of these three models and vision transformer performs the best.  </br> 
Group Members: Zheng Li, Songquan Liu, Ya Xiong
## Dataset
The OCTMNIST dataset is a part of the MedMNIST dataset [1]. This dataset contains 109,309 retina optical coherence tomography (OCT) images. There are four classes in the dataset, Figure 1 shows an example of the four classes of imagesa, which are choroidal neovascularization (CNV) (37,206 images), diabetic macular edema (DME) (11,349 images) , drusen (8,617 images) and normal (51,140 images). In the test set, there are 500 images for each class. The image size is 28 × 28.  
![alt text](https://github.com/Lithium-Plus/ece228/blob/main/retina_img.jpg)
## Installation
Setup the required environment:
```conda create --name <env> --file requirements.txt```

Install the medmnist dataset:
```pip install medmnist```
## Code Structure
There are three training and evaluation scripts of OCTMNIST.

* AlexNet.ipynb: train and evaluate the modified AlexNet model.
* ResNet.ipynb: train and evaluate the ResNet18 model.
* octmnist_vit.ipynb: train and evaluate the vision transformer model.
  
## Source
[1] Jiancheng Yang, Rui Shi, Donglai Wei, Zequan Liu, Lin Zhao, Bilian Ke, Hanspeter Pfister, Bingbing Ni. "MedMNIST v2: A Large-Scale Lightweight Benchmark for 2D and 3D Biomedical Image Classification". arXiv preprint arXiv:2110.14795, 2021.
