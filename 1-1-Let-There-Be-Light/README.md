## Let there be light! 

**Wire up an LED and make it blink! ** *What is a MicroController?*

####About 
The idea is to get a user engaged and doing some thing quickly. Knowledge and skills will be given as the learner progresses.

####Setting Up The PiBot Learning Environment

The course is to be engaged with using:
- a working raspberry pi set up 
- the pibot development kit (breadboard, components etc)
- the ardunio IDE set up and working on the Raspberry Pi.
- a seperate interface to engage with the learing content. 

###### Working Raspberry Pi 
The Raspberry Pi should be built with a keyboard, mouse and monitor connected. The PiBot IO board should be attached and screwed into position on the Raspberry Pi.  The system should either be powered from an external power source through the Raspberry Pi's 5V micro USB power input or through the PiBot IO board and an Integrated PiHero Power Module. 

###### Development Kit
The PiBots breadboard and components should be laid out nearby and ready for use. 

#####Software Environment
This course uses a customised Arduino IDE that has been pre-configured and setup for use with the PiBot IO board. This is where code is inputted and sent to the microcontroller.   (Poss This is either available on an SD card provided with your PiBot kit or can be downloaded and istalled from source at the [PiBot Github repo - to be incldued later](To be included later).

###### Seperate Inteface for Learning Content
Unless the learners are using very big or multi-monitor displays it makes sense to prepare all the learning content for delivery through a web browser.  This can then be viewed and engaged with on a separate device whether that is a laptop, or tablet computer. An Ipad or android tablet could be considered as an ideal device for this. 


###Presentation of Content
Robotics in multi-disciplined as are the skills that people increasingly value in work. For example to be a good architect communication and management skills may be just a important as drawing or technical knowledge. Increasingly its valuable to learn technology *at the same time* as other skills. This course intends to give great value by facilitating and inspiring learning in several areas at the same time.  Our task is to find the best way to present, integrate, or blend these different areas of learning together.  

Whilst the delivery interface is not yet complete we can already consider make distinctions between different areas of learning. This, for example, could be then be presented on diffferent tabs. e.g.:
-**Physical Computing**. Laying out and connection of physical components 
-**Coding**. Using the arduino IDE to learn C and programming.
-**Electronics** Learn about the electronics at play in the lesson.
-**IT & Robotics** Learn key theory and information technology aspects to the lesson. 

When this course is delivered teachers/educators can choose what they would like to include as well as being able to customise the  the content.  (e.g. they could remove the electronics tab if they did not want to include this).


###Lesson Content Start


##1-1-1 Getting Started

Microcontrollers are complete computer systems-on-a-chip designed for measurement, command, and control. In this first step we'll place  an illuminating LED into a circuit and use the microcontroller to control it.  

Take out your breadboard and connect it to the PiBot IO board.  (See fig. 1).  Now take a red LED and 1k Resistor and create a circuit like the one shown in fig. 2. The Positive Voltage Rail is connected to oneside of the resistor and the PiBot IO 's ground pin is connected to the tail pin of the LED.  Please note that the LED needs to be connected the right way round for it to work. It has one leg longer than the other and this needs to connect to the positive side ( the side on the same rail as the resistor).

###How does a breadboard work?
A breaboard allows you to make electronic circuits with out soldering or making any permenant connections. It is ideal for making prototypes and testing designs. Underneath the cover of the breadboard are a number of metal strips that the pins of divices slot into. These strips run vertically and all holes along the same strip are connected electrically. By placing components in the breadboard we can create elecrical circuits that work.  Please see the Electronics tab for detailed knowledge of all the electronics at play in this example. 




##Eletronics Tab - Resistors, LEDs, and Making Simple Circuits 
This exercise connects a simple circuit to the PiBot IO board and arduino microcontroller.  Electronics is about connecting various components together in order to create a particular function.  As we saw in the intro the breadboard is for prototping and for testing designs. You may be curious how to make permanent circuits of complete products so I'll'  Explain whats involved in electronic prototying and manufacture. 
Then Go through the electronics involved in each component
###Resistor
###An LED is (Light Emitting Diode)
###Gnd and VCC

###The Schematic for the device: 
Display and Discuss Schematic View


##Coding Tab
Getting started with the arduino IDE and uploading your first sketch.
Intro to the IDE and the first sketch:

##Robotics Tab - Inner Workings of a Microcontroller.  
The PiBot uses a microcontoller 



Fig 1_2 block diagram of the system on Chip (SOC)
 The CPI (Central Processing Unit)  processes and runs the code given to it. It takes instructions stored in the flash memory and will also read and write to the Random Access Memory. The processor also controls all the IO determining each pins state, configuration, and changes. 
The EEPROM memory is non-volatile and is preserved between powering the system on or off or any resets. 
Clock 
The small silver rectangular component is a quartz chrystal oscillillator.  This cycles 16 million times per second giving the processors frequency of 16 MHz. In each of the 16 million ticks the computer can perform a single operation.

Reset switch. 
The last piece of hardware to note is the microcontrollers reselt switch. This sends a pulse on the microcontrollers reset pin and is used to reset the system. 

Finally the Micronctrollers Serial bus is connected directly to the serial output of the Raspberry Pi.  This means that both system are directly connected over the high-speed  serial connection.


