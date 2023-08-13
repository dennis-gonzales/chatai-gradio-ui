# About the project

Chat Messenger App

## Getting Started

```bash
conda create --prefix ./env
```

```bash
pip install -r requirements.txt
```

## Activate

```bash
# use `conda info --envs` to list all your envs
conda activate /PATH_TO_PROJ/env
```

### Run the App

```bash
gradio app.py
# Note: you can also do `python app.py``, but it won't provide the automatic reload mechanism.
```

### Run Jupyter Notebook

```bash
jupyter notebook
```

### Run Jupyter Notebook in VSCode

Open the Jupyter Notebook file and make sure that the correct [kernel](#selecting-the-correct-kernel) is selected.

## Deactivate

```bash
conda deactivate
```

## Troubleshooting

### Selecting The Correct Kernel

Make sure you've selected the **correct environment** to run on.

e.g. `python <python-version> (conda) .\env\python.exe`
