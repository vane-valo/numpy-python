# numpy-python

This Jupyter Notebook is about an exercise of cleaning and transforming some raw data, to pre-processed data ready to be analyze.

## numpy library

NumPy is the fundamental package for scientific computing in Python. It is a Python library that provides a multidimensional array object, various derived objects (such as masked arrays and matrices), and an assortment of routines for fast operations on arrays, including mathematical, logical, shape manipulation, sorting, selecting, I/O, discrete Fourier transforms, basic linear algebra, basic statistical operations, random simulation and much more.

Some of the functions that were used were:

### -> numpy.genfromtxt
numpy.genfromtxt(fname, dtype=<class 'float'>, delimiter=None, skip_header=0, skip_footer=0, missing_values=None, filling_values=None, usecols=None)

Load data from a text file, with missing values handled as specified.

### -> numpy.isnan
numpy.isnan(x, /, out=None, *, where=True, casting='same_kind', order='K', dtype=None, subok=True[, signature, extobj])

Test element-wise for NaN and return result as a boolean array.

### -> numpy.argwhere
numpy.argwhere(a)

Find the indices of array elements that are non-zero, grouped by element.

### -> numpy.unique
numpy.unique(ar, return_index=False, return_inverse=False, return_counts=False, axis=None, *, equal_nan=True)

Find the unique elements of an array.

### -> numpy.reshape
numpy.reshape(a, newshape, order='C')

Gives a new shape to an array without changing its data.

### -> numpy.hstack
numpy.hstack(tup, *, dtype=None, casting='same_kind')

Stack arrays in sequence horizontally (column wise).

### -> numpy.vstack
numpy.vstack(tup, *, dtype=None, casting='same_kind')

Stack arrays in sequence vertically (row wise).

Source: 
Official Numpy Documentation 
https://numpy.org/doc/stable/index.html
