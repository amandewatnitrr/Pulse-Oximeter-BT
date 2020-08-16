# Pulse-Oximeter-BT
![Alt](https://github.com/Calidad-Healthcare/Pulse-Oximeter-BT/blob/master/Pulse_Oximeter_test/IMG20200816214156.jpg)
# Readings on COM PORT
![ALt](https://github.com/Calidad-Healthcare/Pulse-Oximeter-BT/blob/master/Pulse_Oximeter_test/Pulse_Oximeter%20Radings.PNG)
# Hardware Required
1. MAX30100 Sensor
2. Soldering Iron
3. Solder Wire
4. Arduino Nano
5. Jumper Wires
6. HC-05 Bluetooth Module
# Software Required
1. Arduino IDE
2. Download MAX30100 Library using this Link: https://drive.google.com/open?id=15w7Hp_Lg7FVVQoou1A56JgNDZADBuN15
# Error in the MAX30100 Circuit resolved
The Circuit when closely observed has following faults:
1. INT pin is open, no connection during PCB Manufacturing, Hence it's exsistence makes no sense, so nothing to do with that.
2. Carefully look at the circuit of the MAX30100 module . It involves two linear voltage regulators – U2 and U3. The first one make a + 3.3V from + 5V (or simply passes through the power supply + 3.3V). The second regulator is connected to the output of the first and generates supply voltage + 1.8V. 
# Incorrect Ciruit
![Alt](https://github.com/Calidad-Healthcare/Pulse-Oximeter-BT/blob/master/Pulse_Oximeter_test/Incorrect_MAX30100%20Module.PNG)
# Corrections
![Alt](https://github.com/Calidad-Healthcare/Pulse-Oximeter-BT/blob/master/Pulse_Oximeter_test/Corrected_MAX30100%20Module.PNG)
# Circuitry
![Alt](https://github.com/Calidad-Healthcare/Pulse-Oximeter-BT/blob/master/Pulse_Oximeter_test/MAX30100_connection.PNG)
![Alt](https://github.com/Calidad-Healthcare/Pulse-Oximeter-BT/blob/master/Pulse_Oximeter_test/IMG20200816220549.jpg)
![Alt](https://github.com/Calidad-Healthcare/Pulse-Oximeter-BT/blob/master/Pulse_Oximeter_test/IMG20200816220628.jpg)
