# Setup

Note: python version should be `3.12.3`

`python3 -m venv venv`

`source venv/bin/activate`

(within venv) `pip install -r requirements.txt`

(within venv) `pip install jupyter ipykernel`

(within venv) `python -m ipykernel install --user --name=venv --display-name "Python (venv-exam-prep)"`

This should output
`Installed kernelspec venv in /home/<user>/.local/share/jupyter/kernels/venv`

Open vscode command palette, find "Python: Select Interpreter" then choose the interpreter inside venv

on macOS/linux will be ./myenv/bin/python

on windows will be .\myenv\Scripts\python.exe

Then use this to run the cells in `main.ipynb`