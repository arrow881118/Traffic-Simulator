# TRAFFIC SIMULATOR

This is a project built by college students.<br></br>
There are three members in the team, which is 劉芷言, 陳羽綸 and 王品家.

## Introduction

 A traffic system, i.e., vehicles spawn randomly in multiple traffic scenarios,  and a user-behavior detecting system with Unity, which educates users by reporting their mistakes on their behaviors in specific traffic conditions after driving the user's vehicle to the destination, with two control types: Logitech G29/Keyboard.
 
## Traffic System

In order to accomplish the idea, built the fundamental object is the great way to start with, which is a car with radar. So that these cars could detect each others and more important, the path and intersection.

<img width="875" alt="車輛雷達標示" src="https://user-images.githubusercontent.com/67034993/234522673-e27e0110-6619-4606-8a89-ba41e01dff3a.png">

After built a functional car, we still have to keeps it in the path we designed. For this purpose, we could create an editor to do so. Create dots on the road we bulit, connect the dots to form a line, then our path are done. 

When path were built and cars could follow the path we gave, we still need a object to detect every cars in the intersection. To do this, we built a invisible box cover the whole intersection, which keeps the record of every traffic light, so that when cars collide with the box it, it could sent the car a signal whether to drive of stop.

![image](https://github.com/holydarktank2/Graduation-Project/blob/main/screenshots/Screenshot3.gif)

This is the demo video of the working traffic system.

https://user-images.githubusercontent.com/67034993/234222745-c4a60f85-8442-4533-8e84-7b8cb9afc5a5.mov

## Behavior Detected System

We bulit the detect system in user's vehicle and placed certain type of checkpoint in different scenarios(the green objects are the checkpoint that user are forbid to collide).

![擷取_2021_10_05_17_29_16_511](https://user-images.githubusercontent.com/67034993/234535028-cf7d51b8-a7c4-4479-9271-7c0e34fefab6.png)
 
This is the demo video of user collide with the object that there are not allow to(other vehicles, divisional island and double yellow line respectively).

https://user-images.githubusercontent.com/67034993/234541091-85d7c65c-59b7-453e-a1ac-b0dd8850c043.mov

This is the demo video of detect system keeps the unfullfull mission in record. The mission is "change to inside lane before you went into left turn lane"(notice : user will failed if they did not use the indicator).

https://user-images.githubusercontent.com/67034993/234542910-0e482b3a-4959-46fe-87ec-d293998d4e40.mov

This is the demo video of education mode, which enable user to see where the checkpoint is, so that they could learn the right and approciate way to drive. 

https://user-images.githubusercontent.com/67034993/234547627-7a25dadb-058a-45c2-b721-291091f54d43.mov

This is the demo video of user finish the level but fail to accomplish all missions(failed on did not follow the lane he/she should be or driving on line).

https://user-images.githubusercontent.com/67034993/234556254-23e93ab0-195c-44a2-9031-91bca275418b.mov

## Contorl Types

Logitech G29 or Keyboard

## Set-Up

https://user-images.githubusercontent.com/67034993/234560690-f9247c58-43c0-46d3-9bb6-2249bf58edc3.mp4

https://user-images.githubusercontent.com/67034993/234560925-a0812315-dba5-4490-b0ee-226d68984125.MOV



## Photos
![IMG_6030 2](https://user-images.githubusercontent.com/67034993/234576028-c3a65d2f-91fa-4af0-9a45-7c1e2c58d889.JPG)


![IMG_6049](https://user-images.githubusercontent.com/67034993/234576045-7884c5cf-36fb-4d82-8cc0-c3c0c0972d01.JPG)

