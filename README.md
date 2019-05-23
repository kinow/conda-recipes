# conda-recipes

Misc conda recipes.

General prerequisites:

```bash
$ conda update conda
$ conda install conda-build
$ conda create -n testing-build
$ source activate testing-build
```

Example build command:

```bash
$ conda-build --debug . # . is the local dir, or choose one of the folders in this repo
```
