# unet_pytorch
Unet Pytorch course project for course CS-E4890, project by Jouko Kinnari

## Setting up
- Fetch repository on your computer
- Install Jupyter Notebook and Conda
- Set up Conda environment with provided .env file: `conda env create -f environment.yml`
- Install environment to Jupyter Notebook: `python -m ipykernel install --user --name unet --display-name "Python (unet)"`
- Download [Kitti semantic segmentation data](http://www.cvlibs.net/datasets/kitti/eval_semseg.php?benchmark=semantics2015) and extract
- Start up Jupyter Notebook and load the notebook
- Adjust the paths to data according to where you downloaded the Kitti data
- Run each cell in the model.

The notebook contains ample comments for easy follow-up.

## How to view the implementation without setting up the Jupyter Notebook environment?
Click the [unet.ipynb](https://github.com/jkinnari/unet_pytorch/blob/master/unet.ipynb) file.

## On performance of the model
The model requires improvements for satisfactory performance (including but not limited to data augmentation and tiling of input data). Please don't use this as a reference as such.
