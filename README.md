# Introduction
This repository helps build python environment to use deep learning libraries such as PyTorch, Transformers etc...

# Set up
To create a virtual environment
```
C:\Users\amrul\AppData\Local\Programs\Python\Python39\python.exe -m venv C:\Users\amrul\pyvirtualenvs\dl-python39
```

Activate virtual environment
```
C:\Users\amrul\pyvirtualenvs\dl-python39
```

Install pip-tools
```
python -m pip install pip-tools
```

Compile requirements.in
```
pip-compile
```

Install libraries listed in requirements.txt
```
pip-sync
```