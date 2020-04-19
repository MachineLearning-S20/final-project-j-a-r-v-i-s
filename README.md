# Final Project

Necessary libraries:
 - numpy
 - torch
 - sklearn
 - pandas
 - matplotlib
 - seaboard
 - cv2
 - skimage
 - random
 - scipy
 - itertools
 - datetime
 - os

In order to test our model, the file **test.ipynb** and **MODELNAME.pt** will need to be in the same folder. When **test.ipynb** is open, the cells pre-filled with code must be ran from top to bottom for all the cells to be compiled in the correct order. Any additional code can then be added in a cell below the pre-filled cells.

Input: 
Our *test* function can be ran with one input parameter, **X**. This is expected to be in the same format as the original class data distributed at the beginning of the semester (Nx100x100x3). 

Output:
The *test* function will output a Nx1 array of the predicted values in the range of 1-9, which represents A-I respectively.

