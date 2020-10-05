# Dream Restaurant Project
## Virtual-Reality---CS-5331---Project-1
### Introduction:
Project 1 focuses on creating a human scale scene experienced from the 'inside out'. This project gives me an opportunity to design and express my opinion on how COVID-19 changed the situation. So, it gave me the idea of a restaurant and how it is managing covid-19 situations. My project includes 10+ unique models, user controllable objects (like clicking to trigger music), dynamic object to interact with and user navigation.

### Video Demonstration:

### Try it out:

### Theme:
•	My theme of the project is to make a tiny restaurant where I can be able to show the 6 feet distancing. I did the blue theme as it looks pleasant as well as colorful.
### Description:
 
•	This application is written in HTML, A-Frame.

•	First, I create the walls which I used a box and given a texture of a floor was implemented to create the base of the house. Sample piece of code is given below for the walls.

<a-entity id="Wall1F" position="1.5 2 -15" rotation="0 0 0" geometry="primitive: box; width: 22; height:6 depth: .1"
            material="src:https://cdn.glitch.com/74e63c0c-df5a-4f88-a0dc-e7118cf071c5%2Fwallf.jpg?v=1601489682401; repeat: 3 2"></a-entity>    

•	The ceiling of the house was created by using the a-entity tag with a geometry of a box and given specific attributes and texture. 
<a-entity id="Ceiling" position="1.5 5 -4.5" rotation="-270 0 0" geometry="primitive: plane; width: 22; height:23"
            material="src:https://cdn.glitch.com/74e63c0c-df5a-4f88-a0dc-e7118cf071c5%2Fceiling.jpg?v=1601390595860; repeat: 12 12"></a-entity>
      
•	To decorate the restaurant, I used obj models were used to fill the restaurant. I used blender and I made fan. All of these were loaded as obj-model.

All the objects that the user can interact with are listed below.

• The user may interact with tavern.
• The user may interact with dog
• The user may interact with gramophone which plays music when you click on the slide of gramaphone.

Animation used
• There are three different color lights with different intensilty near the drums
• Dymanic object is the fan, tavern , dog and lights.

All the pictures are shown below.







