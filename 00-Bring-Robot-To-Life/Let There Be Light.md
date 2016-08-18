## Let there be light! 

**Wire up an LED and make it blink! ** *What is a MicroController?*




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
The PiBot uses an arduino compatible microcontoller chip (model 328P). There are kinds of microcontrollers and the 328P is perhaps the best and most widley used microcontroller for getting started with.    



Fig 1_2 block diagram of the system on Chip (SOC)
 The CPI (Central Processing Unit)  processes and runs the code given to it. It takes instructions stored in the flash memory and will also read and write to the Random Access Memory. The processor also controls all the IO determining each pins state, configuration, and changes. 
The EEPROM memory is non-volatile and is preserved between powering the system on or off or any resets. 
Clock 
The small silver rectangular component is a quartz chrystal oscillillator.  This cycles 16 million times per second giving the processors frequency of 16 MHz. In each of the 16 million ticks the computer can perform a single operation.

Reset switch. 
The last piece of hardware to note is the microcontrollers reselt switch. This sends a pulse on the microcontrollers reset pin and is used to reset the system. 

Finally the Micronctrollers Serial bus is connected directly to the serial output of the Raspberry Pi.  This means that both system are directly connected over the high-speed  serial connection.


