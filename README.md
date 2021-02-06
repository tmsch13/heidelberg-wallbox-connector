# heidelberg-wallbox-connector
A simple Python Modbus to MQTT (homie) Connector for Heidelberg Energy Control Wallbox

Values are published to MQTT in homie Standard and are easy integratable into openHAB and other Smart Home Systems

### Currently the follwing Values are published
* total Power
* current

### Currently the follwing Values are read from MQTT and will be written to Wallbox
* maximal allowed current

### requirements 
* Linux System running Linux and Python3 with access to a USB Port 
* A cheap RS485 Modbus USB Stick to connect the Wallbox to the Linux System where you run the script
* Heidelberg Energy Control Wallbox
* wired connection from Modbus Stick to Wallbox (2 wires)
