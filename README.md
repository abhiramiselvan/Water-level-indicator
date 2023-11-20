
# Water Level Indicator

### Introduction:
We incorporate automation and smart solutions into our daily routines to streamline tasks efficiently. This project aligns with that philosophy. We have developed a circuit to indicate the water level in a tank, ensuring a consistent water supply. This intelligent system prevents the tank from running dry, contributing to more effective water management.

### Require Components:
- LED
- Float switch
- 555 timer IC
- Resistor - 1K
- Battery - 9V
- Breadboard
- Jumper wires - As we require


### Interfacing the components:
- Connect one leg of the float switch to the battery’s positive voltage (Vcc).
- Connect the other leg of the float switch to the trigger (TRIG) pin of the 555 timer IC.
- Connect the threshold (TH) and discharge (DIS) pins of the 555 timer IC together and connect them to the battery’s Vcc through a resistor (1k ohm is a common value).
- Connect the discharge (DIS) pin to the battery’s ground (GND).
- Connect the output (OUT) pin of the 555 timer IC to the anode of the LED.
- Connect the cathode of the LED to the battery’s ground (GND).
- Connect the reset (RESET) pin of the 555 timer IC to battery’s Vcc.
- Connect the control voltage (CV) pin of the 555 timer IC to battery’s Vcc.
- Connect the threshold (TH) pin to the trigger (TRIG) pin.
- Connect IC’s ground to battery’s ground and IC’s VCC to battery’s positive.

![circuit (1)](https://github.com/abhiramiselvan/Water-level-indicator/assets/144225835/311c7b2f-fe47-4be4-8c03-70df46191205)



