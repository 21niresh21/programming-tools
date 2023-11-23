# Multidimensional array

## ndarray

* It is a multidimensional array where n>=2, n stands for the dimensions of the array
* ```axes``` - dimension of the array
* ```ndarray``` is the class of NumPy

### Attributes of ndarray

* ```ndarray.ndim``` - no of axes
* ```ndarray.shape``` - dimensions
* ```ndarray.size``` - total number of elements of array
* ```ndarray.dtype``` - data type of array
* ```ndarray.itemsize``` - size of each element in bytes

### array creation

* ndarrays can be created from python sequences like lists, tuples and dictionaries, but be sure to mention data type if you want specific data types in the ndarray and to avoid overflow, underflow results during arithmetic calculations
* ```np.array([sequence])``` - ```np.array([1,2,3])``` - ```np.array([(1,2,3),(4,5,6)])```
* ```np.zeros(shape,dtype=?)``` - ```np.zeros((3, 4))``` - array with all zeroes
* ```np.ones(shape,dtype=?)``` - ```np.ones((3, 4))``` - array with all ones
* ```np.empty(shape,dtype=?)``` - ```np.empty((3, 4))``` - random numbers
* ```np.arange(start,stop,step)``` - (https://numpy.org/doc/stable/reference/generated/numpy.arange.html#numpy.arange)[https://numpy.org/doc/stable/reference/generated/numpy.arange.html#numpy.arange]
* ```np.linspace(start,stop,no of samples to generate)``` - (https://numpy.org/doc/stable/reference/generated/numpy.linspace.html#numpy.linspace)[https://numpy.org/doc/stable/reference/generated/numpy.linspace.html#numpy.linspace]
* 
