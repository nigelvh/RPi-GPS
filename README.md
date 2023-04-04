# GPS Board for Standard Form-Factor RPi Boards
This is a small custom board for use with standard form-factor RPi single board computers.

<img src="[https://github.com/nigelvh/NTP-GPS/raw/main/NTP-GPS V1.0.JPG](https://raw.githubusercontent.com/nigelvh/RPi-GPS/main/Image_Board_V1.0_withoutPours.png)">

This is not a wholly unique device, there are other devices that perform similar functions or some subset thereof. It is certainly not the only way to accomplish the task.

This device uses a good quality GPS receiver with precise Pulse Per Second (PPS) output, and exposes both the NMEA data on the RPi's serial port, as well as the PPS signal on GPIO 4.

The schematic and board files have been created in Eagle, though I cannot guarantee how they will load without all the the associated libraries. There are additionally exported images of the schematic and board designs available for reference without using the Eagle software package.

A parts text file has been included which contains DigiKey links for each part. These are certainly not the only parts that would work, or the links over time may end up referencing parts that are out of stock. Any adjustments are left as an exercise to the reader.
