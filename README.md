# ControladorMicrored
This project contains a master-slave architecture between Raspberry-Pi and Arduino, using I2C protocol. It is used to control 
a renewable energy micro grid.

<img src="resources/circuit.PNG"
     alt="circuit_design"/>
## Prerequisites
* Python 2.7
* Raspberry Pi
* Arduino

### Master (Raspberry Pi)
To setup your Raspberry Pi you first have to execute the following command to enable I2C protocol:

 ``` bash
 $ sudo raspi-config
 ```


## Installation 
### Master (Raspberry Pi)
To setup the master project you first have to install all dependencies as follows.
 ``` bash
 $ pip install -r requirements.txt
 ```
 ### Slaves