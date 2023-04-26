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



## Contorl Types

Logitech G29 or Keyboard

## Set-Up


## Screenshots

![image](https://github.com/holydarktank2/Graduation-Project/blob/main/screenshots/Screenshot1.PNG)
![image](https://github.com/holydarktank2/Graduation-Project/blob/main/screenshots/Screenshot2.PNG)
