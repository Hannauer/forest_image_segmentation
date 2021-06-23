# image_segmentatio
This is a repository for the final project of the Image Processing class from USP 

Name: Segmentation of Forest Areas

Studets: 

         Caio Ferreira Bernado - 9276936
         João Pedro Hannauer Valentini - 9390486
         
         
Abstratc: The main project goal is to use image segmentation in order to produce segments of forest images based on google maps aerial images. We intend to gather images by web scraping or to find some public API that has available aeriel images of forests. The expect result is that each different segment as dense forest areas, rivers and trails appearing on the image could be able to be identified.

Main Objective: We intend to compare diferent methods for image segmentation in the context of aerial forest imagens that can indicate a potencial human intervention or damage manly focused on fires. The ideia is to identify the algorithm that more consistently is able to segmente the fires from the rest of the imagens. We are also trying to propose a inicialization approach to for the watershed seeds because we belive that a smarter choice of the initial point can leed to a better formance in fire region segmentatio.

Input Images: The images are mostly composed of forest images with fire obtained froma kaggle dataset that is link bellow as same examples of the dataset. The forest with fire are just a part of the hole data.

[Link to acess the dataset](https://www.kaggle.com/kutaykutlu/forest-fire)

Dataset Examples:
![example1](https://github.com/Hannauer/forest_image_segmentation/blob/main/fire_seg_test/1.png)
![example2](https://github.com/Hannauer/forest_image_segmentation/blob/main/fire_seg_test/2.jpg)
![example3](https://github.com/Hannauer/forest_image_segmentation/blob/main/fire_seg_test/3.jpg)
![example4](https://github.com/Hannauer/forest_image_segmentation/blob/main/fire_seg_test/4.jpg)



Project Steps:

1. Exploration of data and libs that can be found in the notebooks direction.

2. Creation of fuctions and the inicial proposal of a test pipeline to compare to methods: OTSU and Watershed.

3. Test other methods both proposed in the lectures or from external knowleged sorces. 

4. Include somes of the tested methods on the inicial test pipeline.

5. Propose the final comparision pipeline and implement for all the selected algorithms

6. Test of a sliding windows plus pixel intensity analysis for inicialialization of the random seeds in Watershed so the fire regions could be more contantly found in the segmentation.

7. Compare the results obtained.


Obs: the inicial code for the project can be found on the notebooks directory.

