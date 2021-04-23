## Laplacian pyramid blending
This is a Python implementation of Laplacian pyramid blending.
## required libraries
from skimage.io import imread  
from skimage.transform import rotate  
from numba import jit # conversion to machine code  
import numpy as np  
import matplotlib.pyplot as plt
## Results
*blending an apple with an orange*  
![](https://github.com/Sam-gege/laplacian-pyramid-blending-from-scratch/blob/main/results/apple_orange.png)
<br /><br /><br />
*blend a cheetah face on a cat head*  
![](https://github.com/Sam-gege/laplacian-pyramid-blending-from-scratch/blob/main/results/cheetah_cat.png)
<br /><br />
The visual artifacts around the whiskers are pretty obvious, because the colors and frequencies around the boundary are so much different. 
will probably get better results using human faces.
