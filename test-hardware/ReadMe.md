#Testing the PiBot hardware
This is used initially to test the PiBot board as well as all associated hardware. The test covers:

1. booloader (check that the bootlader can be burt to the micro) PASSED 
2. t-serial upload (Check that Pi can upload a sketch by serial interface) PASSED
3. t-blink (test that the IDE can run the blink sketch on pin D12)
4. t-digitalPins (test all the pins digitally, as pins turn high or low a voltmeter is used to check the actual value)
5. t-PWM (test PWM on D5 and D6) 
6. t-Interupts (test the interupt functionality from the motor encoders)
7. t-pixels (test the neopixels)
8. t-motors (test the motors left and right)
9. t-ultrasound (test ultrasound value and display through serial console)
10. t-AnalogRead (read an analogue value from A1(15),A2(16),A3(17)

##Testing Proceedure
The board is tested by uploading the various sketches and then pysically testing or recording the results. A simple voltmeter is used to detect the voltage (or lack of voltage) on various pins.  A **signal anaylser** can be used to test more detailed signals (e.g. the frequency and duty cycle of a PWM signal for example.For this I am using the [bitscope micro] (http://www.bitscope.com/product/BS05/)


