here, you gotta have a [python installer](https://www.python.org/downloads/).

to set a particular version as default, go to 

``/usr/local/bin/python``

location and select which to use for instance

``/usr/local/bin/python3.9`` 

for setting python 3.9 as default.

now go to the terminal and type out:

``nano ~/.zshrc``

then 

``alias python=/usr/local/bin/python3.9``

and that's it.!

you can comfirm by typing:

``python --version``

and see if your default python displays.

