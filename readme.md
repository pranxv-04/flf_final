PID consists of Proportional Integral Derivative which is genarally a feedback system which tries to decrease the error as much as possible.

Let's take each component out of PID with respect to our FLF bot.

The three components are Proportional-Integral-Derivative

All these components need their proportionality constants let's name them as Kp, Ki and Kd

We'll first take the input we're getting from the sensor as sensor value and we subract it from the desired value to get the error

error = desired value - sensor value 
Motor speed is final output we need to change so as to give 

![image](https://github.com/pranxv-04/flf_final/assets/124788505/8fbf8c79-610c-41c5-82e8-6b6ac4cf7815)

PROPORTIONAL


