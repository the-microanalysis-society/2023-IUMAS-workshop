# IUMAS8 - LumiSpy for Processing Luminescence Spectroscopy Data

* [LumiSpy](https://github.com/LumiSpy/lumispy/) - Luminescence spectroscopy data analysis
* [HyperSpy](https://github.com/hyperspy/hyperspy/) - Hyperspectral data analysis (extended by LumiSpy)

It has been prepared for IUMAS8, the 8th meeting of the International 
Union of Microbeam Analysis Societies being held June 2023 in Banff, Canada.

This code base is using the [Python Language](https://www.python.org/) and
[JupyterNotebooks](https://jupyter.org/) for a tutorial for the
[LumiSpy](https://lumispy.org) package.

To (locally) reproduce this project, do the following:

1. Install the relevant packages:
  - If you have an existing `python` and `jupyter-labs` installation, get the package `lumispy`
    (depends on `hyperspy`) from either [pip](https://pypi.org/project/lumispy/)
    or [conda-forge](https://anaconda.org/conda-forge/lumispy).
  - Otherwise install the [HyperSpy bundle](https://hyperspy.org/hyperspy-bundle/) that ships
    all relevant dependencies for you to be able to run the scripts and everything should work
    out of the box.
2. Download this code base. You will need to download the entire project
   using either Git or by downloading and unpacking the entire project as
   a ZIP archive.
3. Start `jupyter-labs` and open the file `230612_IUMAS8_LumiSpy.ipynb`

