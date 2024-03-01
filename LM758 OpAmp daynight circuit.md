# Light/Dark Circuit using LM758 OpAmp 

The LM758 IC is placed with Pin 1 at **E12**
Pin 1 is connected to resister R1 - **D12** to **D9**
Anode (+ve) of LED is at **E9** & the cathode (-ve) to **E7**
Row 7 is connected to Ground (-ve) rail
Row 11 is connected to Ground (-ve) rail at **A11**
Connect LDR at **C11** to **C14** - **This is Pin 3 of the OpAmp**
Resister R2 is connected at **A14** and  Ground (-ve Rail) - *This forms voltage divider*
Pin 4 is connected to Ground
Pin 8 of the OpAmp is connected to **I12**

Potentiometer P1, with the *wiper* at **A24** with a 1 fixed leg to ground & the other to the +ve rail
Jumper the Pin 2 at **D13** to the *wiper* of P1 at **E24**


**A30** is connected to -ve Rail
The IC Reset, Pin 4 of the IC is connected to the voltage divider at **C23**
Connect the anode (+ve leg) of the green LED to Pin 3 at **C14** and the cathode (-ve leg) to **C16**
Connect 1 leg of R2 to **B16** and the other to the -ve Rail
To indicate darkness, connect the cathode (-ve) leg of the Red LED to **D14** and the anode to **D7**
Place R4 at **C7** and the +ve Rail.

Use a 503 - 50Kohm Pot, LDR and 4.7Kohm resistor to form voltage divider.
## The Breadboard Component Layout

![[Pasted image 20240301185637.png]]


![[Pasted image 20240301193618.png]]

## The Electronic Schematic ##

![[Pasted image 20240301190134.png]]


