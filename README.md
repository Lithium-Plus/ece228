# Retina OCT image classification
Course project for ECE 228, group 3. </br>
Group Members: Zheng Li, Songquan Liu, Ya Xiong
## Dataset
The OCTMNIST dataset is a part of the MedMNIST dataset [1]. This dataset contains 109,309 retina optical coherence tomography (OCT) images. There are four classes in the dataset, Figure 1 shows an example of the four classes of imagesa, which are choroidal neovascularization (CNV) (37,206 images), diabetic macular edema (DME) (11,349 images) , drusen (8,617 images) and normal (51,140 images). In the test set, there are 500 images for each class. The image size is 28 × 28.  
![alt text](https://github.com/Lithium-Plus/ece228/blob/main/retina_img.jpg)
## Installation
Environment can be installed by running conda create --name <env> --file requirements.txt</br>
## Training & Evaluation
Use the octmnist_vit.ipynb to train and evaluate the vision transformer model.
## Source
[1] Jiancheng Yang, Rui Shi, Donglai Wei, Zequan Liu, Lin Zhao, Bilian Ke, Hanspeter Pfister, Bingbing Ni. "MedMNIST v2: A Large-Scale Lightweight Benchmark for 2D and 3D Biomedical Image Classification". arXiv preprint arXiv:2110.14795, 2021.
