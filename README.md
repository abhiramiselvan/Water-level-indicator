
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

### 555 TIMER PIN DIAGRAM
Before using the 555 timer IC, we should know the details about that. 
- #### Pin 1 –  GND
  It is a Ground pin that connects the 555 timer to the negative (0v) supply.
- #### Pin 2 – TRI
  It is a Trigger pin, this pin “sets” the internal Flip-flop when the voltage drops below 1/3Vcc causing the output to switch from a “LOW” to a “HIGH” state.
- #### Pin 3 – OUT
  It is the Output pin, that can drive any TTL circuit and is capable of sourcing or sinking up to 200mA of current at an output voltage equal to approximately Vcc – - 1.5V so small speakers, LEDs, or motors can be connected directly to the output.
- #### Pin 4 – RESET
  Reset, the function of this pin to reset the Flip-flop controlling the state of the output, pin 3.
- #### Pin 5 – CV
  Control Voltage, It controls the timing of the 555 by overriding the 2/3Vcc level of the voltage divider network. By applying a voltage to this pin the width of the - - output signal can be varied independently of the RC timing network. When not used it is connected to ground via a 10nF capacitor to eliminate any noise.
- #### Pin 6 – TH
  Threshold, The positive input to comparator No 2. This pin is used to reset the Flip-flop when the voltage applied to it exceeds 2/3Vcc causing the output to switch from a “HIGH” to a “LOW” state. This pin connects directly to the RC timing circuit.
- #### Pin 7 – DIS
  Discharge, The discharge pin is connected directly to the Collector of an internal NPN transistor which is used to “discharge” the timing capacitor to ground when the output at pin 3 switches “LOW”.
- #### Pin 8 – VCC
  Supply +Vcc, This is the power supply pin and for general purpose TTL 555 timers are between 4.5V and 15V.



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

### Working Model:
https://github.com/abhiramiselvan/Water-level-indicator/assets/144225835/66d602aa-47ec-440f-871a-25d79f0960b8



