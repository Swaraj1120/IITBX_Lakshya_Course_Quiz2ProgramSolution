# IITBX_Lakshya_Course_Quiz2ProgramSolution

####-----------------Special Note-----------------------------######
As per the question, do not copy main function of the code while uploading.


 You need to write the implementation of the given function:

The function customSort takes a vector "num" of integers as an input along with the vector "weights" which contains the weights of the corresponding integers. We wish to sort this vector "num" from the indices start to end based on the fact that numbers with higher weights appear first and in case the weights are equal, we put the greater number first in the list. We check the precision of your function by calling it with start index being equal to 0 and end index to num.size()-1. Your aim is to complete the given function.

We also wish efficient algorithms. We expect an O(n*log(n)) algorithm here instead of a O(n^2) one.
 (Hint : You can think this problem in lines of merge sort !! )

For example:

num= {1, 4, 9, 6, 9}

weights= {2, 9, 5, 9, 8}

Expected Output = 6 4 9 9 1

For graded-test cases:

   The size of the vectors "num" and "weights" lies in the range 10000 to 100000.
   The entries of "num" and "weights" lie in the range 10 to 99.

   If your program takes too much time, you would get a timeout !!
