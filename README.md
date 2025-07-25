# STM32_F446RE_Dual_Motor_Control
Author: @jacob_hohl
Utilizes STM32 Nucleo-F446RE and L298N motor driver to apply PWM voltage for speed control of 2 brushed DC motors.

Parts List:
STM32 Nucleo-F446RE
L298N
2x 12V brushed DC motor
12V DC power supply
6x male-female jumper wire
1x male-male jumper wire
4x stranded-core wire segment ~4 inches

Wiring:
F446RE ground to L298N ground
12V DC to L298N +12V
12V ground to L298N ground
DC motors power and ground to L298N OUT1/OUT2/OUT3/OUT4
L298N ENA to F446RE D6
L298N IN1 to F446RE D5
L298N IN2 to F446RE D4
L298N IN3 to F446RE D8
L298N IN4 to F446RE D7
L298N ENB to F446RE D9
L298N 5V Jumper wire installed

