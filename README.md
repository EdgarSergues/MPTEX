### Build Documentation

You can build the documentation locally by installing the documentation Conda environment:
```
conda env create -f docs/environment.yaml
```

activating the environment:
```
conda activate sphinx_MPTEX
```

Build the documentation on Windows by running:

```
sphinx-build docs _build/html --builder=html --jobs=auto
```