#**Image Processing Projects**

This repository is a collection of all things fun in image processing achieved with opencv and python. Projects and implementations are ever so on random topics but interesting ones nevertheless.

 1. Image_Lib - contains common code files that is reused by most projects.
 2. PyImageSearchProblems - Kudos to Adrian for his awesome blog on image processing in opencv - [PyImageSearch](http://www.pyimagesearch.com/). The files in this folder mostly follow some of his blogs with my flavor to the problems here and there.
 3. PythonProjects - My playground! Every time someone mentions or I think of an interesting problem, it ends up here.
 4. SelfProjectUtils - Code that I usually use to understand images for tuning parameters in other projects and such.
 
 
Few example results:
 - With the availability of displays in various sizes, image retargeting or image resizing with content awareness is something that's done frequently nowadays.  A simple implementation of seam carving a well known method and it's result(width reduction by 20%) is as below.  Note that the content of the image is not scaled or cropped.
   
![Input image](https://github.com/shekkizh/ImageProcessingProjects/blob/master/images/Dog.jpg)                  ![Seam reduced image](https://github.com/shekkizh/ImageProcessingProjects/blob/master/results/20PercentWidthReduction.jpg)

-  Panoramic image stitching using SIFT/ SURF features.

<img src="https://github.com/shekkizh/ImageProcessingProjects/blob/master/images/Image1.jpg" width = "300" height = "225"/>            <img src="https://github.com/shekkizh/ImageProcessingProjects/blob/master/images/Image2.jpg" width = "300" height = "225"/>
<img src="https://github.com/shekkizh/ImageProcessingProjects/blob/master/results/ImageStitiching.jpg" width = "600" height = "225"/>  
-  Image Cartooning. 

![Image](https://github.com/shekkizh/ImageProcessingProjects/blob/master/results/CartoonishImaging.jpg)

-  Color transforms and compression.

<img src="https://github.com/shekkizh/ImageProcessingProjects/blob/master/results/10ClusterImage.jpg" width = "200" height = "150"/>       <img src="https://github.com/shekkizh/ImageProcessingProjects/blob/master/results/ImageDithering.jpg" width = "200" height = "150"/>       <img src="https://github.com/shekkizh/ImageProcessingProjects/blob/master/results/OldSchoolSadnessFilter.jpg" width = "200" height = "150"/>       <img src="https://github.com/shekkizh/ImageProcessingProjects/blob/master/results/StatisticalColorTransform.jpg" width = "200" height = "150"/>

-   Auto detect size of objects in images given a reference object. In the example below the height of iPhoneSE (Reference object in this case) was the only value that was provided to the algorithm.

<img src="https://github.com/shekkizh/ImageProcessingProjects/blob/master/results/AutoDetectedPhoneSize.jpg" width = "449" height = "290"/>   <img src="https://github.com/shekkizh/ImageProcessingProjects/blob/master/images/ActualPhoneSize.jpg" width = "400" height = "175"/>

-   Maze solver - an automatic maze path finder.

<img src="https://github.com/shekkizh/ImageProcessingProjects/blob/master/results/MazeSolver50x50.jpg" width = "400" height = "400"/>   
-  A few days back when I was at a meetup I noticed people taking pictures of the presentation and I realized I could with some code make the whole thing better. So here it is unwarped and centered :)

<img src="https://www.cloudfoundry.org/wp-content/uploads/2016/02/Ben.jpg" width = "300" height = "225"/> <img src="https://github.com/shekkizh/ImageProcessingProjects/blob/master/results/Unwarping%20presentations/unwarped_presentation2.jpg" width = "335" height = "242"/>

Works decently good when there is some occlusion as well

<img src="https://cdn-images-1.medium.com/max/800/1*lWxJOEOSEWmTcRyky0Vc0w.jpeg" width = "400" height = "300"/> <img src="https://github.com/shekkizh/ImageProcessingProjects/blob/master/results/Unwarping%20presentations/unwarped_presentation3.jpg"/>

-  Localization based on Bayesian inference. Here I samplea few locations by calibrating face location initially and perform inference after.

