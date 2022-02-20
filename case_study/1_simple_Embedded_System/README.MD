# Simple Embedded System 
## Password Based Door Lock System Using 8051 microcontroller 

This system uses an 8051 microcontroller to illustrate a password-based door lock system, in which the door is unlocked and the concerned individual is granted entrance to the secured area once the correct code or password is entered. If another individual arrives, it will once again prompt you to input the password. If the password is incorrect, the door will remain closed, denying the person access


# Requirements 

## High level Requirements 
|ID  |DESCRIPTION                                                     |
|:---|:---------------------------------------------------------------|
|HLR1|Open the door                                                   |
|HLR2|Close the door                                                  |
|HLR3|If entered password is incorrect display "wrong password" on LCD|


## Low Level Requrirements
|ID  |DESCRIPTION                                               |
|:---|:---------------------------------------------------------|
|LLR1|Display the message "enter the password" on LCD           |
|LLR2|Read the five digit password from the user                |
|LLR3|compare the entered password with the stored password     |
|LLR4|If password correct, open the door                        |
|LLR5|After some time close the door                            |
|LLR6|If the password is wrong then display wrong pasword on Lcd|
|LLR7|After some delay again ask to enter password              |

## Block Diagram
![Screenshot (102)](https://user-images.githubusercontent.com/98865009/154790162-4de45898-44e7-429e-802d-e36ba8880e31.png)

## System Design
Password based door lock system using 8051 microcontroller circuit design uses five major components  a Microcontroller, an L293D Motor Driver, a DC Motor, a 4×4 Matrix Keypad and a 16×2 LCD. Here, an AT89C52 Microcontroller is used and it is an 8-bit controller. This controller requires a supply voltage of +5V DC. In order to provide regulated 5V DC voltage to the controller We can use 9V DC battery or 12V, 1A adaptor as a power source.
When the circuit is turned on, the microcontroller sends orders to the LCD, which causes the LCD to show "enter password." Now we must use the keypad to input the password. When the password is input, the LCD shows 5 stars, indicating that the controller has successfully read the password.

1. display the message “enter password” on LCD.
2. Now read the five digit password from the user.
3. Compare the entered password with the stored password.
4. If password is correct, then make P0.0 pin HIGH and P0.1 pin LOW to open the door. During this time, display “Door opening” on LCD.
5. After some time, make P0.0 pin LOW and P0.1 pin HIGH to close the door and after this display “Door closing” on LCD.
6. If the password is wrong, then display “Wrong Password” on LCD.
7. After some delay again ask to enter password.

## Functions of the components used
* AT89C52 Microcontroller: 

The Atmel AT89C52 is an 8-bit microcontroller from the 8051 series. The AT89C52 contains 256 bytes of RAM and 8KB of Flash programmable and erasable read only memory (PEROM). The AT89C52 has a 1000 Write/Erase cycle endurance rating, which implies it can be wiped and programmed 1000 times.

* L293D Motor Driver:

Electrical energy is converted into mechanical energy by motors. This motor is used to open and close the door. The motor must rotate, and we use the L293D driver to accomplish this. This driver helps in the control of the motor's speed and direction.

* 4×4 Matrix Keypad:

A keypad is a collection of buttons with various symbols, numerals, and alphabets arranged in a 4x4 grid. Push button keypads, membrane switch keypads, resistive touch keypads, capacitive touch keypads, and other types of keypads are available on the market. We need to type passwords in our project, so the push button keypad will be chosen because of its high stiffness and inexpensive cost compared to other keypads.

* 16×2 LCD:

A liquid crystal display, sometimes known as an LCD, is a great way for a microcontroller to show visual data. LCDs may display microcontroller output such as time, date, and temperature, etc. they can also be used to display memory contents and aid in code debugging.
