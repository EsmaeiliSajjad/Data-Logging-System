# Data-Logging-System
In this project, the designed data logging software for several analog I/O modules from NI is demonstrated.
# Table of Centent
1. [Description](#1)
2. [Required Analog I/O Modules](#2) 
3. [Supported Devices/components](#3)
4. [Display](#4)
5. [Calibration](#5)
<a name="1"></a>


<a name="2"></a>
# Required analog I/O modules
![1](https://user-images.githubusercontent.com/108043716/177007909-15c4b88c-8eb6-4821-aa9d-c43253291346.png)

<a name="3"></a>
# Supported Devices/components
The following components can be connected to the NI-6001 and NI-9221:
1. All PT and DP sensors with 0-10 V or 0-20 mA analog output.
2. All Thermocouple types such as J-type, K_type, ets.
3. All mass flow meters with 0-5 V analog output.
<a name="4"></a>
# Display
The following display can be seen in "Data" tab of the software:
1. Pressure gauges
2. Temperature vertical bar
3. Mass flow meter value
The operator is able to change the limit of the temperature bar or pressure gauges in the software.
<a name="5"></a>
# Calibration
Any sensors such as Pressure transdcuer, Thermocpouple, Mass flow meter or Mass flow Controllers always come with a calibration sheet provided by the manusfacturer. For example for a pressure transdcuer with 0-10V configuration and 0-500 psi pressure variation, a calibration sheet shows the variation of pressure with corresponding voltage. Since most of sensors follow the linear trend between the measured parameter (e.g. pressure) and its analog output (e.g. voltage), a linear regression should be done on pressure versus voltage data.
The operator should enter the slope and intercept of the fitted line in the calibration data of the developed software to configurate the software properly. The following figure shows this option in the software.
![5](https://user-images.githubusercontent.com/108043716/177008468-624c0bcc-eb8f-42d4-b421-67b793c0fa16.png) 

Fig. 5: calibration configuration setting in the developed data logging software
