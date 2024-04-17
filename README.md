# 3D Cone Surface Fitting with Numpy, Python 3.11, and Plotly

This repository contains a Jupyter Notebook (`main.ipynb`) that demonstrates the generation of a 3D cone, addition of Gaussian noise to it, and fitting an appropriate 3D surface to it using the least squares method. 

## Problem Statement

The task involves generating a 3D cone, adding Gaussian noise to it, and fitting a suitable 3D surface to the noisy data points using the least squares method.

## Solution Summary

1. **Generate 3D Cone**: 
   - A 3D cone is generated with a specified number of points.

2. **Add Gaussian Noise**: 
   - Gaussian noise is added to the generated cone to simulate real-world data.

3. **Fit 3D Surface**: 
   - The noisy data points are fitted with an appropriate 3D surface using the least squares method.

## Requirements

- Python 3.11
- Jupyter Notebook
- Numpy
- Plotly

## Installation and Setup

### 1. Install Python 3.11

Download and install Python 3.11 from the [official website](https://www.python.org/downloads/).

### 2. Install Conda (Optional)

If you prefer managing Python environments with Conda, you can install Miniconda or Anaconda.

- **Miniconda**: [Installation instructions](https://docs.conda.io/projects/conda/en/latest/user-guide/install/index.html)
- **Anaconda**: [Installation instructions](https://docs.anaconda.com/anaconda/install/index.html)

### 3. Create Python Environment (Optional)

If you face any issues or version mismatches with Python packages, you can create a separate Python environment using Conda. Run the following command:

```bash
conda create -n cone-fitting python=3.11 numpy plotly jupyter
```
Activating the Environment 

```bash
conda activate cone-fitting
```
### 4. Clone the Repository
Clone the repository to your local machine:

```bash
git clone https://github.com/Sarthak-1520/Nozzel_sim.git
```
Navigate to the repository directory:

```bash
cd 3d-cone-surface-fitting
```
Usage
Launch Jupyter Notebook:

```bash
jupyter notebook
```
Open the main.ipynb notebook in your browser.

Follow the instructions in the notebook to execute each cell and generate the 3D cone, add Gaussian noise to it, and fit the 3D surface using the least squares method.

Results
After running all the cells in the notebook, you should see visualizations displaying the original cone, noisy data points, and the fitted surface and the appropriate metrics. You can interact with the 3D plots to explore the results further.



