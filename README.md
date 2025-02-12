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
## DOMINO Logic
The Domino logic family is used in a wide range of applications that need a
low transistor count and fast speed of operation, such as microprocessors, dynamic
memory, digital signal processors, and so on. Domino logic is an advancement in
CMOS-based dynamic logic approaches that employ either p-MOS or n-MOS for the
pull-down or pull up the network. The Domino logic methodology for constructing
complete adders uses less transistors than typical CMOS logic and produces a
high-performance device.
## FinFET Technique
A fin field-effect transistor (FinFET) is a multigate device, a MOSFET
built on a substrate with the gate put on two, three, or four sides of the 2 channel or wrapped around the channel 
forming a double or even multi-gate structure.FinFET devices feature far faster switching times and higher
current density than planar CMOS devices. FinFETs are a form of the non-planar transistor,
also known as "3D" transistors. It serves the development of modern nanoelectronic
semiconductor devices. To maximise drive strength and performance, it is typical for a
single FinFET transistor to comprise numerous fins positioned side by side and all covered
by the same gate.
## Why do we need to change the existing Technique ?
- We reduce the no of transistors involved
- We reduce the power consumption 
- We reduce average delay involved 
- In case of FinFET Tech. we also reduce the size of transistors

### Here is the comparision of different parameters 
| Parameter  | CMOS  | DOMINO  | FinFET   |
|:----------|:----------|:----------|:----------|
| No of Transistors | 28 | 20 | 28 |
| Size of Transistors | 180 nm | 180 nm | 18 nm |
| Input Voltage | 3 V | 3 V | 1 V |
| Average Delay | 19.94e-9 s | 10.07e-9 s | 36.14e-12 s |
## Results 
I have made a "images" file to show the result of all the methods involved in the project
## Conclusion 
The designing of a full adder circuit using the FinFET Technique has been done. We used
Cadence Virtuoso 6.1.7 software, 18nm technology for analyzing the full adder circuit, and
made the comparison between the FinFET technique, CMOS logic, and Domino Logic. It
was found that FinFET gives us very accurate results with minimum delay as compared to
the CMOS, Domino design logic.

