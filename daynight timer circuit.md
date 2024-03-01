# Light/Dark Circuit using NE555 Timer

The timer IC is placed with Pin 1 at **E12**
Pin 1 is connected to Ground/-ve rail - **C12** to -ve Rail
Pin 2 is jumpered across to Pin 6 - **D13** to **G14**
To avoid any shorts connect Pin 2 to R3 at **A13** and Ground
LDR placed at **E21** & **E23**
Connect left leg of LDR to +5v rail by connect **A21**
R1 at **D23** to **D30** (-ve Rail) - *This forms voltage divider*
**A30** is connected to -ve Rail
The IC Reset, Pin 4 of the IC is connected to the voltage divider at **C23**
Connect the anode (+ve leg) of the green LED to Pin 3 at **C14** and the cathode (-ve leg) to **C16**
Connect 1 leg of R2 to **B16** and the other to the -ve Rail
To indicate darkness, connect the cathode (-ve) leg of the Red LED to **D14** and the anode to **D7**
Place R4 at **C7** and the +ve Rail.

The circuit will light the green LED in daylight and red when it's dark.
## The Breadboard Component Layout

![[Pasted image 20240301184433.png]]
## The Electronic Schematic##

![[Pasted image 20240301185032.png]]


# Add Potentiometer to Adjust the light Sensitivity

Replace Resistor R1 with a Potentiometer P1, with the *wiper* at **D31** and a fixed leg to ground
Jumper the *divider* at **D23** to the *wiper* of P1 at **D31**

All the resistors in both circuits were later replaced with 220 ohm resistors 
