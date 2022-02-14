# Theory of Algorithms 2021 (README TO BE UPDATED)

![GitHub last commit](https://img.shields.io/github/commit-activity/m/OwenKe11y/Emerging-Technologies-2021)

Repository for the Theory of Algorithms module.
<b>All work will be posted to this repository</b> 

![GitHub Title Theory Algor]()


## Introduction
For the <b>50669 -- EMERGING TECHNOLOGIES</b> module, a GitHub repository must be created that must contain the following content to a sufficent level:
 * Two Jupyter Notebooks which discuss:
   * A demonstration of Scikit-Learn and at least three interesting scikit-learn algorithms.
   * A clear and concise comparison of quantum computing and classical computing as well as an explanation of Deutsch’s algorithm and code simulating it using <i>qiskit</i>.

 * A comprehensive GitHub repository that conatins:
   * A clear and informative README.md explaining why the repository exists, what is
     in it, and how to run the notebooks.
   * A Dockerfile and/or a docker-compose.yml file that enables someone to quickly
     run your notebooks with minimal configuration. You should also include any other
     required files, such as a requirements.txt file, data files, and image files.
     
 The content of this introduction was taken directly from the project brief for ease of use and review purposes.

## Repository Content
This repository contains two comprehensive Jupyter Notebooks as well as all lab content pertaining to the module. It also includes a Dockerfile and a docker-compose.yml file that will enable the quick deployment of these notebooks with minimal configuration.

## Requirements 
* <b>Anaconda</b> Command line client (version 1.9.0)
* <b>Docker</b>
* <b>Windows Subsystem for Linux </b> (required if using a Windows Operating System)

## Running the Notebooks

### Nbviewer and Binder
You can view these notebooks in static form through the nbviewer badges. Alternatively, you can view the notebook in dynamic form through the binder badges:



| **Scikit-Learn** | [![Scikit-Learn](https://raw.githubusercontent.com/jupyter/design/master/logos/Badges/nbviewer_badge.svg)](https://nbviewer.jupyter.org/github/OwenKe11y/Emerging-Technologies-2021/blob/main/project_notebooks/scikit-learn.ipynb) [![Scikit-Learn](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/OwenKe11y/Emerging-Technologies-2021/HEAD?labpath=project_notebooks%2Fscikit-learn.ipynb)
| :------------- |:-------------|
| **Quantum Computing**           | [![Quantum Computing](https://raw.githubusercontent.com/jupyter/design/master/logos/Badges/nbviewer_badge.svg)](https://nbviewer.jupyter.org/github/OwenKe11y/Emerging-Technologies-2021/blob/main/project_notebooks/quantum-deutsch.ipynb) [![Quantum Computing](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/OwenKe11y/Emerging-Technologies-2021/HEAD?labpath=project_notebooks%2Fquantum-deutsch.ipynb) |

***

### Running on your local machine
<ol>
<li>Clone this repository using the command  
  
```
git clone https://github.com/OwenKe11y/Emerging-Technologies-2021.git
```
  
  </li>
<li>
  
  Install Anaconda3 onto your machine. Anaconda can be installed 
  [here](https://www.anaconda.com/products/individual#linux)
  
</li>
  
  <li>
    
Install JupyterLab by running the following command into a new terminal:
    
```
conda install -c conda-forge jupyterlab
```
    
  </li>
  
<li>
  
  Access the Jupyter notebooks by navigating to the project_notebooks folder using the following command:
  
  ```
  cd Emerging-Technologies-2021/project_notebooks
  ```
 </li>
  
 <li>
   
   Run the notebooks by inputting the following command:
```
jupyter-lab
``` 
   This will open a browser window where the notebooks can be accessed. NOTE: if there is an ``` Access denied ``` prompt, open your command prompt in administator mode.
   
  </li>
  
  <li>
    
 Select either the scikit-learn.ipynb or quantum-computing.ipynb notebook from the menu on the left panel to view the notebooks. 
    
  </li> 
</ol>

***

### Running using Docker 
<ol>
<li>Clone this repository using the command:  
  
```
git clone https://github.com/OwenKe11y/Emerging-Technologies-2021.git
```
  
</li>
<li>
  
  Install Docker onto your machine. Get started with Docker 
  [here](https://docs.docker.com/get-docker/)
  
 </li>
<li>
  
  Access the Jupyter notebooks by navigating to the project_notebooks folder using the following command:
  
  ```
  cd Emerging-Technologies-2021/project_notebooks
  ```
 </li>
  
<li>
  Run the docker container using:
  
  ```
  docker-compose up
  ```
  
  </li>
  
  <li>
    The following output or something similar should be seen:
    
```
    web_1  |     
    web_1  |     To access the server, open this file in a browser:
    web_1  |         file:///home/jovyan/.local/share/jupyter/runtime/jpserver-8-open.html
    web_1  |     Or copy and paste one of these URLs:
    web_1  |         http://26c9a804cf75:8888/lab?token=8aef46f6ffbd7bac47b5d6b0bfcc48718cf283d04b433940
    web_1  |      or http://127.0.0.1:8888/lab?token=8aef46f6ffbd7bac47b5d6b0bfcc48718cf283d04b433940
    
```   
Access the notebooks using any of these methods. NOTE: use the URL seen in your own terminal, not the one seen in this repository.

  </li>
  <li>
    
 Select either the scikit-learn.ipynb or quantum-computing.ipynb notebook from the menu on the left panel to view the notebooks. 
    
  </li> 
</ol>

***

## Acknowledgements 

### A markdown cheatsheet used to write the README
https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet

### List of Github badges
https://gist.github.com/tterb/982ae14a9307b80117dbf49f624ce0e8

### Shields.io for quick and easy badges for Github READMEs
https://shields.io/category/activity







