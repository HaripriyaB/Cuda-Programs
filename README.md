# Cuda-Programs
Simple basic Cuda programs for beginners.
* Addvec is addition of two 1D vectors in GPU. It takes user input and processes.
* Addmatrix is addition of two 2D matrices in GPU. In first case it takes user input and process with One block with number of threads equal to number of pixels. eg. gridDim=(1,1,1), blockDim=(m,n,1) and second case gridDim= (adjusted according to values of m and n)(Ceil(n/4),Ceil(m/4),1), blockDim=(4,4,1).
* Convert RGB image to Greyscale using pycuda, matlab, openCV libraries. It converts the RGB image to a 3D matrix and then feed in to the kernel function and later compute each pixel value as grey= (red x 0.21) + (green x 0.72) + (blue x 0.07). the RGB with 3 channels turned in to a 2d Channel with black and white as the primary colors and 0-255 range between them.
# Note
This is done as a part of the course CS 466. Topic : Basic Cuda Programming.
