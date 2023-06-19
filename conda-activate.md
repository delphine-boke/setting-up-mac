incase one is having issues entering the conda environment automatically after opening the terminal, this command would help:
<img width="785" alt="base environment" src="https://github.com/delphine-boke/setting-up-mac/assets/55446293/84e3054e-907f-4475-ba81-32b960124edd">


``conda config --set auto_activate_base false``

now open a new terminal and see that the conda environment has been deactivated.

<img width="815" alt="base environ off" src="https://github.com/delphine-boke/setting-up-mac/assets/55446293/8138c9b9-9e49-422f-883a-e2647bc5bd09">



to require the conda environment on terminal, run:

``conda config --set auto_activate_base true``
