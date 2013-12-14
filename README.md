INSTALL:

* Make your own PCB
* Burn firmware
* Connect wires (take a look in PCB files)
* Press On/Off button to start Raspberry Pi
* Copy RPiSU.sh to users home dir
* Execute 'sudo chmod 766 /home/users home dir/RPiSU.sh'
* Add command '/home/user/RPiSU.sh &' above 'exit 0' in /etc/rc.local
* Reboot
* 

Forked from original at:
https://github.com/schmron/RPiSU

You need a Tiny45/85 or other AVR (Arduino, Freeduino, Seeeduino,...), Relay (5V, 150Ohm), USB-Micro-Cable (or USB[/code] breakouts) and some Transistors, LEDs, Capacitors, Resistors, etc

Pinheader USB:
pin 1 = 5V
pin 2 = GND
pin 3 = (D+) not used
pin 4 = (D-) not used 
