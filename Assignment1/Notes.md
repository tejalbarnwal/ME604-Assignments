# Assignment 1

## Question 6
The ABB IRB1600-8/1.45 robot resembles the robot given in question 5. So, except the link lengths, the configuration of the robot remains the same.

`funcA` contains the function written to calculate transformation between two consecutive frames given the DH parameters. 
Using this function, calculation of T is performed where, T represents the transformation matrix calculated manually.

Output T is shown in the following image - <br>
<p align="center">
  <img src="https://user-images.githubusercontent.com/64950661/152683603-0eafd431-f7d5-466e-bdfc-13a5e244af66.png">
</p>

Further, using the robotic toolbox a serial robotic arm is created with the same DH parameters. The output for the same is shown below -
<p align="center">
  <img src="https://user-images.githubusercontent.com/64950661/152683621-60ab9f1c-0688-4586-be21-c1a29aacdd8f.png">
</p>


The following figure represents the confihuration of the robot provided all joint angles are 0
<p align="center">
  <img src="https://user-images.githubusercontent.com/64950661/152681942-63d66bf8-af28-413a-9f49-17b8779b2825.png">
</p>

`fkine()` is used to calculate the forward kinematic transformation between the end link and the base link given the six joint angles. The output for the same is shown below-
<p align="center">
  <img src="https://user-images.githubusercontent.com/64950661/152683647-a8bf671b-11bb-48ae-b5cf-2be3c4971cd8.png">
</p>


 
