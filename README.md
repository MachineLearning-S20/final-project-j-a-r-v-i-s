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

## Trying ##
In order to train our model, the file **train.ipynb** must be ran. This file is pre-filled to use the class data as the training set. The code can be ran in its entirety from top to bottom to show the how well our model performs. It will print the overall accuracy, per-class accuracy, and the confusion matrix at the bottom of the document. 

If it is wished to change the training data, **X** and **y** can be changed to load from a different directory path.

The main functionality of this file is to run the *train* function. Epoch size, learning rate, batch size, and momentum rate are defined inside this function. 

Each function will have a short description about the functionality of the code, and expected inputs and outputs.

## Testing ##
In order to test our model, the file **test.ipynb** and **model.pt** will need to be in the same folder. When **test.ipynb** is open, the cells pre-filled with code must be ran from top to bottom for all the cells to be compiled in the correct order. Any additional code can then be added in a cell below the pre-filled cells.

Input for *test* function: 
Our *test* function can be ran with one input parameter, **X**. This is expected to be in the same format as the original class data distributed at the beginning of the semester (Nx100x100x3). 

Output for *test* function:
The *test* function will output a Nx1 array of the predicted values in the range of 1-9, which represents A-I respectively. If the the predicted labels are required to be in a 1D vector of size N, the final line of code before the return statement may be commented out or deleted.

