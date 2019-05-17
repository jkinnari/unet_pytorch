# unet_pytorch
Unet Pytorch course project for Aalto University course CS-E4890, project by Jouko Kinnari
## Setting up
- Fetch repository on your computer
- Install Jupyter Notebook and Conda
- Set up Conda environment with provided .env file: `conda env create -f environment.yml`
- Install environment to Jupyter Notebook: `python -m ipykernel install --user --name unet --display-name "Python (unet)"`
- Download [Kitti semantic segmentation data](http://www.cvlibs.net/datasets/kitti/eval_semseg.php?benchmark=semantics2015)
- Start up Jupyter Notebook and load the notebook
- Adjust the paths to data according to where you downloaded the Kitti data
- Run each cell in the model.

The notebook contains ample comments for easy follow-up.

## How to view the implementation without setting up the Jupyter Notebook environment?
A HTML rendering of the notebook is also available in this repository to view the notebook without starting Jupyter Notebook. The HTML file is too big to show on Github directly. Please [download the html file](https://github.com/jkinnari/unet_pytorch/raw/master/unet.html) on your computer and open it in a web browser.
