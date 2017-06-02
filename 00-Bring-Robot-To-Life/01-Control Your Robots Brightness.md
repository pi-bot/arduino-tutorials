### Control Your Robots Brightness

In the first lesson we ran a sketch without knowing how its code works or hows its sent to the robot. Here is where we'll begin to learn to speak robot using a proper programming language. Arduino sketches are written in a version of the C language. Lets see what happens if we type some normal text into the Ardunino IDE and send it to the microcontroller.  In the Arduino IDE open up a new file and type the following:

```
What kind of robot are you?
```
If we press *upload* we'll see there's some problems with this:  

The Arduino IDE checks the code to look for errors and it will complain if there are any issues. Finding  **errors** and **fixing errors** are a major part of programming and its very helpful for our development environment to catch these errors. (IDE stands for Integrated Development Environment).    You can see that with our natural human text the IDE is not happy:

```
Put Error Code HERE
```
### Learning robot lingo
Machines do not yet speak English, Spanish, or other human languages.   Programming languages are made to communicate with machines and there are many programming languages that can be learnt.   Fortunately learning programming languages is much easier than learning a  languages, and it doesn't need to take long to learn the language of robots. 

All you need to do is follow the rules of the language and practice writing code.   As soon as you learn the language you'll be  commanding your robots in no time at all! 

The following steps are focused on giving you the foundations and basics of programming in C. For more details of the particular language wer're using and how that compares to other languages please see the **programming** tab. 


##### HOT TIP
In the world of humans you don't need to speak or write correctly to be understood (though it sometimes helps!).  The world of machines is different where precision and correctness is extremely valuable.  Errors in code are the biggest cause of problems and losses of time.  For this reason it really pays to take care and bring attention to detail to your coding. This requires patience and focus though believe me, getting in the habit of this now will save time and grief in the future.

So the IDE did not like our human readable text so now lets see what happens if we simply upload acompletley blank document. Delete all the text in your text and upload to the micro controller. 

```
Error Message HERE
```

Again the IDE throws an error. 

Now open **step3.ino** (replace with proper name later). And try uploading this.  Whilst this sketch doesn't have a single useful command it does enough for the IDE code checker to be uploaded to the microcontroller without error. 

```
Binary sketch size: 444 bytes (of a 32,256 byte maximum)
```

#### Sketch fundamentals
Lets look closer at the standard code that forms the basis of every working sketch. Firstly lets look at the comments:

```
Comments section put here
```

In most programming languages specific character combinations are used to signify comments. These are ignored by the compiler (or parser) and they are used only to help us humans.  In C a multi-line comment is started with **/\*** and ended with **\*/** and single line comments are signified with **//**.  Use comments as much as you can to help yourself and others understand and follow your code.

The first non-comment section is :

```
Void setup() {
}
```

This shows the correct syntax for declaring (or creating) a function called **setup**.  In arduino some functions like **digitalWrite** are already defined so there’s no need to define them in your sketch. You must *or* can define other functions for yourself.  **setup** and **loop** are the two functions you must declare in every sketch that you write and together these form the basic structure of an arduino sketch. 

{ figure showing the  statement with explanations}

N.B. Add explaniation inspired by SM intro book p34 in here:
The word “void” indicates that nothing is returned by the function. Some functions return values whiles others do not. 

#### Learn To Get The Help You Need
It is possible to learn just about anything from freely available resources on the internet. The key question is knowing which resoruces to use. This course is complete and we believe provides the fastest and most powerful way to learn. There is though one  resource that we recommend is used for enhancing and suporting your learning on this course. 
- [Arduino Language Reference](www.arduino.cc/en/Reference/Setup) This is a concise and well written guide on the arduino language. As the course prgresses we'll refer to relevant pages on it. Please end by taking a look at the Language Reference Site and the descriptions for the **setup()** and **loop** functions in particular.  As the course progresses further references will be made to this resource. 


## Programming Section

The arduiono uses a subset of the C language. C is one of the most prolific and widely used languages in the world. The arduino subset of this makes it easier to learn the language quickly and start using it with physical computing.  All the code your learn for programming an arduino will form a solid basis for learning and extending your knowledge of C and many other related languages. The syntax and patterns of C have influenced many other languages including C++ python and javascript. This makes it quicker to learn other languages once you have become familiar with C. 

#### What Kind Of Language is C?
 C is a compiled language that maps efficiently to machine instructions.  This ‘lower level’ language was first made to create the Unix Operating System in the early 1970’s.  IT is well suited for replacing applications that before would have used assembly language.  It is widely used for coding operating systems, as well as various applications for a wide range of systems, from supercomputers to small embedded systems. It has been around since the 70’s and is very standardized and stable.  Most of the code and applications on your Raspberry Pi, including Linux has been written in C. 




#### Random Notes Not sure what to do with this


An example of a function that does return a value :

Int Double ( int num) {
Return num*2;
} 

From the above you can see int being used to state that the function both takes as interger called num as a parameter and also returns an integer. Don’t worry if you don’t know yet what an integer is as this will be explained in step3. 


See the Arduino Language Reference for further functions.

Questions :
What does the isDigit() function do:
A)
B)
C)

What unit of time does the delay() function take as a parameter?

A) seconds 
B) milli seconds
C) hours 


