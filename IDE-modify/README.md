#Modify the Arduino IDE 
Here we'll explain how the Arduino IDE can be modified to work with the PiBot.
####Approach 
We wanted to modify the IDE to simplify its options and add some unique styling.
- create a unique PiBot board configuration and make it the IDE 's default instead of the *UNO*.. **Boards.txt**
- Create a custom way to program the microcontroller using a **RasPi ISP**
- Replace the default **Examples** directory with support files for the learning system
- Replace the default **Libraries** directory with ones specific to the PiBot.
- **preference.txt** Here we'll customise some settings 

### File locations
The **preference.txt** is found in 
```
~/.arduino
```
### Modifying the Examples and Libraries Directories
The Examples Directory is replaced with the 4 learning sections for the tutorials.
This is done by replacing files in the default **/usr/share/arduino/examples** directory:

```
mv /usr/share/arduino/examples /usr/share/arduino/examples-original
```

Then we can replace with the examples from the repo:

```
mv /location/of/arduino-tutorials/examples /usr/share/arduino/examples
```

See the seaxples-original folder for how the directory is organised.

### Modifying the Libraries Directories
The Libraries Directory contains a **Test-hardware** library that is used to test all the robots hardware. 

