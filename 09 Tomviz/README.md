# IUMAS 8 - Tomviz for Processing and Visualizing Tomographic Data

The [Tomviz](https://github.com/openchemistry/tomviz) GitHub repository
is where development takes place. There is also online documentation for the
project on [tomviz.readthedocs.io](https://tomviz.readthedocs.io/) with
pointers to various aspects of the project.

Before the workshop I recomment that you get the latest release of Tomviz.
There are two methods which I will discuss at the workshop - the standalone
installer or a Conda packge. The Conda package is a little more up to date as
we work through the RC process, either should work for the purposes of the
workshop.

Go to [Tomviz 1.10.0](https://github.com/OpenChemistry/tomviz/releases/tag/1.10.0)
to get the standalone installer for your platform. If you use Conda I would
recommend creating a Tomviz environment as you are then able to install
additional Python modules which offers the most flexibility depending upon
your use case.

Assuming you have Conda installed and configured:
```
conda create --name tomviz --channel=conda-forge python=3.7 tomviz
conda activate tomviz
tomviz
```

You can install other packages, such as tomopy, which can then be used from
the application. Tomviz makes heavy use of GPU accelerated rendering and having
working OpenGL drivers is important. You can easily test this by opening the
application and going to Sample Data -> Generate Random Particles and accepting
the defaults. Adding the Visualization -> Volume will exercise the volume
rendering capabilities.

There are [tutorial slides](https://openchemistry.github.io/tomviztutorial/)
that will be used to guide the workshop and discuss various elements of the
user interface, data processing and visualization capabilities along with how
to add custom code to process your data.
