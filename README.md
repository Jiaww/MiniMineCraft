# MiniMineCraft
Final Project of Computer Graphics, developed by ***Jiawei Wang, Kaixiang Miao, YiGuo***.

CGGT, Upenn
## Screenshot
![](screenshots/screenshot01.png)
## Description
`C++` `OpenGL4.0` `Qt Creator`

Besides the basic features of the MiniMineCraft, we also implemented Biomes, Skybox, Weather system, Shadow mapping, Day and night cycle, Fire and GUI. 
## Results
### Biomes
![](screenshots/screenshot02.PNG)
### Skybox
![](screenshots/screenshot03.PNG)
### Weather system
* Geometry Shader
  *  Calculate the local axis of the point
  *  Expand the point sprite to a billboard

![](screenshots/screenshot06.PNG)
### Shadow Mapping
* Directional Light
* Optimization
  * A **bias** to solve the shadow acne
  * **Cull Front Face** for shadow depth rendering to solve peter panning 
  * **PCF** to make the shadow more smooth

![](screenshots/shadowMapping.PNG)![](screenshots/shadowMapping2.PNG)
### Day and night Cycle
* Not only the light intense will change, also the direction
![](screenshots/lightdireciton.PNG)![](screenshots/lightdirection.PNG)![](screenshots/lightdirection2.PNG)
### Fire and GUI
* The fire will spread along the grass
![](screenshots/screenshot04.png.jpg)![](screenshots/screenshot05.png.jpg)
