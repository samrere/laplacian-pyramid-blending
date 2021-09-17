## Laplacian Pyramid Blending
This is a Python implementation of Laplacian pyramid blending.
## Required Libraries
from skimage.io import imread  
from skimage.transform import rotate  
from numba import jit  
import numpy as np  
import matplotlib.pyplot as plt
## Results
*blending an apple with an orange*  

apple             |  orange
:-------------------------:|:-------------------------:
![](https://github.com/Sam-gege/laplacian-pyramid-blending-from-scratch/blob/main/images/apple.png)  |  ![](https://github.com/Sam-gege/laplacian-pyramid-blending-from-scratch/blob/main/images/orange.png)  
<p align="center">
  <img src="https://github.com/Sam-gege/laplacian-pyramid-blending-from-scratch/blob/main/results/apple_orange.png">
</p>  

*blending a cheetah's face onto a cat's head*  

cheetah             |  cat
:-------------------------:|:-------------------------:
![](https://github.com/Sam-gege/laplacian-pyramid-blending-from-scratch/blob/main/images/face1.png)  |  ![](https://github.com/Sam-gege/laplacian-pyramid-blending-from-scratch/blob/main/images/face2.png)  
<p align="center">
  <img src="https://github.com/Sam-gege/laplacian-pyramid-blending-from-scratch/blob/main/results/cheetah_cat.png">
</p>
The visual artifacts around the whiskers are pretty obvious, because the colors and frequencies around the boundary are so much different. 
will probably get better results using human faces.
