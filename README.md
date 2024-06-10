## Implementing Transformer in PyTorch: Full Source Code and Notebook Playground
- Building a Python package for transformer. 
- Building source code for each class and function,
- Playground with the notebook files.

## Create Python environment with venv
```
# Navigate into the project directory
    cd path/to/your/project 

# Create Python environment, eg. named ".myenv"
    python -m venv .myenv 
    # (For Linux, MacOS, you may need to used `python3` instead of `python`)

# Activate "transformer" environment
    .myenv\Scripts\activate  # For Window
    source myenv/bin/activate # For Linux, MacOS

# Deactivate
    deactivate
```

## Create Python environment with conda
```
# Navigate into the project directory
cd path/to/your/project 

# Create Python environment, eg. named "transformer"
conda create -n transformer python=3.10

# Activate "transformer" environment
conda activate transformer

# Deactivate
conda deactivate
```

## Install the required dependencies: 
    - ```pip install -r requirements.txt```
    - Adapt the first lines in requirements.txt for Pytorch usage with CPU or GPU:
        - For GPU, install locally Pytorch. Visit https://pytorch.org/get-started/locally/ Update the following URL to download and install appropriate Torch and Cuda for your system, e.g.: https://download.pytorch.org/whl/cu118
        - For CPU, install Pytorch from PyPI

## Launch training
```
python train.py
```

## Playground with inference
- After obtaining the trained model in './models', playground with "nb_inference.ipynb"

## Playgroud with all other notebooks
- For each functions/classes, playground with the coresponding notebooks in './notebooks/' 