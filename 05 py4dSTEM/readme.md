

![py4DSTEM logo](./py4DSTEM_logo.png)

**py4DSTEM** is an open source set of python tools for processing and analysis of four-dimensional scanning transmission electron microscopy (4D-STEM) data. Additional information:

- [Our open access py4DSTEM publication in Microscopy and Microanalysis](https://doi.org/10.1017/S1431927621000477) describing this project and demonstrating a variety of applications.
- [The py4DSTEM documentation pages](https://py4dstem.readthedocs.io/en/latest/index.html).
- [Our open access 4D-STEM review in Microscopy and Microanalysis](https://doi.org/10.1017/S1431927619000497) describing this project and demonstrating a variety of applications.


# py4DSTEM Installation

We recommend that you use the Miniconda python distribution for **py4DSTEM**, which you can download here: https://docs.conda.io/en/latest/miniconda.html.

Next, open a terminal on OSX or Linux, or open "Anaconda Prompt" in Windows, and then run the following commands:


```
conda update conda
conda create -n py4dstem
conda activate py4dstem
conda install -c conda-forge py4dstem=0.13.17 pymatgen jupyterlab
```

You will need to specify "yes" to confirm some these commands by typing "y" and pressing enter. In Windows you may also need to run:

```
conda install pywin32
```

In order, these commands:

- Ensure your installation of anaconda is up-to-date.
- Make a virtual environment.
- Enter the py4dstem virtual environment.
- Install py4DSTEM, pymatgen and Jupyter Lab into this environment.

- On Windows: enable python to talk to the windows API

Finally, to enter the notebook environment you will run:
```
jupyter lab
```
Or if you are determined to use classic Jupyter Notebooks, you can instead run:
```
jupyter notebook
```

Once you are in the jupyter environment, you can verify that py4DSTEM is correctly installed by running:
```
import py4DSTEM
```


