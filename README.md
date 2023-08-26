# Cartooning-of-an-image-with-Python
We are cartoonifying an image by creating an edge mask, then we reduce the 
colour palette of the original image that is reduce the number of different colours 
that will be seen in the image. The final image is achieved by combining the edge 
mask and reduced colour palette of the original image .

The mask is created by initially blurring the image using Averaging blurring 
,median blur , Gaussian blur, Bilateral blurring. and then edges are extracted from 
both median blur , Gaussian blur , Averaging blurringusing, Bilateral blurring using adaptive threshold, Sobel, Canny and 
Laplacian filters .

Conclusion:  Among all the four techniques i.e Adaptive threshold ,Sobel ,Canny, Laplacian
Canny fail to give us the expected output and would not be suitable to filter the 
blurred image
