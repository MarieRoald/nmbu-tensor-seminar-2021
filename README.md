# Extra materials for the multi-way data analysis tutorial at NMBU
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/MarieRoald/nmbu-tensor-seminar-2021/HEAD)

To run these notebooks, clone the repository or use [binder](https://mybinder.org/v2/gh/MarieRoald/nmbu-tensor-seminar-2021/HEAD).

The code dependencies are listed in the `environment.yml`-file. You can create a new environment with only the code dependencies by running

```
conda create -f environment.yml
```

This will create an anaconda environment named `demo`, which you can use to run the tutorial from. Alternatively, you can run

```
conda install -c conda-forge numpy matplotlib pandas rise ipywidgets scipy xarray plotly requests statsmodels tqdm
pip install wordcloud git+https://github.com/tensorly/tensorly.git git+https://github.com/marieroald/component-vis.git
```

to install the dependencies manually.
