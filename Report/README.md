# Password Based Circuit Breaker
## Description 
Nowadays, electrical accidents to the line man are increasing, while repairing the electrical lines due to the lack of communication between the electrical substation and maintenance staff. This project gives a solution to this problem to ensure line man safety. In this proposed system, the control (ON/OFF) of the electrical lines lies with line man. This project is arranged in such a way that maintenance staff or line man has to enter the password to ON/OFF the electrical line.


 Now, if there is any fault in electrical line, then the line man will switch off the power supply to the line by entering password and comfortably repair the electrical line, and after coming to the substation line man switch on the supply to the particular line by entering the password. Separate passwords are assigned for each electrical lines.
 
 
## Requirements 
## High Level Requirements
|ID|DESCRIPTION                               |
|:-|:-----------------------------------------|
|HLR1|Line man can switch off the power supply|
|HLR2|line man can switch on the power supply |

## Low Level Requirements
|ID  |DESCRIPTION                                                                                   |
|:---|:---------------------------------------------------------------------------------------------|
|LLR1|user needs to enter the password                                                              |
|LLR2|Enter the password with help of keypad                                                        |
|LLR3|If the password is correct then circuit breaker changes its state & display line status on LCD|
|LLR4|If the password is wrong then the LCD display wrong password                                  |





## Block Diagram 

![Screenshot (99)](https://user-images.githubusercontent.com/98865009/154733580-6f502432-d3b9-4bf7-8486-56e9c65b5752.png)


The above circuit consists of 8051 series controller (AT89C52), 4×4 Matrix Keypad, 16 x 2 LCD Display, 4 – Channel Relay Module and Four Loads. LCD data pins are connected to PORT1 and control pins RS, RW and EN pins are connected to P3.0, GND and P3.1 respectively. Here, the LCD is used to display the information related to the load.

Keypad is connected to PORT2 of the microcontroller. The four Row Pins of the Keypad are connected to P2.0 to P2.3 and the four Column Pins are connected to P2.4 to P2.7. Using this keypad, we need to enter the password.

Four Lamps (acting as Electrical Lines) are connected to P0.0 to P0.3 through the 4 – Channel Relay Module. These are used to indicate circuit breaker state (Light ON – Line Active and Light OFF – Line Not Active).

## System Design
1. Now give the connections as per the circuit diagram.
2. While giving the connections, make sure that there is no common connection between AC and DC supplies
3. Use 5V power supply circuit to provide regulated 5V DC to the controller.
4.  Switch on the both AC and DC supplies.
5. Now relay output pins gets 230V. So, do not touch the load connected pins.
6. LCD displays “enter password”.
7. Enter the password with help of keypad.
8. Now, if the password is correct, then circuit breaker changes its state (i.e. if it is already ON, now it becomes OFF and if it is already OFF, now it becomes ON) and displays line (or load) status on LCD.
9. If the password is wrong, then the LCD displays “wrong password”.
10. After some time, the microcontroller asks to enter password by displaying “enter password”.

## Components Required
* 8051 Microcontroller (AT89C52)
* 8051 Development Board
* 4 x 4 Matrix Keypad
* 4 – Channel Relay Module
* 16 x 2 LCD Display
* 10KΩ Potentiometer
* 4 Loads (Light Bulbs)
* Power Supply
* Connecting Wires


## Functions of the components used
## Power supply :
takes the AC from the wall outlet, converts it to unregulated DC, and reduces the voltage using an input power transformer, typically stepping it down to the voltage required by the load

## Keypad
used to take inputs in the form of numbers and albhabets, and feed the same into system for further processing

## Crystal 
 This crystal oscillator is used to generate clock pulses required for the synchronization of all the internal operations.
 Oscillators provide the basic timing and control for a microcontroller and its peripherals. Commonly used oscillators are of crystal because of its well known stability and durability. It produces stable output for prolonged time.
 
 ## Relay
Relays are the switches which aim at closing and opening the circuits electronically as well as electromechanically. It controls the opening and closing of the circuit contacts of an electronic circuit.

## potentiometer 
A potentiometer is a three-terminal resistor with a sliding or rotating contact that forms an adjustable voltage divider. If only two terminals are used, one end and the wiper, it acts as a variable resistor or rheostat.

## LCD 
LCDs can display output from the µC such as time, date, and temperature.


## Advantages
* Avoids electrical accidents to line man
* Project is simple and easy
* Uses commonly available components

## Applications
* Used in electrical substations to ensure line man safety
* This system is used in buildings and houses
* Used in hotels and shopping malls to save the power. 
* Can also be used as Password based electrical appliance control or Password based Load Control system.
