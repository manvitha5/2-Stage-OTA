# 2-Stage-OTA Design using 180nm Technology

Design and Layout implementation of a high-performance two-stage Operational Amplifier (OPAMP) using 180nm semiconductor technology. Achieved required gain, bandwidth, and power efficiency through simulatio.
# Circuit Diagram
![link to image](https://drive.google.com/file/d/15vTvmyoz7TlK8qUIJq2KOoga5Lap3BD9/view?usp=drive_link)

# Design-Specification
Vdd = 1.8V <br>
DC Gain >= 60dB <br>
GBW = 5MHz <br>
PM >=60 degree <br>
ICMR(+) = 1.6V <br>
ICMR(-) = 0.8V <br>
CL = 23pF <br>
Power Dissipation < 200 uW <br>

# Design Process 
(W/L) ratio of M3,M4 is found using ICMR(+) <br> 
(W/L) ratio of M1,M2 is found using GBW <br>
(W/L) ratio of M5 is found using ICMR(-) <br>
(W/L) ratio of M6 is found from location of zero<br>

# Technology Used
LTspice (tsmc018.lib)
