# conda-environments


### List environments

```conda env list```


### To create an environment with a specific version of Python:

```conda create -n myenv python=3.9```


### Export your active environment to a new file:

```conda env export > environment.yml```

### Create the environment from the environment.yml file:

```conda env create -f environment.yml```
