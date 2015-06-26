# ircltools

Command line tools for high-resolution stellar spectroscopy work.

It is recommended that you clone this repo into your $PYTHONPATH directory, so these files will be in $PYTHONPATH/ircltools. If you don't know where your $PYTHONPATH lives, type <code>echo $PYTHONPATH</code> in a terminal. If you don't get anything back then you do not have a $PYTHONPATH set.

Edit your .bashrc (or .bash_profile or .profile) to include this line after $PYTHONPATH has been defined:
```console
export PATH="$PYTHONPATH/ircltools:$PATH"
```

That way you should be able to either import the tools from within python:
```python
from ircltools import mksplot
help(mksplot)
```
or run them from the terminal:
```console
mksplot.py -h
```

*Contact: [Ivan Ramirez](mailto:ivan@astro.as.utexas.edu?subject=cltools)*
