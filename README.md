###Purpose:
To create a user guide and learning content for people to learn arduino (C++) and microcontrollers with the Pi Bot.The course will be marketed under the general message of : **Build, play, and learn technology with robotics!** Build and program an awesome PiBot and learn fantastic skills: inc. programming, physical computing and robotics!

###Objectives:
Empower and educate future engineers with knowledge and skills in arduino and microcontrollers. This is in integral to the PiBot learning platform that also integrates Physical computing and robotics with the Raspberry Pi.  
Learn physical computing and about key hardware including actuators ( lights, servo’s , stepper motors, dc motors, speakers, tft screens etc) Sensors ( distance sensors, encoders, temperature sensors etc.)
Learn to program using a wiring ( a subset of C++). Learning to think programmatically. 
Learn core knowledge and principles of Information Technology and its relationship to Hardware. (inc. hardware protocols such as SPI, I2C etc)
Learn the basics of programming in C. 
This work will integrate into a complete set of learning material that will include lessons in using linux, programming languages, electronics, digital making and creation. 

I suggest the material can be developed here on GitHub.  Basic formatting can be done using Github Flavored Markdown and can be converted to HTML later. (A basic guide to the Markdown can be found [basic writing and formatting syntax:] (https://help.github.com/articles/basic-writing-and-formatting-syntax/). 

###Course Content:
The Arduino IDE will be used to **learn-by-doing** as the learner programs the microcontroller and develops robot powers!  Starting from the basics of controlling a single LED we'll progressively learn to control more and more sensors and actuators. Simultaneously the learner will develop skills in physical computing, electronics, as well as robotics and general information technology. 

The goal will be to learn to command every part of the robot and do this in a co-ordinated way. This will extend to completing an API for the robot and commanding the robot from Python on the Raspberry Pi. This will enable the final task of the course that will be to control the robot remotely over the network or internet.  

###Suggested Lessons: 

The lesson plan has been developed and now resides as an index to this repo.  Please see the **index.md** file for this.  For reference the initial lesson plan has been appended to the end of this page. 



### Developing Content:
The content will be textual with pictures to illustrate and enhance the learning.

[Fritzing](http://fritzing.org/home/) will be used to show breadboard layout and the setup of components. It will also be used to set up the schematic view.  As far as possible Illustrations will be made in **SVG** format for great page loading and clarity.   
I will create a good looking plan of the PiBot board. 

As stated the content will be made using Markdown and converted to HTML5 later for injection onto the PiBot website.

##Users:  
Who is this for: future engineers and computer scientists: The content will be made for someone wanting to learn robotics, physical computing, and IT with the PiBot.  It is designed for learners from the age of 13 and upwards and should include adults as well. If the content would serve and make sense to someone like you then that would work! As the audience and user base becomes clearer and known the content can always be optimised and adjusted to suite. 


##Delivery:
In the first delivery phase it will be taught as part of an 8 weeks course. This will be the opportunity to test the content and get feedback from it.  The course final release will be delivered online through a web app/ website. This will be developed from now and all content will be presented as part of a website as soon as possible.  The course material will be hosted on GitHub. A convention will be made used for the text and content and the material will be automatically pushed online to a beta environment. 

####Legacy Initial Lesson Plan 
1. Writing your first sketch: Make a sketch to make an LED blink
On the breadboard connecting a resistor and led 
Control the onboard led.   (explain the difference between breadboard components, and SMD components)
2. Using PWM to control the brightness of the LED. Make a new sketch that adds 
3. Using PWM to control a servo (Also explain what a servo is)
4. Controlling DC motors.  Powering your robot! 
4b. Libraries and using code in a modular way. Learn the benefit of libraries and modular design. Turn previous lessons (leds, servos, DC motors) into libraries and make sketch that combines all of them into one. 
5. Controlling a Stepper Motor 
6. Controlling  a neopixel. A neopixel uses 3 colored leds in a tiny package. By altering 
Now we will learn about sensors and taking information in from the world
7. Ultrasound.  Learning to measure distance 
8. Measuring Temperature 
-Potential Additions:
-Measuring Humidity ,
-3 Axis accelerometers 
-IMU
-Digital compass
-GPS modules
-Encoders 
