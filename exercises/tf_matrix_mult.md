## Matrix Multiplication in TensorFlow

a) Open the notebook [MatrixMultiplication](https://github.com/tensorchiefs/dl_course/blob/master/notebooks/01_MatrixMultiplication.ipynb) and visualize the computational graph in TensorBoard  
Hint: run all cells in the jupyter notebook and then open a terminal and type: tensorboard --logdir=path/to/log-directory or run tensorboard from the notebook with: !tensorboard --logdir=path/to/log-directory

b) Change the code in the notebook that it divides the matrix multiplication by 10 instead of multiplying it with 10. Compare the numpy and tensorflow restults. What do you observe?

c) Now use a placeholder for m2 to feed-in values. You must specify the shape of the m2 matrix (rows, columns).
