# Designing-of-Miller-Compensated-two-stage-OPAMP

Design of miller compensated two stage opamp:

Here we have attempted to design a two stage opamp in LTSPICE with the following specifications:
(All the aspect ratios are being considered with respect to 1um Length)
</br>
Open Loop Gain= 70db.
</br>
Gain Bandwidth= 8 Mhz.
</br>
SR >=10v/us.
</br>
ICMR >=1.5V.
</br>
Vin:2.7V to 1.2 V
</br>
Vdd= 3.3V.
</br>
PM>= 60 deg.
</br>
CL=10pF.
</br>
Kp=50uA/V.(Assumed)
</br>
Kn=110uA/V.(Assumed)
</br>
Pdiss<=2mW
</br>
























**The 

Circuit Diagram**
</br>
</br>
</br>
</br>
![image](https://user-images.githubusercontent.com/75901646/185986941-0d3b50d1-16d9-4b2e-bab0-fc01e57a9e23.png)
</br></br></br></br></br>


**Design Steps:**













 





















Checking the gain as well as power dissipation from the calculated values
















The circuit Diagram


The operating points:



























The input and output graph:
 
AC Analysis



Some of the observations:
1.	Our design produced an open loop gain of about 82db with a considerable phase margin of 69 degree as originally opposed to 70db and 60 degree margin.
2.	Overall power dissipation is about 0.8mW which is quite low as compared to the higher limit that we set of about 2mW.
         Parameter	        Calculated Value	          Obtained Value
             gm1	                 150.8uS	                    152uS
gm6	                  1510uS	                   1600uS
              Id6	                219.2uA	                 219.04uA



	Some tradeoffs:
On changing the value of compensating capacitor ,for different values :
Cc (pF)	PM (deg)
2.2	64
2.6	67
3	69
3.5	71

We observe that the phase margin increases.

Effect of changing (W/L)6,

(W/L)6	Id6(uA)	Gain(dB)	PM(deg)
110	225	81	69
120	234	81	70
125	239	81	71


	As observed ,on increasing W/L for M6 we were able to increase phase margin even though experimentally no visible change was observed in the gain value. Also Current through M6 increased which would ultimately increase the overall power dissipation in the circuit.
