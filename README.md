<img src="https://github.com/kylecurtis/interactive-python/blob/main/images/python-bg.jpeg?raw=true">

# Interactive Python Notebook

![Static Badge](https://img.shields.io/badge/Python_Version-3.12+-yellow) ![Static Badge](https://img.shields.io/badge/Work_In_Progress-WIP-orange)

<br>

Interactive Jupyter notebooks for learning all things Python.

[Non-interactive Preview (Web Browser Only)](https://github.com/kylecurtis/interactive-python/blob/main/notebook.ipynb)


<br>

## Requirements

- [Python (3.12 or higher)](https://www.python.org/downloads/)

<br>

## Setup

## Clone the repo

```bash
git clone https://github.com/kylecurtis/interactive-python.git
```

<br>

## Change root directory to the repo

```bash
cd /path/to/interactive-python
```

<br>

## Create the venv

```bash
python -m venv venv/
```

<br>

## Source the venv:

- Windows
 
```bash
# In cmd.exe
venv\Scripts\activate.bat
# In PowerShell
venv\Scripts\Activate.ps1
```

- Linux / MacOS / Git Bash 
```bash
source ./venv/bin/activate
```

<br>

## Install dependencies

```bash
pip install -r requirements.txt
```

<br>

## Run the notebook

Because of an [issue](https://github.com/kylecurtis/interactive-python/issues/1) regarding the table of contents navigation, the recommended way to view the notebook is with the browser by running jupyter lab or notebook in the terminal:

```bash
jupyter lab
```
