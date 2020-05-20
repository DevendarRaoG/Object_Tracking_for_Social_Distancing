# Object_Tracking_for_Social_Distancing
In this project I've built a Social Distancing Detection Tool using Deep Learning Skills and leveraged Detectron 2 – FAIR library for Object Detection and Segmentation  from FacebookAI

#Overview
Build Social Distancing Tool using your Deep Learning and Computer Vision 
Learn how the State-of-the-Art architectures (SOTA) works for Object Detection
Hands-on with Detectron 2 – FAIR library for Object Detection and Segmentation – required to build the social distancing tool

#Introduction:
The biggest cause of concern is that COVID-19 spreads from person to person through contact or if you’re within close proximity of an infected person. Given how densely populated some areas are, this has been quite a challenge.
The only way to prevent the spread of COVID-19 is Social Distancing. Keeping a safe distance from each other is the ultimate way to prevent the spread of this disease (at least until a vaccine is found).

So i wanted to develop a social distancing tool which can effectively detect distance between people and alert.This can be used by governments to analyze the movement of people and alert them if the situation turns serious.

# Below are the steps involved in developing a tool for object detection and using for social distancing.
# Steps:
1. Install Dependencies : Pytorch, Detectron 2
2. Import libraries
3. Reading a Video
4. Download the pre-trained model for object detection from Detectron 2’s model zoo
5. Read an image and pass it to the model for predictions:
6. understand the objects present in an image &  bounding boxes of each object
7. identify classes and bounding boxes related to only the people
8. Understand the format of the bounding box
9. Draw a bounding box for one of the people
10. compute the distance between two people in an image using bounding box
11. Define a function that returns the bottom center of every bounding box
12. Compute the bottom center for every bounding box and draw the points on the image
13. Define a function to compute the Euclidean distance between every two points in an image
14. Compute the distance between every pair of points
15. Define a function that returns the closest people
16. Set the threshold for the proximity distance
17. Define a function to change the color of the closest people to red
18. Carry out similar steps on each and every frame of the video
19. Define a function that performs all the steps we covered on each and every frame of the video
20. Identify the closest people in each frame and change the color to red
21. After identifying the closest people in each frame, convert the frames back to a video. 
That’s it!
