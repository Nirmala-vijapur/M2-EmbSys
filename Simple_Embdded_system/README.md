# simple Embedded System
## Password Based Circuit Breaker

Nowadays, electrical accidents to the line man are increasing, while repairing the electrical lines due to the lack of communication between the electrical substation and maintenance staff. This project gives a solution to this problem to ensure line man safety. In this proposed system, the control (ON/OFF) of the electrical lines lies with line man. This project is arranged in such a way that maintenance staff or line man has to enter the password to ON/OFF the electrical line.


 Now, if there is any fault in electrical line, then the line man will switch off the power supply to the line by entering password and comfortably repair the electrical line, and after coming to the substation line man switch on the supply to the particular line by entering the password. Separate passwords are assigned for each electrical lines.

![Screenshot (92)](https://user-images.githubusercontent.com/98865009/154540153-60ccc338-435c-4841-a801-71f00c3046f9.png)


The above circuit consists of 8051 series controller (AT89C52), 4×4 Matrix Keypad, 16 x 2 LCD Display, 4 – Channel Relay Module and Four Loads. LCD data pins are connected to PORT1 and control pins RS, RW and EN pins are connected to P3.0, GND and P3.1 respectively. Here, the LCD is used to display the information related to the load.

Keypad is connected to PORT2 of the microcontroller. The four Row Pins of the Keypad are connected to P2.0 to P2.3 and the four Column Pins are connected to P2.4 to P2.7. Using this keypad, we need to enter the password.

Four Lamps (acting as Electrical Lines) are connected to P0.0 to P0.3 through the 4 – Channel Relay Module. These are used to indicate circuit breaker state (Light ON – Line Active and Light OFF – Line Not Active).

## System Design
1. Write the program to the Password based Circuit Breaker in Keil software and create .hex file.
2. Burn program to the controller with help of 8051 Programming Board and Willar Software.
3. Now give the connections as per the circuit diagram.
4. While giving the connections, make sure that there is no common connection between AC and DC supplies
5. Use 5V power supply circuit to provide regulated 5V DC to the controller.
6.  Switch on the both AC and DC supplies.
7. Now relay output pins gets 230V. So, do not touch the load connected pins.
8. LCD displays “enter password”.
9. Enter the password with help of keypad.
10. Now, if the password is correct, then circuit breaker changes its state (i.e. if it is already ON, now it becomes OFF and if it is already OFF, now it becomes ON) and displays line (or load) status on LCD.
11. If the password is wrong, then the LCD displays “wrong password”.
12. After some time, the microcontroller asks to enter password by displaying “enter password”.


## Functions of the components used
## power supply :
takes the AC from the wall outlet, converts it to unregulated DC, and reduces the voltage using an input power transformer, typically stepping it down to the voltage required by the load

used to take inputs in the form of numbers and albhabets, and feed the same into system for further processing


