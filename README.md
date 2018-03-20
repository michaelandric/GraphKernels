# GraphKernels


A large collection of source codes for computing kernels on graph.

- GraphKernelsCollection contains a variety of scripts for computing kernels with MATLAB and Python
- graphkernels is a Python package for graph kernels. The Python interface is created from a C++ source code that is wrapped with SWIG
- GKextCPy is the package created to build the extension module for the wrapper from C++ to Python

### install on mac
See here: https://github.com/BorgwardtLab/GraphKernels/issues/5

Needed to jump through some hoops:

* `brew install igraph`
* `brew install eigen`

Then update CFLAGS for numpy:
* `export CFLAGS="-I/usr/local/lib/python3.6/site-packages/numpy/core/include $CFLAGS"`
