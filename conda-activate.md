incase one is hvaing issues entering the conda environment automatically after opening the terminal, this command would help:

``conda config --set auto_activate_base false``

now open a new terminal and see that the conda environment has been deactivated.

to require the conda environment on terminal, run:

``conda config --set auto_activate_base true``

