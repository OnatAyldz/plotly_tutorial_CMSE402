# Installation Guide

## Prerequisites
- Python 3.9 or higher
- Git
- Conda(https://docs.conda.io/en/latest/) can be Miniconda or Anaconda

## Installation

### 1. Repository
Clone the repository using an SSH key

### 2. Data files
The data files can already be found in the [data directory](data), but if you wish to download them yourself, they are publicly accessible
- [Palmer Penguins Dataset](https://www.kaggle.com/datasets/satyajeetrai/palmer-penguins-dataset-for-eda)
- [CO2 Emissions Dataset](https://www.kaggle.com/datasets/ravindrasinghrana/carbon-co2-emissions)

# Environment Set-up

## Option 1: Using Conda (Standard)

1. Create environment
    ```bash
    conda env create -f environment.yml -n <environment_name>
    ```

2. Activate environment
    ```bash
    conda activate <environment_name>
    ```

3. (Optional) Verify the environment by checking the packages within it
    ```bash
    conda list
    ```

4. Launch Jupyter Notebook from the terminal after activating the environment by running the following command
    ```bash
    jupyter notebook
    ```

# Usage

Once the above steps are completed, you can run each notebook in the [notebooks directory](notebooks) or you can use Binder to interact with the notebooks on the web.
