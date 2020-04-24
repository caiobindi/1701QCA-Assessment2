# 1701QCA Making Interaction - Assessment 2 workbook

You will use this workbook to keep track of your progress through the course and also as a process journal to document the making of your projects. The comments in italics throughout the template give suggestions about what to include. Feel free to delete those instructions when you have completed the sections.

When you have completed the template, submit the link to the GitHub Pages site for this repository as a link in Learning@Griffith. The link should be something like [https://qcainteractivemedia.github.io/1701QCA-Assessment2/](https://qcainteractivemedia.github.io/1701QCA-Assessment2/) where `qcainteractivemedia` is replaced with your GitHub username and `1701QCA-Assessment2` is replaced with whatever you called the repository this template is contained in when you set it up.

## Project working title ##
Mini Hoop Automatic Score Board

## Related projects ##
*Find about 6 related projects to the project you choose. A project might be related through  function, technology, materials, fabrication, concept, or code. Don't forget to place an image of the related project in the appropriate folder and insert the filename in the appropriate places below. Copy the markdown block of code below for each project you are showing.*

### Related project 1 ###
Automatic Arduino Goal Counter for Table Football/Soccer

https://www.youtube.com/watch?v=WqkIgd9vjbk

![Image](related1.PNG)

This project is related to mine because it has the same function and concept. They both are used to automatically count a score when playing a game.

### Related project 2 ###
Automatic Basketball Score Board

https://www.sitepoint.com/create-an-automated-scoreboard-that-senses-your-score-with-a-raspberry-pi/

![Image](related2.PNG)

This project is related to mine because it has the same function, concept and technology. They both are used to automatically count a score when playing a game. They also both are using a sensor to detect the ball going through the hoop. 

### Related project 3 ###
Automated Cornhole Scoring System

https://www.youtube.com/watch?v=AZAraY28n6E

![Image](related3.PNG)

This project is related to mine because it has the same function and concept. They both are used to automatically count a score when playing a game.  

### Related project 4 ###
Smart Basketball Scoreboard

https://create.arduino.cc/projecthub/marceloavilaoliveira/smart-basketball-scoreboard-f922cb

![Image](related4.PNG)

This project is related to mine because it has the same function, concept and technology. They both are used to automatically count a score when playing a game. They also both are using a sensor to detect the ball going through the hoop. This one is more advanced than mine because they are using a smart phone to display the score.

### Related project 5 ###
Touchless Automatic Motion Sensor Trash Can

https://www.hackster.io/will-su/touchless-automatic-motion-sensor-trash-can-bbeed1

![Image](related5.PNG)

This project is related to mine because it has the same Technology. They both use motion sensors to detect movement.

### Related project 6 ###
Security System

https://www.hackster.io/alpha/security-system-2188de

![Image](related6.PNG)

This project is related to mine because it has the same Technology. They both use motion sensors to detect movement.

## Other research ##
*Include here any other relevant research you have done. This might include identifying readings, tutorials, videos, technical documents, or other resources that have been helpful. For each particular source, add a comment or two about why it is relevant or what you have taken from it.*
https://www.safewise.com/resources/motion-sensor-guide/
I first looked a motion sensors but figured it would be too difficult.

https://www.elprocus.com/infrared-ir-sensor-circuit-and-working/
This was a reading about how IR sensors work. It gave me a better understanding of how to use them. It is relevant to my project beacuse I am using an IR sensor.

### *Brief resource name/description* ###

*Provide a link, reference, or whatever is required for somebody else to find the resource. Then provide a few comments about what you have drawn from the resource.*

## Conceptual progress ##

### Design intent ###
A game were it automatically counts the score when you make a shot.

### Design concept 1 ###
Basketball Bounce Tracker

![Image](concept1.jpg)

The purpose of this this counter is to count the amount of times the ball is bounced. This will be done by using a micro:bit which will be attached to the ball and each time the ball hits the ground the mirco:bit will detect impact and add a number to the LED display.  

*Outline three design concepts, each developed to a point where you anticipate it would be feasible to complete by the end of the course. Each should have a summary of the idea, a rough sketch of what it might be like, and any other notes you created while exploring the idea.* 

*Put the first two design concepts in the sections "Design concept 1" and "Design concept 2". Then put the third, with more development in the section "Final design concept".*

### Design concept 2 ###
Interactive Noughts and Crosses

![Image](concept2.jpg)

This will be played like normal but will be more modern. Instead of drawing a nought or a cross you either single or double click a button (single click noughts, double tap crosses). When placed an X or O will be displayed on the micro:bit led display. 

### Final design concept ###
*This more fully developed concept should include consideration of the interaction scheme, technical functionality, fabrication approach, materials to be used, and aesthetic.*

Mini Basketball Automatic Score Board

![Image](concept3.jpg)

This project will be a game were the aim is to score as money points as possible in under 30 seconds. How this will work is there will be a sensor right under the rim. I am still experimenting one which type of sensors I will use. The two main ones I'm testing is a light sensor and IR sensor. What I am thinking for the 30 second timer is when it runs out, the score will go back to 0 and it will make a noise. If I do chose to use a IR sensor I will have to purchase that and a micro:mate (breakout board). For the hoop itself I am going to construct one out of wood. The experience of the user will connect with the functionally of the project via vison and sound.

### Interaction flowchart ###
*Draw a draft flowchart of what you anticipate the interaction process in your project to be. Make sure you think about all the stages of interaction step-by-step. Also make sure that you consider actions a user might take that aren't what you intend in an ideal use case. Insert an image of it below. It might just be a photo of a hand-drawn sketch, not a carefully drawn digital diagram. It just needs to be legible.*

![Image](missingimage.png)

## Physical experimentation documentation ##

*In this section, show your progress including whichever of the following are appropriate for your project at this point.
a.	Technical development. Could be code screenshots, pictures of electronics and hardware testing, video of tests. 
b.	Fabrication. Physical models, rough prototypes, sketches, diagrams of form, material considerations, mood boards, etc.
Ensure you include comments about the choices you've made along the way.*

*You will probably have a range of images and screenshots. Any test videos should be uploaded to YouTube or other publicly accessible site and a link provided here.*

![Image](score.PNG)

This is the code for the score board. I am unable to test it yet because I do not have the IR sensor micro:mate

![Image](timercode.PNG)

This is the code for the timer. I have tested it and it's working. I just figure out a way to incorporate with the score board code.

https://youtu.be/TczXaRjO0-s

![Image](concept3.jpg)

This is my design so far for the hoop. The micro: bit will be in the centre were it is easily to see the score. The IR sensor will be located right under the hoop so it senses the ball when it goes in. 

## Design process discussion ##
*Discuss your process in getting to this point, particularly with reference to aspects of the Double Diamond design methodology or other relevant design process.*

## Next steps ##
*Write a list or provide other information about your plan to move the project forward to be ready to present by video and documentation in week 12 of the course.*
