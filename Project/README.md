# Temperature based Fan Speed Controller
## Description 
This project Temperature Based Fan Speed Control s can be done by using Arduino board with some electronics materials. The Arduino UNO board is very popular among all electronic circuits, thus we employed Arduino UNO board for the operation of the fan speed control. In the proposed system itself said that it is designed to detect the temperature of the room and send that information to the Arduino UNO board. Then the Arduino UNO board carries out the contrast of current temperature and set temperature based on the inbuilt program of the Arduino that feed through us. The output obtained from the operation is given through the o/p port of an Arduino UNO board to the LCD display that connected with the board. This generates the PWM pulses from the board which is further given to the driver circuit to get the expected output to the fan. 

# Requirements 
## High Level Requirements
|ID  |DESCRIPTION        |
|:---|:------------------|
|HLR1|Fan ON             | 
|HLR1|Fan OFF            |
|HLR1|LED  ON            |

## low Level Requirements 
|ID  |DESCRIPTION                                            |
|:---|:------------------------------------------------------|
|LLR1|Fan is OFF when the temperature with in the limit      |
|LLR1|Fan is ON when the temperature is higher then the limit|
|LLR1|Buzzer or LED ON when the temperature is higher then the limit|

## Architecture / Block Diagrams 
### Structure Diagram 

![Screenshot (118)](https://user-images.githubusercontent.com/98865009/155737638-a534fa1d-e870-4313-9951-3ba12638c45e.png)



![Screenshot (114)](https://user-images.githubusercontent.com/98865009/155703826-b39094c9-c222-4778-accc-5769b3c528b6.png)

### Behavior Diagram 

![Screenshot (112)](https://user-images.githubusercontent.com/98865009/155706056-6b56cf4f-401e-4e4c-8a96-388e0980cc1c.png)



![Screenshot (110)](https://user-images.githubusercontent.com/98865009/155692430-6b594a41-1f56-4c49-a93a-4bb63ed3ce05.png)

## Components Required
## Hardware Requirements 
* Arduino UNO
* LM35 Temperature sensor 
* Potentiometer 
*  DC Fan
*  Relay
*  LED 
*  Transistor
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

## Functions of the components used 
### TEMPERATURE SENSOR LM35
Temperature sensor senses the room temperature. This electronic device converts the data that sensed in the surrounding into the electronic data for recording purpose. There are many different types of temperature sensors.Here in this project we are using LM 35 temperature sensor. The LM35 temperature sensor is graded to work from -55° Centigrade to 150° Centigrade with a udeviating scale factor of +10mv/° C. It is a tiny and low cost IC which can be used to measure temperature anywhere in the surrounding between -55°C to 150°C.

### ARDUINO 
Arduino UNO is a development board which contains microcontroller in the board itself. It is an open-source software. In the electronics platform, arduinois easy to use hardware and software. The Arduino boards can read inputs so that they can understand and give as some of the outcomes like light on a sensor, a finger on a button, activating a motor, turning on an LED, publishing something manually in online etc,. that are all given as output to us. The most of the applications on everyday life, ardunio is a part of the application. The reason is that the Arduino follows the instruction correctly that fed by us. How can we send the instructions to the Arduino board? The instructions can be fed
to the Arduino board by these tools, one is the Arduino programming language (based on Wiring), and the other one isArduino Software (IDE), based on Processing.

### POTENTIOMETER
The Potentiometer is an electric device that used to measure the Electro Motive Force of a given battery, the internal resistance of a cell. And also it is used to compare the EMFs of different cells. It can also use as a variable resistor in most of the applications.


### TRANSISTOR
A transistor is a semiconductor device used to amplify or switch electronic signals and electrical power. It is composed of semiconductor material usually with at least three terminals for connection to an external circuit.

### RELAY
It is a switch which controls (open and close) circuits electromechanically. The main operation of this device is to break contact with the help of a signal without any human involvement in order to switch it ON or OFF. It is mainly used to control a high powered circuit using a low power signal.


## Applications
* Temperature Controlled DC Fan can be used to control the temperature of devices, rooms, electronic components etc. by monitoring the temperature.
* The circuit can be used in CPU to reduce the heat.

