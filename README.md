# makeathon_4.0
Documentation of "Smart Resource (Electricity+Water) Usage and Monitoring System

Our prototype monitors electricity usage (Energy-kWh) using the following components:-
Arduino UNO, NodeMCU, ACS712 current sesnor, relay modules, OLED dispaly,IR sensor, LDR sensor, breadboards, IC 7805, flowsensor
About the Sensor: The ACS712 provides economical and precise solutions for AC or DC current sensing in industrial, commercial, and communications systems. The device package allows for easy implementation by the customer. Typical applications include motor control, load detection and management, switched-mode power supplies, and overcurrent fault protection.

Brief Descption : The prototype calculates the energy using a current sensor(with suitable calculations we are getting the 
power, energy and the bill amount) and this data is being uploaded to the firebase cloud(By Google.Co) using the serial transmiision from the arduino which has calculated the parameters mentioned above to NodeMCU, wherein the NodeMCU uploads the data to cloud realtime database. We have an android app interface to monitor the same. The same mechanism is being done for monitoring water usage using the flow sensor.

I have provided all the required codes, libraries and the android app files in this repository.
