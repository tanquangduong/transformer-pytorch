## Implementing Transformer in PyTorch: Full Source Code and Notebook Playground
- Building a Python package for transformer. 
- Building source code for each class and function,
- Playground with the notebook files.

## Installation
0. Navigate into the project directory: 
```
cd transformer-pytorch
```
1. Create Python conda environment, eg. named "transformer": 
```
conda create -n transformer python=3.10
```
2. Activate ENV_NAME environment: 
```
conda activate transformer
```
3. Install the required dependencies: 
    - ```pip install -r requirements.txt```
    - Adapt the first lines in requirements.txt in CPU or GPU:
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