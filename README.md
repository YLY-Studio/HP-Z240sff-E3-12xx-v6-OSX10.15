# HP-Z240sff-E3-v6-OSX 

HP Z240sff Chassis hackintosh

Chipset Intel C236

CPU:Intel Xeon E3-1280 v6  ( Kaby Lake)

GPU:AMD R5 430 without iGPU. , I try other RX550(Lexa,2017 Bios) Device ID 699F, GT720(NO CI/QE)

Memory:8G / 24G all tryed. 

HDD: 7200rpm 320G

NIC: onboard intel 219i worked

Wireless: add PICE-m.2 intel 3xxx wireless card. enable to scan SSID and BT with usb connect to onboard Media 3 pin.

Intel wireless with No Airdrop.

Bootloader : Opencore 0.64


Status: 
For now , files worked for install OSX 10.15.7
Onboard PCI Audio Controller working fine with aid parameter, could select internal speaker or output port.


ISSUE:

eGPU not driver ,so don't have graphics acceleration (sluggish animations, no QE/CI)

sometime the system will too slow after open a app

Everytime reboot , HP bios will report some RTC and time error 005,  already add rtc fixed.

