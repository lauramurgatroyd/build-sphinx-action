v0.0.1
* Change order of conda env setup so that built package is installed before packages in the environment.yml are.
* Add package_conda_channels variable which sets the conda channels used when installing the built package.
* Add build_subdir_name variable which sets where the docs htmls are saved within docs/build
* conda environment by default installs python 3.7
