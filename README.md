# Processing Nova project for the most actively modified modules
Welcome to this repository  
Using python as a scripting language, the commits and churns in OpenStack Nova project is processed and their quantity is elaborated. this repository contains:
1. an ipynb file which was created by Jupyter Notebook, this file contains the script that was written titled "Processing Nova Project"
2. a PDF file which contains a brief report on top 12 modules in nova titled "Report.PDF"
3. this readme file which has the instuctions on how to execute the notebook 
4. Three CSV files, one that has every modifications with each commit hash, one that includes list of modifications to each file and finally, one that has changes to each module in nova subdirectory. titled "List of Modifications", "Changes to each file" and "Nova modules" respectively.
 
## Instructions on how to execute "Processing Nova Project.ipynb"
Before anything, you need to make sure that python is installed on your computer. for doing so, one of the options is to download python from [here](https://www.python.org/downloads/). after python is installed, there are four dependencies that are required for this project. here's how to install them:  
1. Pydriller: if Google Colab is the selected option to view the script, it can be easilly installed with writing "!pip install pydriller" in the first cell, with other local options, open command prompt and enter "pip install pydriller".
2. Pandas: if Google Colab is the selected option to view the script, Pandas is already installed. with other local options, open command prompt and enter "pip install pandas".
3. matplotlib: if Google Colab is the selected option to view the script, matplotlib is already installed. with other local options, open command prompt and enter "pip install matplotlib".
4. OS: this library is installed with python, so there is no need to install it after installing python.
5. datetime: this library is installed with python, so there is no need to install it after installing python.

There are multiple ways to execute this script. here on github, the script is read-only and can be examined without actually executing it. but for modifying and executing the script, after downloading the file, here are some of the options available:

1. Google Colab: Using this powerful tool that is accessible from [here](https://colab.research.google.com/), developers can run and edit ipynb files. once the file is uploaded, it will run on colab's dedicated servers
2. Jupyter Notebook: Installing Jupyter Notebook can be achived by following [this](https://jupyter.org/install) link. after installing Jupyter, the file should get uploaded on the local server that Jupyter creates and it can be easily run and manipulated ("Processing Nova Project" notebook was created using this method)
3. Visual Studio Code:  Visual studio code can be downloaded from [here](https://code.visualstudio.com/), it is easy to use and supports ipynb files, with a more familiar look than the other two options.


