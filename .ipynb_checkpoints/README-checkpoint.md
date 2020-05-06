# Object detection using Local Binary classification 

Developer : Dishan Nahitiya
Area      : Image analysis


# Objective

 Develop an image classifier to identify different pattern of canopies on ground.

#  Methodology
 There are number of image classification algorithm in the field of image analysis. I will make this project as a opportunity to explore about local binary pattern search , a basic image analysis method which is widely used in facial recognition.  

# What is local binary patter search ?

Local binary search is a image texture based classification algorithm which transform an image in to a pattern sequence for to compare to another number of images. LBP operator is then applied on the image to extract local features represented by histogram.

Basic 3 * 3 pattern

we are taking 8 pixels such as


 
Since pattern matching is using a binary scheme/methodology , this process is called binary pattern matching. The lbp values we are gathering after the calculation shows the intesity of the of the each color represent in the picture and the scales are round up to the 256

 intesity to of each catogory
 ^
 |
 |
 |_________ >  
     color scheme
     
 <-- 256 --->


# What is it used for

 - face recognition 
 - face detection 
 - verication purposed of the facial images

# Sketch 

  <img src="images/readme/lbp_process.png" alt="lbp process.png" width="500"/>
  
# Results and Discussion 
 - Since the match is problem 
 - rotation was needed to identify the differences because the 
 
# Conclusion 

 - Hard to identify the intensties becuase of unorthodox shapes of each plants.
 - Large data set is needed to optimizer  
 - It was easy to identify the things
 
  



#References

1.[Vupputuri, A. and Meher, S., 2015, April. Facial expression recognition using local binary patterns and kullback leibler divergence. In 2015 International Conference on Communications and Signal Processing (ICCSP) (pp. 0349-0353). IEEE.](https://ieeexplore.ieee.org/document/7322904)

2. [Scikit-image.org. 2020. Local Binary Pattern For Texture Classification — Skimage V0.17.Dev0 Docs. [online] Available at: <https://scikit-image.org/docs/dev/auto_examples/features_detection/plot_local_binary_pattern.html> [Accessed 5 May 2020].](https://scikit-image.org/docs/dev/auto_examples/features_detection/plot_local_binary_pattern.html)