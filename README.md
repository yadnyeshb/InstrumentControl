# Control_Instrument_VISA
 Simple Python script using PyVISA to control an instrument e.g. Variable Power Supply

## _Prerequisites_
 **Python 3 installed (Tested on Python 3.7)**
 
 **Python PyVISA 1.7 package or newer installed**
    
    First install pip at python 3 : Check google
    Install PyVISA via pip : https://pypi.org/project/PyVISA/
    
 **Power supply is controlled via serial port [Tested] ** 
    
    Connect the power supply serial port to the laptop.
    
    Edit the script as per usage (Check for correct COMx)
    
    At power supply use (57600, 8 bit, No parity, Xon/Xoff)    
    
    Communication channel instead of Serial port can be used. Check out :
    https://pyvisa.readthedocs.io/en/1.5-docs/instruments.html#gpib-devices
