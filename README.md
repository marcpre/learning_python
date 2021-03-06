# learning_python

## Install 

### Python 3.5

`python --version`

### Jupyter

#### Install

1. Install conda

```
$ wget https://repo.continuum.io/miniconda/Miniconda3-latest-Linux-x86_64.sh 
$ chmod a + x Miniconda3-latest-Linux-x86_64.sh 
$. / Miniconda3-latest-Linux-x86_64.sh 
``` 

2. Install Jupyter

```
$ conda install jupyter 
```

3. Run Jupyter
    `jupyter notebook --ip=0.0.0.0 --port=8080 --no-browser`

4. Open the URL `http://projectname-username.c9users.io:8080`

`https://learning-python-pisco.c9users.io:8080/tree?token=3fbf6012c61ec6c8b6d7716cf6ae9971f42278d113fb0861`

[https://learning-python-pisco.c9users.io:8080/tree?token=3fbf6012c61ec6c8b6d7716cf6ae9971f42278d113fb0861](https://learning-python-pisco.c9users.io:8080/tree?token=3fbf6012c61ec6c8b6d7716cf6ae9971f42278d113fb0861)
[Source - C9 - How to get jupyter notebook to run on C9?](https://community.c9.io/t/how-to-get-jupyter-notebook-to-run-on-c9/6518/3)

### Run Code

<kbd>shift</kbd> + <kbd>enter</kbd>

### Exit Edit Mode

<kbd>Esc</kbd>

Then the selector should turn blue and you can move it around.

### Show further information about variable

<kbd>Shift</kbd> + <kbd>Tab</kbd>


### Switch Mode

F.ex.:
Code to Markdown

<kbd>Esc</kbd> and then <kbd>M</kbd>

## Add Cell

Press <kbd>a</kbd>


## Autocompletion

Press <kbd>Tab</kbd>

## Install packages in Jupyter notebook

### Conda

```
import sys
!conda install --yes --prefix {sys.prefix} matplotlib
```

Hint: Install `pip install matplotlib==2.0.2`

[python 2.7 functools_lru_cache does not import although installed](https://stackoverflow.com/questions/47179433/python-2-7-functools-lru-cache-does-not-import-although-installed)

### Pip

```
import sys
!{sys.executable} -m pip install numpy
```

[https://jakevdp.github.io/blog/2017/12/05/installing-python-packages-from-jupyter/](https://jakevdp.github.io/blog/2017/12/05/installing-python-packages-from-jupyter/)




--> further at 06/067