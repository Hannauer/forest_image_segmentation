# image_segmentatio
This is a repository for the final project of the Image Processing class from USP 

Name: Segmentation of Forest Areas

Studets: 

         Caio Ferreira Bernado - 9276936
         João Pedro Hannauer Valentini - 9390486
         
         
Abstract: The main project goal is to use image segmentation in order to produce segments of forest images based on google maps aerial images. We intend to gather images by web scraping or to find some public API that has available aerial images of forests. The expected result is that each different segment as dense forest areas, rivers and trails appearing on the image could be able to be identified.

Main Objective: We intend to compare different methods for image segmentation in the context of aerial forest images that can indicate a potential human intervention or damage mainly focused on fires. The idea is to identify the algorithm that more consistently can segment the fires from the rest of the images. We are also trying to propose an initialization approach for the watershed seeds because we believe that a smarter choice of the initial point can lead to a better performance in the fire region segmentation.

Input Images: The images are mostly composed of forest images with fire obtained from Kaggle's dataset that is linked below, and one can find some examples of the dataset just after its link. The forest with fire is just a part of the hole data.

[Link to acess the dataset](https://www.kaggle.com/kutaykutlu/forest-fire)

Dataset Examples:
![example1](https://github.com/Hannauer/forest_image_segmentation/blob/main/fire_seg_test/1.png)
![example2](https://github.com/Hannauer/forest_image_segmentation/blob/main/fire_seg_test/2.jpg)
![example3](https://github.com/Hannauer/forest_image_segmentation/blob/main/fire_seg_test/3.jpg)
![example4](https://github.com/Hannauer/forest_image_segmentation/blob/main/fire_seg_test/4.jpg)



Project Steps:

1. Exploration of data and libs that can be found in the notebooks directory.

2. Creation of functions and the initial proposal of a test pipeline to compare to methods: OTSU and Watershed.

3. Test other methods both proposed in the lectures or from external knowledge sources. 

4. Include some of the tested methods on the initial test pipeline.

5. Propose the final comparison pipeline and implement it for all the selected algorithms

6. Test of a sliding window plus pixel intensity analysis to initialize the random seeds in Watershed so the fire regions could be more constantly found in the segmentation.

7. Compare the results obtained.


Obs: the initial code for the project can be found on the notebooks directory.
