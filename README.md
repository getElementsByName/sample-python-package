# sample-python-package

## prerequisite
- conda


## setup env by conda

```
conda env create -f environment.yml
```

```
conda env update -f environment.yml
```

### (if the local environment is windows) vscode setting for conda
- `settings.json`
```
    "terminal.integrated.shellArgs.windows": ["/K", "conda activate samplepython"],
    "terminal.integrated.shell.windows": "C:\\Windows\\System32\\cmd.exe"
```

## install the package to local
```
pip install -e .
```

```python
import sample_python_package_getelementsbyname
```