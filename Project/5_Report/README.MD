# Report 
# Temperature based Fan Speed Controller
# Abstract 
This project, Temperature Based Fan Speed Control, can be completed with the help of an Arduino board and some electronic components. The Arduino UNO board is quite popular among all electronic circuits, so we used an Arduino UNO board to regulate the fan speed. The suggested system is designed to detect the temperature of the room and transfer that information to the Arduino UNO board, according to the proposal. The Arduino UNO board then compares the current temperature to the set temperature using the Arduino's built-in programme, which is fed through us. The operation's output is sent to an Arduino UNO board's o/p port, which is connected to an LCD display.

# Requirements 
## High Level Requirements
|ID  |DESCRIPTION                         |
|:---|:-----------------------------------|
|HLR1|It can sense the temperature        |
|HLR2|It display the temperature on LCD   |
|HLR3|It can control the fan              |
|HLR4|It can measure the speed of the fan |
|HLR5|It display the speed of fan on Lcd  |

## Low Level Requirements 
|ID  |DESCRIPTION                                                   |
|:---|:-------------------------------------------------------------|
|LLR1|change the temperature in temperature sensor                  | 
|LLR2|Fan is OFF when the temperature with in the limit             |
|LLR3|Fan is ON when the temperature is higher then the limit       |
|LLR4|LED ON when the temperature is higher then the limit          |
|LLR5|we can see the varying tempature, and fan speed on LCD display|


# SWOT 
## Strength 

* Speed fluctuates automatically, thus it manages the speed without the user having to do it manually.
* It is useful for disabled persons.
* It is simple to install in businesses, homes, and other places. 
* It saves energy by slowing down in low temperature. 

## Weakness 

* Since the Arduino is the circuit's heart, if the controller is damaged, the entire system will be interrupted.
* Individual preferences have no effect on speed control.

# 4w's & 1H
## WHO
Temperature based Fan Speed Controller can be used in both the home and Industry.

## WHAT
Temperature based Fan Speed Controller It helps in saving the energy and electricity.

## WHEN
Temperature based Fan Speed Controller Prevents waste of energy when it’s not hot enough for a fan to be needed. To assist people who are disabled to adjust the fan speed automatically.

## HOW
The aim of this project is to design a temperature controlled fan using Arduino, in which the fan is automatically turned ON or OFF according to the temperature

# Architecture / Block Diagrams 
# Structure Diagram 
## High Level 

![Screenshot (197)](https://user-images.githubusercontent.com/98865009/157102585-a67a8787-d68e-413f-9413-7c9c507cf036.png)

## Low Level

![Screenshot (201)](https://user-images.githubusercontent.com/98865009/157102928-8a195d19-7aab-4709-b906-5ccf644701fe.png)

# Behavior Diagram 

![Screenshot (200)](https://user-images.githubusercontent.com/98865009/157102995-aefff24b-4e5a-4d68-8f9e-5284a5e2d374.png)

# Flow chat  

![Screenshot (204)](https://user-images.githubusercontent.com/98865009/157176852-cc2cad3e-2f31-41c4-bc1c-8dd21067e7ec.png)


# Components Required
## Hardware Requirements 
* Arduino UNO
* LM35 Temperature sensor 
* Potentiometer 
*  DC Fan
*  Relay
*  LED 
*  Mosfet
*  100R resistor 
*  4.7k Resistor 
*  1k Resistor
*  10k Resistor 
*  10uf capacitor
*  male to male jumper wires
*  Battery 9v
*  Battery clip 

## software requirements
* Simulide
* Arduino

# Functions of the components used 
## TEMPERATURE SENSOR LM35
The temperature of the room is detected by the temperature sensor. This electrical gadget turns data detected in the environment into electronic data for the purpose of recording. Temperature sensors come in a variety of shapes and sizes. The LM 35 temperature sensor is used in this project. With an udeviating scale factor of +10mv/° C, the LM35 temperature sensor can work in temperatures ranging from -55°C to 150°C. It's a small, low-cost IC that can measure temperature anywhere in the environment between -55°C and 150°C.

## ARDUINO 
The Arduino UNO is a development board that has a built-in microprocessor. It is a free and open-source programme. Arduino is a hardware and software platform for electronics that is simple to use. The Arduino boards can receive inputs and understand them, resulting in outputs such as light on a sensor, a finger on a button, activating a motor, turning on an LED, manually publishing anything online, and so on. Ardunio is a component of the majority of applications used in daily life. The reason for this is that the Arduino correctly interprets the instructions that we provide.What is the best way to send commands to the Arduino board? These tools can feed the instructions to the Arduino board: the Arduino programming language (based on Wiring) and the Arduino Software (IDE) (based on Processing).


## POTENTIOMETER
A potentiometer is an electric device that measures the Electro Motive Force of a battery, as well as the internal resistance of a cell. It's also used to compare the EMFs of various cells. In most applications, it can also be used as a variable resistor.

## RELAY
It's an electromechanical switch that controls (opens and closes) circuits. The main function of this device is to break contact using a signal without the need for human intervention in order to turn it ON or OFF. Its primary function is to regulate a high-powered circuit with a low-power signal.


# Applications
* Temperature Controlled DC Fan can be used to control the temperature of devices, rooms, electronic components etc. by monitoring the temperature.
* The circuit can be used in CPU to reduce the heat.
