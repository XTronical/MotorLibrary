# MotorLibrary
A motor library for normal (not stepper or servo) motors - for use in the Arduino IDE, or adapt to other environments as required.
It allows for analogue control of a motor.
2 examples provided that take you through the basics. This library needs only 1 PWM pin to operate the motor. Therefore on Arduino
Uno or Nano you could control up to six motors at different speeds and directions independently.

Key functions - Please see www.xtronical.com/motorlibrary for more information and parameters

SetSpeed  : Set the speed of the motor in %
GetSpeed  : Get current speed of motor in %
Reverse   : Reverse direction
SetDirection : Set current motor direction
GetDirection : Get current motor direction
