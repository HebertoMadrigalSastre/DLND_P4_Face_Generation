
## Project Overview

It is the Face Generation project from the Deep Learning Nanodegree program of Udacity. This project is based on Generative Adversarial Networks (GANs) and it can be used to generate new faces using celebrity images.

## Project Instructions

### Instructions

1. Clone the repository and navigate to the downloaded folder.
	
	```	
	git clone https://github.com/HebertoMadrigalSastre/DLND_P4_Face_Generation.git

	cd DLND_P4_Face_Generation
	```


2. Verify that you have already installed the required Python packages:

	- jupyter notebook
	- pytorch

3. Download the [CelebFaces Attributes Dataset (CelebA)](https://s3.amazonaws.com/video.udacity-data.com/topher/2018/November/5be7eb6f_processed-celeba-small/processed-celeba-small.zip). Unzip the folder and place it in the DLND_P4_Face_Generation repository, at the location `processed_celeba_small`.


3. Open the notebook dlnd_face_generation.ipynb file.
	
	```
	jupyter notebook dlnd_face_generation.ipynb
	```

The dataset is already included within the repository

## Project content

Content: 

- Pre-processed Data
- Create a DataLoader
- Define the Model
    - Discriminator
    - Generator
- Initialize the weights of your network
- Build complete network
- Discriminator and Generator Losses
- Optimizers
- Training
    - Training Loss
- Generator samples from training


## (Optionally) Accelerating the Training Process

If the execution of the code is taking too long, you'd like to use a GPU. You can use Amazon Web Services to launch an EC2 GPU instance.