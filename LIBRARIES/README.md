# NUMPY LIBRARY
- NumPy is a Python library used for working with arrays. It also has functions for working in domain of linear algebra, fourier transform, and matrices.
- For installing numpy library on your system, type the command - **pin install numpy**.
- Getting it inside your code, we need to type - *import numpy* or *import numpy as np* (this method shortens the need to use keyword numpy everytime).

#### Creating numpy array.
- We can directly make numpy array as np.array([ *values* ]).
- By this method, we can create 0D, 1D, 2D or 3D arrays.
- We can also convert lists into numpy arrays by using the same method of np.array().
- "arrname.ndim" is used to store the Dimension of the array.

#### Numpy array basics and methods.
- These arrays are made with 0 based indexes.
- For multi-dimensional arrays, arrname[ m, n, k ] is used. (k for 3D array).
- SLICING IN NUMPY ARRAY 
    - ARR_NAME[ START : END ]
    - ARR_NAME[ START : END : STEP ]
    - Negative array indexing refers to indexing from the back starting from 0 , -1 and so on...
- Numpy array data type
    - arr_name.dtype method returns the data type of the array.
    - To create an array of certain data type, we can use method  np.array(arr_data , dtype = " ").
    - arr_name.astype(' '), returns a copy of the array converting it to the provided data type.
- COPY() AND VEIW() 
    - copy() method creates a copy of the array and gives it to the variable. This is an independent copy, any changes made in the either two will not affect the other.
    - veiw() can be seen as a live copy of the array in another variable. Changes made in any of the copy will be reflected in all of the others.
    - .base method tells us whether the array is copy or veiw. If the return value is *none* then it is a copy otherwise it is a *veiw*.
- *(IMPORTANT)* Iterating through array
    - We can use " **for x in arr_name** " to make x run through the array row-wise(for higher dimension arrays).
    - We can use np.nditer(arr_name) to return a var which runs through linearily.
    - refer [here](https://www.w3schools.com/python/numpy/numpy_array_iterating.asp) to get some more iterations method.
- .where(*condition*) returns the indices of the elements which satisfy the given condition.
- np.searchsorted(arr_name , val , side= "*side to search from*") returns the index of the array where the given val is to be inserted in order to keep the array sorted.
- np.sort(arr_name) sorts the rows of array. (*arrays of other data types can also be sorted.*).

    These resources can be read in more-depth from [here](https://www.w3schools.com/python/numpy/numpy_intro.asp)

