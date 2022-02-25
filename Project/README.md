# Temperature Controlled DC Fan
## Description 
Temperature Controlled DC Fan is a system which automatically turns on a DC Fan when the ambient temperature increases above a certain limit.
Generally, electronic devices produce more heat. So this heat should be reduced in order to protect the device. There are many ways to reduce this heat. 
One way is to switch on the fan spontaneously.switches the fan when it detects the temperature inside the device greater than its threshold value. 

# Requirements 
## High Level Requirements
|ID  |DESCRIPTION|
|:---|:----------|
|HLR1|Fan ON     | 
|HLR1|Fan OFF    |
|HLR1|BUZZER ON  |

## low Level Requirements 
|ID  |DESCRIPTION                                            |
|:---|:------------------------------------------------------|
|LLR1|Fan is OFF when the temperature with in the limit      |
|LLR1|Fan is ON when the temperature is higher then the limit|
|LLR1|Buzzer ON when the temperature is higher then the limit|

## Block Diagram
![Screenshot (107)](https://user-images.githubusercontent.com/98865009/155678688-70d7e31c-2a85-4fc4-b93f-5cfc55d19191.png)

## Components Required
## Hardware Requirements 
* ARDUINO
* LM35 Temperature sensor 
* POWER MOSFET 
*  DC Fan
*  BUzzer
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



