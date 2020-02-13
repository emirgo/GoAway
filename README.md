# GoAway
GoAway is an intruder system developed by a single developer (owner of this repository). First firmware is planned as a prototype based and is based on ESP8266.

## What will GoAway do?
If you are accomodating in a shared household, sometimes fellow members of the house might go into your room or into places you don't want without your permission. GoAway aims to solve this issue in terms of notfying you via email when this happens. There will also be a web page where you can see logs of what happened and how long the intruder was in the room or environment you wanted to private.
A possibility of adding a buzzer as a sound source to warn the intruder will be added.

## Hardware Specificaitons
### ESP8266
Processor: L106 32-bit RISC microprocessor core based on the Tensilica Xtensa Diamond Standard 106Micro running at 80 MHz<br>
 32 KiB instruction RAM<br>
 32 KiB instruction cache RAM<br>
 80 KiB user-data RAM<br>
 16 KiB ETS system-data RAM<br>
External QSPI flash: up to 16 MiB is supported (512 KiB to 4 MiB typically included)<br>
IEEE 802.11 b/g/n Wi-Fi<br>
 Integrated TR switch, balun, LNA, power amplifier and matching network<br>
 WEP or WPA/WPA2 authentication, or open networks<br>
16 GPIO pins<br>
SPI<br>
I²C (software implementation)[6]<br>
I²S interfaces with DMA (sharing pins with GPIO)<br>
UART on dedicated pins, plus a transmit-only UART can be enabled on GPIO2<br>
10-bit ADC (successive approximation ADC)<br><br>
### PIR Sensor
Working voltage: DC5V to 20V	<br>
Static power consumption: 65	<br>
Output level: high 3.3V, low 0V	<br>
Delay time: adjustable (0.3 sec \~18 sec)	<br>
The embargo time: 0.2 seconds	<br>
Trigger mode: l not repeatable, h can be repeated, the default value for h	<br>
Induction range: less than 120 degree cone angle, up to 7 meters	<br>
Working temperature:- -15\~+70	<br>
PCB dimensions: 32*24mm, screw hole 28mm, screw diameter 2mm, induction of lens dimensions: (diameter): 23mm (default)
