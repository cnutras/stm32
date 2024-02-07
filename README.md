
A circuit for counting numbers from 0 to 255 using 2-digit 7-segment displays controlled by 4 buttons
STM32F4 Pin Connections:

1.(LEFT DIGIT)     2.(RIGHT DIGIT)
  PA0 -> A1           PB0 -> A2
  PA1 -> B1           PB1 -> B2
  PA2 -> C1           PB2 -> C2 
  PA3 -> D1           PB3 -> D2
  PA4 -> E1           PB4 -> E2
  PA5 -> F1           PB5 -> F2
  PA6 -> G1           PB6 -> G2

PA0-6 and PB0-6 pins are output pins.

PC6-9 pins are input pins:
PC6 -> button1
PC7 -> button2
PC8 -> button3
PC9 -> button4
