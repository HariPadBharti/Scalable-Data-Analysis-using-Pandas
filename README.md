### Scalable-Data-Analysis-using-Pandas (Python)

<B>Dataset:</B> Extracted from World Bank official public datasets repository : <a href="http://data.worldbank.org/topic/environment#tp_prop"> Click here </a>

Codes in `Ipython Notebook` ('ipynb') file format. 

<I>Introduction:</I><P> Motivated by helpful ways to spread awareness about environment and role of environmental resources on economy, this project was to worked on World Bank Datasets and derive useful results on Carbon Emission, Forest Cover and corresponding GDP of the region and influence of environment on the economy. Use of Pandas and Matplotlib libraries of Python to create data visualization. Data cleaning done using ipython notebook on Anaconda. </P>

<I>Goal: </I> Learn about visualization of large dataset elements on a scalable platform and better analyze the trends and picture of valuable informations. 

<B>Conclusion: </B> "Environmental exploitation is not a right way to grow Economy". 


### About  [IPYTHON NOTEBOOK] 

<img src = "https://github.com/HariPadBharti/Scalable-Data-Analysis-using-Pandas/blob/master/images/ipynblogo.png">

# ipynb

[![Build Status](https://travis-ci.org/yuvipanda/ipynb.svg?branch=master)](https://travis-ci.org/yuvipanda/ipynb)

A python package providing an easy way to explicitly import [Jupyter Notebooks](https://github.com/jupyter/notebook) files (`.ipynb`) the same way you would import regular `.py` files.

## Installation ##

You can install ipynb with:

```bash
pip install ipynb
```

## Importing a notebook ##

### Full import ###

You can do a 'full' import - this has the same semantics of importing a .py file. All the code in the .ipynb file is executed, and classes/functions/variables in the top level are available for use.

If you have a notebook file named `server.ipynb`, you can import it via:

```python
import ipynb.fs.full.server
```

You can use the `from ... import ..` too.

```python
from ipynb.fs.full.server import X, Y, X
```


-------------------------------------------------------------------------------------------------------------------------
