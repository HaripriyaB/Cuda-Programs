# Cuda-Programs
Simple basic Cuda programs for beginners.
* Addvec is addition of two 1D vectors in GPU. It takes user input and processes.
* Addmatrix is addition of two 2D matrices in GPU. In first case it takes user input and process with One block with number of threads equal to number of pixels. eg. gridDim=(1,1,1), blockDim=(m,n,1) and second case gridDim= (adjusted according to values of m and n)(Ceil(n/4),Ceil(m/4),1), blockDim=(4,4,1).
