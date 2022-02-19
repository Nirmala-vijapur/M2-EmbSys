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

![Screenshot (97)](https://user-images.githubusercontent.com/98865009/154789682-341c069e-6666-4f95-bc5d-42611f932875.png)


