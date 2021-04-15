# Learning from Graphs: From Mathematical Principles to Practical Tools

A hands-on tutorial presented by [Michaël Defferrard](https://deff.ch) at [The Web Conference 2021](https://www2021.thewebconf.org/program/tutorials).

> A graph encodes relations between objects, such as distances between points or hyperlinks between websites.
> You will learn how to extract information about that relational structure.
> This information is crucial to characterize an object through its local connectivity or an entire graph through its global connectivity.
> On top of that structure, a network may possess data about the objects or the relations, such as a point's color or an hyperlink's click-through rate.
> You will learn how to leverage a graph to analyze this data.
> Leveraging the structure that underlies data is an important concept, from physical symmetries dictating conservation laws to the efficiency of convolutional neural networks.
> The tutorial is built on deep mathematical principles but will walk you from the basics with an emphasis on intuitions and working knowledge.

**Intended audience**: people with theoretical or practical interests about graphs and data on graphs. Adapted to both researchers and practitioners.

**Prerequisite knowledge**: scientific python programming, basic linear algebra, no prior knowledge about networks is necessary.

## Installation

[![Binder](https://mybinder.org/badge_logo.svg)][binder]
&nbsp; Click the binder badge to run code from your browser without installing anything.

[binder]: https://mybinder.org/v2/gh/mdeff/learning-from-graphs-webconf2021/HEAD?urlpath=lab

For a local installation, you will need [git], [Python], [Jupyter], and packages from the [Python scientific stack][scipy].
If you don't know how to install those on your platform, we recommend to install [Miniconda] or [Anaconda], a distribution of the [conda] package and environment manager.
Follow the below instructions to install it and create an environment for the course.

1. Download the Python 3.x installer for Windows, macOS, or Linux from <https://conda.io/miniconda.html> and install with default settings.
   Skip this step if you have conda already installed (from [Miniconda] or [Anaconda]).
   * Windows: double-click on `Miniconda3-latest-Windows-x86_64.exe`.
   * macOS: double-click on `Miniconda3-latest-MacOSX-x86_64.pkg` or run `bash Miniconda3-latest-MacOSX-x86_64.sh` in a terminal.
   * Linux: run `bash Miniconda3-latest-Linux-x86_64.sh` in a terminal or use your package manager.
1. Open a terminal.
   Windows: open the Anaconda Prompt from the Start menu.
1. Install git with `conda install git`.
1. Navigate to the folder where you want to store the material with `cd path/to/folder`.
1. Download this repository with `git clone https://github.com/mdeff/learning-from-graphs-webconf2021`.
1. Enter the repository with `cd learning-from-graphs-webconf2021`.
1. Create an environment containing the required packages with `conda env create -f environment.yml`.

Every time you want to work, do the following:

1. Open a terminal.
   Windows: open the Anaconda Prompt from the Start menu.
1. Activate the environment with `conda activate learning-from-graphs-webconf2021`.
1. Navigate to the folder where the material is stored with `cd path/to/folder/learning-from-graphs-webconf2021`.
1. Start Jupyter with `jupyter lab`.
   The command should open a new tab in your web browser.
1. Edit and run the notebooks from your browser.
1. Once done, you can run `conda deactivate` to leave the environment.

[git]: https://git-scm.com
[python]: https://www.python.org
[jupyter]: https://jupyter.org
[scipy]: https://www.scipy.org
[anaconda]: https://www.anaconda.com/download
[miniconda]: https://conda.io/miniconda.html
[conda]: https://conda.io
[conda-forge]: https://conda-forge.org

## License

The content is released under the terms of the [MIT License](LICENSE.txt).
