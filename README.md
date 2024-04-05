## In this repo we're going to review some of Opencv algorithms and methods to change your picture and detect objects in our picture.

This repo is bulit along with the course I've seen to learn opencv and we'll start with some basic method such as cvtColor and the deeper we go through course the more interesting the methods become
like we'll use yolo to detecte obejects or count coins with opencv itself and use some algorithms like Clahe and more. 

* [Read an image ](https://github.com/0nE01/Opencv/tree/main?tab=readme-ov-file#read-an-image)
* [Cropping](https://github.com/0nE01/Opencv/tree/main?tab=readme-ov-file#cropping) 
* [Color channels](https://github.com/0nE01/Opencv/tree/main?tab=readme-ov-file#color-channels)
* [Gray images](https://github.com/0nE01/Opencv/tree/main?tab=readme-ov-file#gray-images)
* [Transparent image](https://github.com/0nE01/Opencv/tree/main?tab=readme-ov-file#transparent-image)
* [Water mark](https://github.com/0nE01/Opencv/tree/main?tab=readme-ov-file#water-mark)
* [Look Up Table (lut)](https://github.com/0nE01/Opencv/tree/main?tab=readme-ov-file#look-up-table-lut)
* [Video/Save video](https://github.com/0nE01/Opencv/tree/main?tab=readme-ov-file#videosave-video)
* [Thersh Hold/Adaptive thersh hold](https://github.com/0nE01/Opencv/tree/main?tab=readme-ov-file#thersh-holdadaptive-thersh-hold)
* [Morphology](https://github.com/0nE01/Opencv/tree/main?tab=readme-ov-file#morphology)
* [Connected componets](https://github.com/0nE01/Opencv/tree/main?tab=readme-ov-file#connected-componets)
* [Contur](https://github.com/0nE01/Opencv/tree/main?tab=readme-ov-file#contur)
* [Approx poly](https://github.com/0nE01/Opencv/tree/main?tab=readme-ov-file#approx-poly)
* [Color detection](https://github.com/0nE01/Opencv/tree/main?tab=readme-ov-file#color-detection)
* [Pop Effect](https://github.com/0nE01/Opencv/tree/main?tab=readme-ov-file#pop-effect)
* [Clahe](https://github.com/0nE01/Opencv/tree/main?tab=readme-ov-file#clahe)
* [Denoising](https://github.com/0nE01/Opencv/tree/main?tab=readme-ov-file#denoising)
* [Sharpening images](https://github.com/0nE01/Opencv/tree/main?tab=readme-ov-file#sharpening-images)
* [Normalizing images](https://github.com/0nE01/Opencv/tree/main?tab=readme-ov-file#normalizing-images)
* [Houghline](https://github.com/0nE01/Opencv/tree/main?tab=readme-ov-file#houghline)
* [Counting coins](https://github.com/0nE01/Opencv/tree/main?tab=readme-ov-file#counting-coins)
* [Shi-tomasi](https://github.com/0nE01/Opencv/tree/main?tab=readme-ov-file#shi-tomasi)
* [HDR](https://github.com/0nE01/Opencv/tree/main?tab=readme-ov-file#hdr)
* [Human detection](https://github.com/0nE01/Opencv/tree/main?tab=readme-ov-file#human-detection)
* [Document scanning](https://github.com/0nE01/Opencv/tree/main?tab=readme-ov-file#document-scanning)

1.  #### `Read an image`

This is the first subject we'll learn.
Basically we are using cv.imread to convert image into numpy array.

After that we can use the image and make changes or see the image. 

![alt text](https://miro.medium.com/v2/resize:fit:720/format:webp/1*wFcEuz4CtvdgJUW-mkKvZg.jpeg)

2. ####  `Cropping`

In this part we want to crop and take a part of image that we want.


![cropted opencv](https://github.com/0nE01/Opencv/assets/127254729/11bf098d-7b9a-4e12-abd7-ceb28d92bfff)

3. #### `Color channels`
   
In this part we'll see color channels in our picture that are Red Blue Green.

![color channels](https://github.com/0nE01/Opencv/assets/127254729/e6958262-86b7-445f-99f0-8a8b6f5c958c)

4. #### `Gray images`

In this part we'll convert our images into grayscale images that have only one color channel.

You can do convert images into grayscale in two ways and there's such big difference.

![download (1)](https://github.com/0nE01/Opencv/assets/127254729/81c31774-1d8d-4495-9646-dfa9df9353bd)

5. #### `Transparent image`
   
In this part we convert our image to Transparent image.

6. #### `Water mark`

In this part we will use opencv to put a water mark in the picture.

![download (2)](https://github.com/0nE01/Opencv/assets/127254729/9af73d4c-20a0-467b-801a-01d74a6ffade)

7. #### `Look Up Table (lut)`
Look Up Table is a way to change rgb color or even contrast, tones, and so on 
 
![download (3)](https://github.com/0nE01/Opencv/assets/127254729/ad576a37-84be-446a-889a-fec118b81063)


8. #### `Video/Save video`

In this part we will read video and save them.

9. #### `Thersh Hold/Adaptive thersh hold`

In this part we'll learn how to set a thersh hold for an image.

Thersh hold is a simple, yet effective, way of partitioning an image into a foreground and background.

![download (4)](https://github.com/0nE01/Opencv/assets/127254729/145a9402-f29d-49eb-9c93-77ef96a3f7b2)

10. #### `Morphology`

Morphology is a non-linear operation that correlate to the shape or morphology of features in an image.


 ![download (5)](https://github.com/0nE01/Opencv/assets/127254729/5970c8e1-e795-450b-9b52-aa46ae22b330)

11. #### `Connected componets`

In this part we'll learn how to find adjacent pixels

12. #### `Contur`
In this part we'll learn how to draw Contur in our pictures.

Contur is a curve joining all the continuous points (along the boundary), having same color or intensity.

![download (6)](https://github.com/0nE01/Opencv/assets/127254729/fa61e15a-aabf-4d55-b371-5bb0940ae071)

13. #### `Approx poly`
In this part we'll draw Approx poly in our picture.

![download (7)](https://github.com/0nE01/Opencv/assets/127254729/ff364fd6-cd9a-4fef-8a8f-2147d5544db3)

14. #### `Color detection`
    
In this part we'll find a specific color in our image.

![download (8)](https://github.com/0nE01/Opencv/assets/127254729/268707a4-2649-4b69-9e12-cc5c46f22651)

15. #### `Pop Effect`
    
This part is similar to last part but instead we find the color we want and convert other part of image to gray.

![download (9)](https://github.com/0nE01/Opencv/assets/127254729/d0685c19-4488-448a-8a02-3fef10873211)


16. #### `Clahe`
    
In this part we learn how to use Clahe.

Clahe is a algorithm can be used to improve image contrast.

![download (10)](https://github.com/0nE01/Opencv/assets/127254729/61dd4a60-3fcd-4cfa-8cfd-569814d2eb5f)


17. #### `Denoising`
    
In this part we learn how to remove noise form our picture.

![download (11)](https://github.com/0nE01/Opencv/assets/127254729/7489871a-1cfe-4f79-a68d-7b83031b1f2e)

18. #### `Sharpening images`

In this part we'ill make our image shaper.

![download (12)](https://github.com/0nE01/Opencv/assets/127254729/92ae9b73-c9ed-4a43-8b04-f9316b862078)


19. #### `Normalizing images`

In this part we'll learn how to Normaliz our image.

Normalization is a process that changes the range of pixel intensity values.

![download (13)](https://github.com/0nE01/Opencv/assets/127254729/15f05e74-93df-4322-b747-35211e95afb9)


20. #### `Houghline`

In this part we'll learn how to draw lines in our image.

Houghline is a process that can find lines in image. 

![download (14)](https://github.com/0nE01/Opencv/assets/127254729/5e949986-da7a-4d93-8425-05254eedf0c2)


21. #### `Counting coins`

In this part we'll draw Contur for coins and count amount of coins in image.

![download (15)](https://github.com/0nE01/Opencv/assets/127254729/7c001afd-bd67-44cd-9306-dac12bba61fd)

22. #### `Shi-tomasi`

In this part we will find corners in image.

Shi-tomasi used for the corner detection in the reference image.

23. #### `HDR`
    
In this part we'll learn how to use HDR in images.

We can say that HDR is a very large ratio between the brightest and darkest parts of the image.

![download (16)](https://github.com/0nE01/Opencv/assets/127254729/3a86ec9c-21c9-43b4-9e39-cb31389106e9)


24. #### `Human detection`
    
In this part we'll use yolo and detect human in image.

![download (17)](https://github.com/0nE01/Opencv/assets/127254729/ca9fa58f-20c9-4c82-9dbc-bda639487a5f)


25. #### `Document scanning`

In this part we'll learn to fix a image about Document so we can scan it.

![download (18)](https://github.com/0nE01/Opencv/assets/127254729/3047777b-0aa4-44be-8eca-d0d13f1f1f1e)


