v0.1.4
* Allows user to specify which python version they want the action to work with. Defaults to 3.7.

v0.1.3
* Remove use of set-output due to deprecation: https://github.blog/changelog/2022-10-11-github-actions-deprecating-save-state-and-set-output-commands/

v0.1.2
* Updates actions/upload-artifact to v3.1.1
* Updates actions/download-artifact to v3.0.1

v0.1.1
* Force install from artifact by setting version of package (by retrieving version string from tar.bz2 file)
* Add print statements to show files being copied, conda channel being created, and version being retrieved
* Install conda-build from conda-forge


v0.0.1
* Change order of conda env setup so that built package is installed before packages in the environment.yml are.
* Add package_conda_channels variable which sets the conda channels used when installing the built package.
* Add build_subdir_name variable which sets where the docs htmls are saved within docs/build
* conda environment by default installs python 3.7
