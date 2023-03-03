# Robot_4WD
Autonomous smart vehicle with line following and collision avoidance using Arduino Uno(Atmega 328P) microprocessor.
Line tracking system is initialized using IR sensor module.
Collision Avoidance system implementation using ultrasonic sensor.
4 stepper Motor powered by 8833 Driver expansion board.

Robotic Kit : Keyes Studio 4WD Bluetooth 2.0 kit KS0559

Basic Controls
Motors are connected on PORTD
Forward Pin Left   : Pin D5 (1 << PD5) ~ PWM
Forward Pin Right  : Pin D6 (1 << PD6) ~ PWM
Backward Pin Left  : Pin D2 (1 << PD2) 
Backward Pin Right : Pin D4 (1 << PD4)

Line Following
IR sensor module is connected to PORTD and PORTB
Left IR Sensor LED   : Pin B3 (1 << PB3)
Centre IR Sensor LED : Pin D7 (1 << PD7)
Right IR Sensor LED  : Pin B0 (1 << PB0)
