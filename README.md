# apex_code

### Generate distribution archive
```bash
python3 -m pip install --upgrade build
```
```bash
rm dist/*
```
```bash
python3 -m build
```

### Upload the distribution archive
```bash
python3 -m pip install --upgrade twine
```
```bash
python3 -m twine upload dist/*
```

### Install
```bash
pip install apex_code
```

### Tests
```bash
python3 -m unittest discover -s tests
```


### Usage
```python
from apex_code.math.linear_algebra.Matrix import Matrix

# Create matrix object
my_matrix = Matrix([1,2,3],[4,5,6])

# View docs
help(Matrix)
```
