# ASUS VivoBook Pro 15 N580VD - Hackintosh 

* Model: ASUS VivoBook 15 N580VD
* Motherboard: X580VD
* CPU: i7-7700HQ (Kaby Lake FCBGA-1440)
* eGPU: Intel HD630
* dGPU: Nvidia Geforce GTX1050 (2GB)
* RAM: ~~16GB (Samsung M47A1K43CB1-CRC DDR4 2x8GB PC4 2400T SA1-11)~~  
Replaced with 32GB (2 x Hynix HMA82GS6JJR8N-VK 16GB DDR4 SODIMM 2666MHZ)
* SSD: 256GB Micron 1100 M.2 (MTFDDAV256TBM)
* SSHD: 2TB FireCuda (ST2000LX001)
* Ethernet: Realtek RTL8168
* WIFI: ~~Intel 8265NGW M.2 (Stock)~~  
Replaced with Dell DW1820A CN-0VW3T3 BCM94350ZAE
* Audio: Conexant Audio CX8150
* Built-in Display: B156HAN06.1 (1080p non touch)
* Touchpad: ELAN1200
* Cardreader: RealTek USB2.0-CRW (Product ID: 0x0129, Vendor ID: 0x0bda)

# Not Working:
* RealTek USB2.0-CRW. (Haven't done much research)
* dGPU: Nvidia Geforce GTX1050.  (Nvidia Optimus not supported on MacOS 10.13+)
* Stock WIFI card needs to be replaced.
* HDMI cables (HDMI & USB-C HDMI) for external displays needs to removed before boot or the internal laptop screen will be black.  
If you remove FakePCIID_Intel_HDMI_Audio.kext, you can leave external displayed plugged in but you won't have Audio over HDMI.

