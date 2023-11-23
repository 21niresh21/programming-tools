# About NumPy

## What is NumPy ?

* NumPy - Numerical Python
* NumPy is a package built for python to be used in scientific computing and other high level advanced math calculations which typically uses array, table, matrices
* It provides a multidimensional array object and fast operations to perform on those array objects
* The core of NumPy is the ```ndarray ``` object - n-dimensional arrays of homogeneous type

## Why NumPy ?

* NumPy objects are much faster than the native python sequences when the size starts to grow
* NumPy can perform complex and advanced numerical calculations on these objects efficiently
* NumPy arrays are optimized for storage and computation internally

### Differences between python sequence and NumPy arrays

[https://vegibit.com/why-is-numpy-faster-than-lists-in-python/](https://vegibit.com/why-is-numpy-faster-than-lists-in-python/)

| Python List | NumPy Array |      
| :-------- | :------------------------- |
| Variable size | Fixed size |
| Heterogeneous elements | Consistent data type | 
| array of pointers each pointing to objects | contiguous block of memory  |
| memory overhead and runtime checking | prettier |
| no cache locality | better cache locality |
| uses loops to perform element by element operations | vectorization |
| each element has it's own metadata hence the memory overhead | strides (these hold the data of how much to move in that ndarray for efficient indexing) | 

