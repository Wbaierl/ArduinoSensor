########General
     Directory RFM69 is copied in current working directory
     to manage RFM69.cpp, RMF69.h  etc. with git
     To have the files available in /Arduino/libraries
     a symlink is created with
	ln -s ~/Arduino/Sketchbook/RFM69ATC_node1/RFM69   ~/Arduino/libraries
	
    

#########RFM69ATC_node1 - Initial version for 868MHz Transmission Line
 Works well with 2400 baud
 RSSI drop by approx. -20dB when increasing to 4800 baud


######## Branch RFM_Sensor
 Build a sensor that transmits sensor data over RFM69 868MHz
 
 
