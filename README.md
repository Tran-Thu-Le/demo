# demo

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/Tran-Thu-Le/demo/HEAD)

with the new environment.yml file, we are now able to put it into Binder. However, it is still quite slow since all the package are to heavy.


run jupyter notebook online using Google Colab

1. Go to this [link](https://colab.research.google.com/github/) and press Tab GitHub
2. Go to and copy this [link]()
3. In Tab GitHub, past the link. Press search-symbol
4. Run the code by clicking the correspoding triangle-symbol in the left of its line


theoriginal  `.yml` should be

name: pDL
channels:
  - conda-forge
  - pytorch
  - dglteam
dependencies:
  - python=3.8
  - pip
  - matplotlib
  - jupyter
  - jupyterlab
  - pytorch>=1.4
  - torchvision>=0.5
  - torchtext
  - opencv
  - librosa
  - nb_conda_kernels
  - dgl>=0.4.3
  - pip:
    - torchviz

