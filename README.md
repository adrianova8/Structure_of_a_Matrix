# S03 T02: Estructura d'una Matriu

**Target:**

_We will practice and become familiar with the structure of **Matrices**, **Dimension**, **Shape**, **Vectorization**, and **Broadcasting**._

# LEVEL 1
_We work on the concepts of the structure of a matrix, dimension, axes and vectorization that allows us to reduce the use of for loops in arithmetic or mathematical operations_

    # Exercise 1
    - Creates a one-dimensional np.array, including at least 8 integers, data type int64. Shows the size and shape of the array.

    # Exercise 2
    - From the matrix of exercise 1, calculate the average value of the values entered and subtract the average resulting from each of the values in the matrix

    # Exercise 3
    - Create a two-dimensional array with a shape of 5 x 5. Extract the maximum value of the array, and the maximum values of each of its axes

  
 # LEVEL 2
_We work on the concepts of the structure of an array, **Broadcasting**, **Indexing**, **Mask**_
  
  # Exercise 1
  - Show me with examples of different arrays, the fundamental rule of Broadcasting that says, "arrays can be transmitted / broadcast if their dimensions match       or if one of the arrays has a size of 1
  
  # Exercise 2
  - Use **Indexing** to extract the values of a column and a row from the array. And add up their values.
  
  # Exercise 3
  - Mask the above matrix, perform a vectorized Boolean calculation, taking each element and checking if it is evenly divided by four.
    * This returns a mask array in the same way as the elementary results of the calculation
  
  # Exercise 4
  - Now use this mask to index the original number array. This causes the array to lose its original shape, reducing it to one dimension, but you still get the data you are looking for.
  
 # LEVEL 3
_Age manipulation with Matplotlib._

_You will upload any image (jpg, png ..) with Matplotlib. note that RGB images (Red, Green, Blue) are really only widths × heights × 3 arrays (three channels Red, Green, and Blue), one for each color of int8 integers,_

_Manipulate these bytes and use Matplotlib again to save the modified image once you're done._
  
  # Exercise 1
* How me to see what happens when we remove the Green G or Blue B channel.

* Show me see what happens when we remove the Green G or Blue B channel. You should use indexing to select the channel you want to undo.

* Use the method, mpimg.imsave () of the imported library, to save the modified images and you will need to upload them to your repository on github.
  
