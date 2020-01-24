# Runtime reproducibility with Conda and Jupyter

## Conda
*[Online presentation](https://maxibor.github.io/conda-presentation) - [PDF](https://github.com/maxibor/conda-presentation/raw/master/presentation_conda.pdf)*

[conda](https://maxibor.github.io/conda-presentation ':include :type=iframe width=100% height=600px')

## Jupyter

[Jupyter](https://jupyter.org) notebooks are a form of electronic notebooks that can combine both code and notes (similar to [Rmarkdown](https://rmarkdown.rstudio.com)).
They are language agnostic (can be used with different languages, like R, Python, Julia) and are easily deployed on remote servers.  
Also, jupyter notebooks are [rendered by default on Github](https://github.com/rrdm-shh/jupyter-notebook/blob/master/rrdm-notebook.ipynb), like markdown files.

Jupyter is already pre-installed in the course conda environment. We just need to activate this environment: 

```bash
conda activate rrdm-shh
```

Let's first check that jupyter is installed

```bash
conda list
```

Let's Download the rrdm demo notebook

```bash
wget https://raw.githubusercontent.com/rrdm-shh/jupyter-notebook/master/rrdm-notebook.ipynb
```

Now we launch a Jupyter session

```bash
jupyter notebook
```

?> For users having trouble with conda/jupyter, you can use an online notebook version [here](https://mybinder.org/v2/gh/rrdm-shh/jupyter-notebook/master)

### Advanced

- Create a conda environment with `bwa` and `nb_conda`
- Create a conda environment with the R kernel [(hint)](https://anaconda.org/r/r-irkernel)
- Explore the slide function of Jupyter notebook with *reveal.js* export

---
---

**For the SDAG/CDAG users, here is a function to add in your `.bashrc` to have Jupyter notebooks on the cluster**

```bash
jupyterlab(){
    export XDG_RUNTIME_DIR=""
    JUP_IP="$(/bin/hostname -i)"
    jupyter-lab --no-browser --notebook-dir ./ --ip $JUP_IP  --port 8889
}
```
