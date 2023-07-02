PID consists of Proportional Integral Derivative which is genarally a feedback system which tries to decrease the error as much as possible.

Let's take each component out of PID with respect to our FLF bot.

The three components are Proportional-Integral-Derivative

![image](https://github.com/pranxv-04/flf_final/assets/124788505/31edcc68-e18e-4a68-af8f-46d1209d6d52)

![image](https://github.com/pranxv-04/flf_final/assets/124788505/49a76545-f8c6-40f0-9df9-de9d541633ad)


All these components need their proportionality constants let's name them as Kp, Ki and Kd

We'll first take the input we're getting from the sensor as sensor value and we subract it from the desired value to get the error

for now assume sensor value = speed of motor

error(e) = desired value (dv) - sensor value(sv) 

Motor speed (ms) is final output we need to change so as to turn smoothly

let's assume.
desired value(dv) = 100
sensor value(sv) = 0

PROPORTIONAL

let Kp be any constant and the value we get as error at time t be e(t)

Motor speed then becomes

ms = Kp.e(t)

Now as the the loop comes across again the value of error changes thereby motor speed also changes


INTEGRAL

the proportional part is not cpable of making changes as fast as possible hence we take up an inegral

Ki is the integral constant and the formula now becomes

ms = Kp.e(t) + Ki.[0∫t].e(t).dt 


DERIVATIVE



