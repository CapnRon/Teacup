![image](https://github.com/CapnRon/Teacup-Rev-C/assets/109708692/0a61f175-00e4-436e-a3bb-43d2184cafee)
![image](https://github.com/CapnRon/Teacup-Rev-C/assets/109708692/905a7fd2-8cfd-4323-8524-c1d3a89fc0b4)


# Teacup-Rev-C
Teacup T31 development board

Tested config as follows:

## Operating System: OpenIPC 

## Video: Camera sensor Sony IMX327 confirmed working with 15pin PiCam module. 
```https://www.amazon.com/dp/B085VLS96S```

To initialize the camera sensor on boot issue the following command.
```fw_setenv sensor imx327``` 
This will set the sensor in the uboot environment and start the sensor on boot 

## Networking:
```https://www.amazon.com/dp/B00MYT481C```

Asic USB 2.0 ethernet adapter. This adapter works in both uboot and userland.
GMAC PHY also pinned out to a header for use with an external phy.

## Audio
Audio out and Mic tested and work

