# piLCD
# Nexgen-Gadgets Raspberry Pi 3.5 Touchscreen LCD Drivers type-2

# How to install:
  
1.)Step1, Install Raspbian official mirror <br>
====================================================
  a)Download Raspbian official mirror:<br>
  https://www.raspberrypi.org/downloads/<br>
  b)Use“SDFormatter.exe”to Format your TF Card<br>
  c)Use“Win32DiskImager.exe” Burning mirror to TF Card<br>
     
2.) Step2, Clone this repository onto your pi and install<br>
====================================================
Use SSH to connect the Raspberry Pi, <br>
And Ensure that the Raspberry Pi is connected to the Internet before executing the following commands:
-----------------------------------------------------------------------------------------------------

```sudo rm -rf piLCD```<br>
```git clone https://github.com/nexgen-gadgets/piLCD.git```<br>
```chmod -R 755 piLCD```<br>
```cd piLCD/```<br>
```sudo ./LCD35a1-install```<br>

Raspberry Pi will then reboot and LCD will be working.
