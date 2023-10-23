# pypackage-sample
How to create a python package



## Install
```
python setup.py sdist
pip install .
```

## Pypi config

Please put this file at $HOME with a name .pypirc



## Upload
```
pip install twine
python -m twine upload dist/*
```