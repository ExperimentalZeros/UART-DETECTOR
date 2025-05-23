# UART-DETECTOR
NODE-RED application to detect more than one UART device attached to a LINUX (RPI Debian) running machine:

* Checks "/dev/serial/by-id" for available "device/s".
* Maps the proper "device" attached to the running machine to the ideal NODE-RED "Funtion" output.
* This comes as an example to connect the Geiger Counter "GC-10" to the top output,
  and the lower function output to "U-BLOX-7" GPS module, of the "SERIAL PORT ASSIGMENTS" function.
* Other distribution compatibility has not been tested.
* Feel free to use as needed.
