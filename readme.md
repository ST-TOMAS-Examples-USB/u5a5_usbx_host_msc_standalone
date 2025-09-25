# STM32U5A5 USBX host msc standalone example

Simple example on Nucleo board. 
On ucleo is needed to add second jumper on JP6 on 5V_USB_C to power the usb power. Without it the USB will not add 5V on VBUS. Because nucleo is created for sink only so no dedicated LDO for usb is present. 

The example will read a file from usb stick. USB need to be in FAT32. And there need to be a file `test.txt` for example to work. 

