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


## Circuit operation
When the circuit is turned on, the microcontroller sends orders to the LCD, which causes the LCD to show "enter password." Now we must use the keypad to input the password. When the password is input, the LCD shows 5 stars, indicating that the controller has successfully read the password.

The controller now compares the entered password to the password that was previously set. If the password is correct, the microcontroller sets P0.0 to HIGH and P0.1 to LOW, allowing the motor driver to receive input signals for forward motion.

As a result, to open the door, the Door Motor rotates in a forward motion. The microcontroller makes P0.0 LOW and P0.1 HIGH after a 10-second delay, allowing the motor driver to receive input signals for reverse motion. As a result, the Door motor closes the door by rotating in the opposite direction.


If the password is not entered correctly, the microcontroller keeps both P0.0 and P0.1 low. As a result, the door motor remains stationary, allowing the door to remain closed.


