# Installation Instructions

### Step 1: Install conda
Start by installing conda onto your computer. You can follow the instructions from the [conda site](https://docs.conda.io/projects/conda/en/stable/user-guide/install/index.html). Feel free to download either Miniconda or Anaconda Distribution -- both are sufficient and we can talk about the differences during class!

### Step 2: Install Git
Install Git if needed following the instructions [here](https://github.com/git-guides/install-git). Be sure to check if Git is already installed on your machine and, if not, follow the instructions for your operating system.

### Step 3: Download and set up environment
From your terminal, clone the Python_Math_Review repository:

`git clone https://github.com/Fuchan2004/Python_Math_Review.git`

Change your current working directory to the location to which you downloaded Python_Math_Review (The repository should have been cloned into a directory named "Python_Math_Review" located in whichever directory you ran the git clone command from):

`cd /Users/zoeaarons/Documents/Documents/Python_Math_Review/`

Create conda environment from the included environment.yml file:

`conda env create -f environment.yml`

> Note: These instructions should hopefully work on all operating systems. However, if you are using Windows and this does not work, check out the [Anaconda Navigator](https://docs.anaconda.com/navigator/tutorials/manage-environments/#importing-an-environment)

Once the environment is done building, check that the new environment was installed correctly:

`conda info --envs`
