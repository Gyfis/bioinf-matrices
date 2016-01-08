# Bioinformatics matrices for Python

This repository contains some popular bioinformatics matrices, pickled and prepared to be used in Python 2 and 3.

### Format of the matrices
All the matrices are a dictionary, with keys being a tuple of two letters. 
The '-' (dash) character corresponds to the gap.

### Using the matrices
```python
> import pickle
> pam120 = pickle.load(open('pam120.p', 'rb'))
> print(pam120['A', '-'])
-8
```
