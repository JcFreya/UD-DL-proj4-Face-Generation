## GANs Project: Face Generation
### Getting the project files

The project files are located in the Project Workspace and include the following files:

* **`dlnd_face_generation_starter.ipynb`**
* **`README.md`**
* **`requirements.txt`**
* **`tests.py`**
* **`processed-celeba-small.zip`**

### Instructions

Open the notebook file, `dlnd_face_generation_starter.ipynb` and follow the instructions. This project is organized as follows:

* **Data Pipeline**: implement a data augmentation function and a custom dataset class to load the images and transform them.
* **Model Implementation**: build a custom generator and a custom discriminator to make your GAN
* **Loss Functions and Gradient Penalty**: decide on loss functions and whether you want to use gradient penalty or not.
* **Training Loop**: implement the training loop and decide on which strategy to use 


Building a deep learning model is an iterative process, and it's especially true for GANs!

# Installation:

1. For running this project on your local computer, first make sure you have git by typing `git --version` on cmd, if version number appears that means you have git installed. Go ahead and clone the repository:

```
git clone https://github.com/JcFreya/UD-DL-proj4-Face-Generation.git
cd UD-DL-proj4-Face-Generation

```
2. Now please open the file with filename: dlnd_face_generation.ipynb


# Dependencies:

- Make sure to create an environment for running this project using conda (you can install [Miniconda](http://conda.pydata.org/miniconda.html) for this

- Once you have Miniconda installed, please make an environment for the project like so: 
```
conda create --name face_generation python=3.6
activate face_generation

```
- Install Pytorch: 
```
conda install pytorch -c pytorch
pip install torchvision
```

- Install a few required pip packages, which are specified in the requirements text file.

`pip install -r requirements.txt`
