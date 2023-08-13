# how to upload python library to pip

create directory with uniq name
create empty **init**.py file
add your code into the project dir

```python
    python3 -m build
```

```python
python3 -m twine upload --repository testpypi dist/*
```

full details https://packaging.python.org/en/latest/tutorials/packaging-projects/ 