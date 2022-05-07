# Program TI devices using Uniflash
CCS Uniflash is a standalone tool used to program on-chip flash memory on TI MCUs and on-board flash memory for Sitara processors. Uniflash has a GUI, command line, and scripting interface. CCS Uniflash is available free of charge.<br>
Okay! Now let’s see how to program on-chip flash memory using Uniflash.<br>
For more details refer [TI's Website](https://www.ti.com/tool/UNIFLASH)

Follow the steps for getting started:
* Connect the USB to TTL(CP2102) to USB port of PC and open device manager to check the port connected to serial bridge (USB to TTL).<br>
![Alt text](Images/deviceManager.png?raw=true "Title")
* Open Realterm or any other serial terminal you want to use.
* Open the port to which your serial device is connected make sure to check serial configuration as follows:<br>
    Baudrate : 9600<br>
    Data Bits : 8<br>
    Parity : None<br>
    Stopbits : 1<br> 
![Alt text](Images/serialConfig.PNG?raw=true "Title")
* That's it!!! Now you can tap RFID tag and see it on realterm directly.
## Implementation
![Alt text](Images/RFID.png?raw=true "Title")
## Contributions
For reporting any ```technical issue``` or proposing ```new feature```, please create new [issue](https://docs.github.com/en/issues/tracking-your-work-with-issues/creating-an-issue).



