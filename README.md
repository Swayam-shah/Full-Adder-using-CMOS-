# Design and Analysis of Full Adder   
In the rapidly expanding VLSI industry, transistor density is increasing at an alarming rate.
According to Moore’s law, transistor density will double every eighteen months. The
device’s area, delay, and power consumption will all grow as the number of transistors
increases. As a result, a solution is necessary to lower the space while increasing the
device’s performance. For the past few decades, CMOS technology has been utilised to
develop chips in the semiconductor industry, but as the number of transistors increases, so
does the area of the device and the delay. As a result, it is necessary to convert to a
technology that utilises less area and has a shorter delay. As a result, the Domino logic is
utilised to create the one-bit full adder, and the various performance parameters such as
area, delay, and power consumption in both technologies are compared 
## CMOS logic 
A.CMOS Logic- CMOS stands for "Complement Metal Oxide Semiconductor.".
CMOS logic employs pMOS and nMOS transistors, which function as pull-up and
pull-down transistors, respectively. When the input is low, the P-MOS turns on and charges
the output node to Vdd; when the input is high, the n-MOS turns on and the charge stored
at the output node forms a conducting channel between the output node and ground. When
compared to previous logic designs.

CMOS logic design has several advantages. 
In this case, both transistors are connected in a complementary manner, which means that if one
transistor is turned on, the other is turned off, and vice versa. The key advantages of CMOS
logic are its large noise margin, low power dissipation, and rail-to-rail output.

There aresome drawbacks to CMOS logic, such as the need for a large area and the slow speed of
operation. As a result, for a circuit with a large number of transistors, the area required is
very large, and the speed of operation becomes slow. That’s why there is a need to move on
to another technology that requires a smaller number of transistors and provides a high
speed of operation

