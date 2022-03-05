# Temperature based Fan Speed Controller
## Description 
This project Temperature Based Fan Speed Control s can be done by using Arduino board with some electronics materials. The Arduino UNO board is very popular among all electronic circuits, thus we employed Arduino UNO board for the operation of the fan speed control. In the proposed system itself said that it is designed to detect the temperature of the room and send that information to the Arduino UNO board. Then the Arduino UNO board carries out the contrast of current temperature and set temperature based on the inbuilt program of the Arduino that feed through us. The output obtained from the operation is given through the o/p port of an Arduino UNO board to the LCD display that connected with the board. This generates the PWM pulses from the board which is further given to the driver circuit to get the expected output to the fan. 

# Requirements 
## High Level Requirements
|ID  |DESCRIPTION        |
|:---|:------------------|
|HLR1|It can sense the temperature        |
|HLR2|It display the temperature on LCD   |
|HLR3|It can control the fan              |
|HLR4|It can measure the speed of the fan |
|HLR5|It display the speed of fan on Lcd  |

## low Level Requirements 
|ID  |DESCRIPTION                                                   |
|:---|:-------------------------------------------------------------|
|LLR1|change the temperature in temperature sensor                  | 
|LLR2|Fan is OFF when the temperature with in the limit             |
|LLR3|Fan is ON when the temperature is higher then the limit       |
|LLR4|LED ON when the temperature is higher then the limit          |
|LLR5|we can see the varying tempature, and fan speed on LCD display|

# SWOT 
### Strength 

* it is very economical and easy to handel by the user
* speed varies automatically, so that it controls the speed without using it manually 
* it is help full to disabled people 
* it is very easy to install in offices, houses etc
* save energy by showing down its speed in low temperature 

### weakness 

* Arduino is the heart of the circuit, if controller is damaged the whole system will be interrupted.
* Speed control is independent of individual preference.

# 4w's & 1H
## WHO
Temperature based Fan Speed Controller can be used in both the home and Industry.

## WHAT
Temperature based Fan Speed Controller It helps in saving the energy and electricity.

## WHEN
Temperature based Fan Speed Controller Prevents waste of energy when it’s not hot enough for a fan to be needed. To assist people who are disabled to adjust the fan speed automatically.

## HOW
The aim of this project is to design a temperature controlled fan using Arduino, in which the fan is automatically turned ON or OFF according to the temperature
