# QCTO---Workplace

This README file provides instructions on how to recreate the Python environment for this project using Anaconda.

Prerequisites
Anaconda installed on your system. You can download and install it from Anaconda Distribution.
Steps to Recreate the Environment
Clone the repository:

git clone https://github.com/yourusername/crwp.git
cd crwp
Create the Conda environment:

Create a new Conda environment with Python (specify the desired version if needed):

conda create --name crwp-env python=3.x
Replace 3.x with the version of Python you need (e.g., 3.8).

Activate the environment:

conda activate crwp-env
Install dependencies:

Install the required packages from the requirements.txt file:

pip install -r requirements.txt
Verify the installation:

Ensure all packages are installed correctly by checking the installed packages:

conda list
Additional Commands
Deactivate the environment:

To deactivate the current environment, use:

conda deactivate
Remove the environment:

If you need to remove the environment:

conda remove --name crwp-env --all
Replace crwp-env with the name of the environment you want to remove.

Troubleshooting
Common issues:

If you encounter any issues related to package conflicts, try updating Conda:

conda update conda
If you still face issues, you can create a new environment from scratch and install the required packages manually.

Data set : https://www.kaggle.com/datasets/vakhariapujan/avocado-prices-and-sales-volume-2015-2023/code
