# Team-Manipal-Racing-
For the event, to pass the 1st check, a safety control needs to be implemented for turning on the vehicle:
That is: (Ignition should be on, break should be pressed and vehicle is in neutral), If any on the provided is not maintained, vehicle should not turn on
To achieve this, we had used a simple yet cost effective solution that bagged us innovation award by using 8:1 mux 
S0 - Throttle is dis engaged
S1 - vehicle in neutral position
S2 - breaks are engaged
while S2 and S1 are high with S0 in Low, powering the vehicle will work.

Simulation:
used DEEDS software for a simple simulation for validating and proceeed for design.
<img width="790" height="463" alt="image" src="https://github.com/user-attachments/assets/6b033e51-cf5f-453a-baa3-6dc4743f3300" />

Validation of Vehicle dynamics using simulink model:
To validate our concept and design as per E-Baja specifications, a simulink model is developed and presented for the panel that had secured 2nd prize for validation.
Specifications:
Battery pack nominal voltage: 48 V (33P,13S)_Lithium Ion type
Fully charged voltage: 56V
Amp hrs: 100 Ah
Motor: 4.5KW, 4500 rpm_BLDC type
Maximum speed achieved = 34Kmph
Maximum accelration : 5.86 m/s^2
Range : 72km
Drive cycle: ( own drive cycle with initial run of prototype for better results)
Simulink model: 

<img width="1716" height="686" alt="image" src="https://github.com/user-attachments/assets/ab6fffdd-6660-4049-91fd-ac49bf552b62" />

Graphs:
Drive cycle:
<img width="1919" height="904" alt="image" src="https://github.com/user-attachments/assets/205f0e78-a761-4015-8389-f6be014622a1" />
SOC( State of charge(charge vs time)):
<img width="1919" height="882" alt="image" src="https://github.com/user-attachments/assets/0ac04c3a-acee-41c0-afbf-00ef2142045c" />
Voltage drop vs time:
<img width="1919" height="898" alt="image" src="https://github.com/user-attachments/assets/6a7a19fc-6a5e-4cda-a28c-5b8dba5221ea" />
Distnce vs Time:
<img width="1918" height="911" alt="image" src="https://github.com/user-attachments/assets/82341607-38dd-499d-bf81-983525847c67" />
Vehicle testing:


