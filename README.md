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
























**The Circuit Diagram**
</br>
</br>
</br>
</br>
![image](https://user-images.githubusercontent.com/75901646/185986941-0d3b50d1-16d9-4b2e-bab0-fc01e57a9e23.png)
</br></br></br></br></br>


**Design Steps:**

</br>
</br>
![image](https://user-images.githubusercontent.com/75901646/185987160-277db655-e26e-4ec4-9fbc-d7d7f503d576.png)
</br>
</br>
</br>
![image](https://user-images.githubusercontent.com/75901646/185987178-bdc333f5-b242-4192-b8fd-e5f10667dec9.png)
</br>
</br>
</br>
![image](https://user-images.githubusercontent.com/75901646/185987195-caaa7d4b-794b-424b-91f1-4291c4d9da17.png)
</br>
</br>
</br>
Checking the gain as well as power dissipation from the calculated values
</br>
</br>
![image](https://user-images.githubusercontent.com/75901646/185987203-4e8e07c9-b0fe-47ee-afb8-e86f26746974.png)
</br>
</br>
</br>
</br>
</br>








 






































**The circuit Diagram in LTSPICE:**
</br>
![image](https://user-images.githubusercontent.com/75901646/185987436-d4416599-f260-4b58-a510-237bb2352556.png)
</br>



**The operating points:**
</br>
![image](https://user-images.githubusercontent.com/75901646/185987512-1707a336-c9a3-4d86-ac68-b61aec87a5ba.png)
</br>
![image](https://user-images.githubusercontent.com/75901646/185987620-d895551e-5fa0-4c19-9c77-9fc51933b8e1.png)
</br>





























**The input and output graph:**
</br>
![image](https://user-images.githubusercontent.com/75901646/185987655-91bcae71-433d-45c4-9051-b6a20fb673dc.png)
</br>
</br>
</br>

 
**AC Analysis**
</br>
</br>
![image](https://user-images.githubusercontent.com/75901646/185987729-9c77c0f1-5bb9-4b59-9f49-c9d872a08a12.png)
</br>




