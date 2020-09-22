HW2

I started with think which part needed to use the most in the memory. It is the vector part which it called every time. I then think about the tile, so I create the tile Ns in the program. I figure that I only need to calculate the column index since vector is a N x 1 matrix. Then I need to try to figure the function of the loop for the tile that load into the shared memory.
 
Here is the sample of running 10 x 10 matrix and 10 x 1 vector. The three array is matrix-vector multiplication without using shared memory. The last array is matrix-vector multiplication using shared memory. I tried the matrix-matrix multiplication example showed in class and it also give me 0 array for the shared memory. 

Refer to HW2 result.png

My CGMA ratio for shared memory = \frac{#FLOPs}{#GMA}=\ \frac{2}{2}\ =\ 1 


My CGMA ratio for shared memory = \frac{#FLOPs}{#GMA}=\ \frac{2}{1}\ =\ 2
