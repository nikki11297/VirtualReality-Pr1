# Dream Restaurant Project
## Virtual-Reality---CS-5331---Project-1
### Introduction:
Project 1 focuses on creating a human scale scene experienced from the 'inside out'. This project gives me an opportunity to design and express my opinion on how COVID-19 changed the situation. So, it gave me the idea of a restaurant and how it is managing covid-19 situations. My project includes 10+ unique models, user controllable objects (like clicking to trigger music), dynamic object to interact with and user navigation.

### Video Demonstration:
https://youtu.be/J_1kfRx1QV4

### Try it out:
https://nikki11297.github.io/VirtualReality-Pr1/

https://glitch.com/~nikki-vr-project

### Theme:
•	My theme of the project is to make a tiny restaurant where I can be able to show the 6 feet distancing. I did the blue theme as it looks pleasant as well as colorful.
### Description:
 
•	This application is written in HTML, A-Frame.

•	First, I create the walls which I used a box and given a texture of a floor was implemented to create the base of the house. Sample piece of code is given below for the walls.
```
<a-entity id="Wall1F" position="1.5 2 -15" rotation="0 0 0" geometry="primitive: box; width: 22; height:6 depth: .1"
            material="src:https://cdn.glitch.com/74e63c0c-df5a-4f88-a0dc-e7118cf071c5%2Fwallf.jpg?v=1601489682401; repeat: 3 2"></a-entity>    
```

•	The ceiling of the house was created by using the a-entity tag with a geometry of a box and given specific attributes and texture. 
```
<a-entity id="Ceiling" position="1.5 5 -4.5" rotation="-270 0 0" geometry="primitive: plane; width: 22; height:23"
            material="src:https://cdn.glitch.com/74e63c0c-df5a-4f88-a0dc-e7118cf071c5%2Fceiling.jpg?v=1601390595860; repeat: 12 12"></a-entity>
```
•	To decorate the restaurant, I used obj models were used to fill the restaurant. I used blender and I made fan. All of these were loaded as obj-model.
```
  <a-asset-item id="CeilingfanO" src="https://cdn.glitch.com/74e63c0c-df5a-4f88-a0dc-e7118cf071c5%2F540%20Ceiling%20Fan.obj?v=1600809501621"></a-asset-item> 
  <a-asset-item id="CeilingfanM" src="https://cdn.glitch.com/74e63c0c-df5a-4f88-a0dc-e7118cf071c5%2F540%20Ceiling%20Fan.mtl?v=1600809493474"></a-asset-item>
  <a-entity rotation="0 0 0" position="0 4.3 -1.5" scale=".007 .003 .007" obj-model="position:0 4.3 -1.5;obj:#CeilingfanO; mtl:#CeilingfanM"  class="intersectable" >
            <a-animation attribute="rotation"
               dur="3000"
               from="0 0 0"
               to="0 360 0"
               easing="linear"
               repeat></a-animation></a-entity>
  ```
      
### Standard Models
Drums (image 1)

Dog Bowl (image 2)

Dog Biscuit(image 2)

Door (image 3)

Flower Table(image 1)

Icecream(image 4)

Juice pointe (image 4)

Mask (image 2)

Orchid(image 1)

Popcorn (image 5)

popcorn stand (image 5)

Sofa (image 2)

Stereo (image 1)

Sanitizer(image 1)

6-feet distance posters (all images)

TV(image 1)

Tables(image 1)

Wending machine (image 4)

Window(image 5)


### All the objects that the user can interact with are listed below.

• The user may interact with tavern, when user click tavern will appear(image 6)

• The user may interact with dog, when suer click on the dog , dog will move from its place. (image 7, 8)

• The user may interact with gramophone which plays music when you click on the slide of gramaphone. (image 3)

### Animation used
• There are three different color lights with different intensilty near the drums(image9 , 10)

• Dymanic object is the fan, tavern , dog and lights. ##Please click on tavern, dog, gramaphone(for music)

### All the pictures are shown below.
image1
![alt text](https://github.com/nikki11297/VirtualReality-Pr1/blob/master/image1.png)
image2            
![alt text](https://github.com/nikki11297/VirtualReality-Pr1/blob/master/image2.png)
  image3                 
![alt text](https://github.com/nikki11297/VirtualReality-Pr1/blob/master/image3.png)
       image4               
![alt text](https://github.com/nikki11297/VirtualReality-Pr1/blob/master/image4.png)
  image5             
![alt text](https://github.com/nikki11297/VirtualReality-Pr1/blob/master/image5.png)
     image6              
![alt text](https://github.com/nikki11297/VirtualReality-Pr1/blob/master/image6.png)
     image7               
![alt text](https://github.com/nikki11297/VirtualReality-Pr1/blob/master/image7.png)
image8            
![alt text](https://github.com/nikki11297/VirtualReality-Pr1/blob/master/image8.png)
image9
![alt text](https://github.com/nikki11297/VirtualReality-Pr1/blob/master/image9.png)
image 10
![alt text](https://github.com/nikki11297/VirtualReality-Pr1/blob/master/image10.png)
image 11
![alt text](https://github.com/nikki11297/VirtualReality-Pr1/blob/master/image11.png)

### Conclusion
In conclusion, I think that this project was a good stepping stone into learing how to code in virtual reality.Some improvements I would like to make is making an outside area, and making multiple levels(upstairs and downstairs). A learned the basics of aframe and I now feel confident in my ability to code using it. I plan on coming back to this project in the future and improving it even more.
                
