PID consists of Proportional Integral Derivative which is genarally a feedback system which tries to decrease the error as much as possible.

Let's take each component out of PID with respect to our FLF bot.

The three components are Proportional-Integral-Derivative

![image](https://github.com/pranxv-04/flf_final/assets/124788505/8fbf8c79-610c-41c5-82e8-6b6ac4cf7815)
![image](https://github.com/pranxv-04/flf_final/assets/124788505/49a76545-f8c6-40f0-9df9-de9d541633ad)


All these components need their proportionality constants let's name them as Kp, Ki and Kd

We'll first take the input we're getting from the sensor as sensor value and we subract it from the desired value to get the error

error(e) = desired value (dv) - sensor value(sv) 

Motor speed is final output we need to change so as to turn smoothly

let's assume.
desired value(dv) = 100
sensor value(sv) = 0

PROPORTIONAL

let kp be any constant and the value we get as error at time t be e(t)

The formula for error 




