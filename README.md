# Argon One V2 Pi 4 Installation Guide
If you havent already assembled your Argon One V2 Pi 4 Case, please assemble it first.  
If you need help with that look through the assembly manual provided inside the box.  
If your manual is missing or prefer to look it up online instead i have a PDF manual for you to download/look through.


### Installation

1. Connect to the internet.
2. Open "Terminal" in Raspbian.
3. Type the text below in the "Terminal" to initiate installation of Argon ONE (V2) Pi 4 script.

   ```
   curl https://download.argon40.com/argon1.sh | bash
   ```

4. Reboot.


##  Default Config and Instructions

### Argon ONE V2 Pi 4 Power Button Functions
The process above will automatically install the configuration that will activate the Argon ONE Pi 4 power button with the following functions.

ARGON ONE V2 PI 4 STATE | ACTION                  | FUNCTION
:------------------:    | :---------------------: | :------:
OFF                     | Short Press             | Turn ON
ON                      | Long Press (>= 3 s)     | Soft Shutdown & Power Cut
ON                      | Short Press (< 3 s)     | Nothing
ON                      | Double Tap              | Reboot
ON                      | Long Press (>= 5 s)     | Forced Shutdown

### Argon ONE V2 Pi 4 Fan Speed
Upon installation of the Argon ONE V2 Pi 4 script by default, the settings of the Argon ONE V2 Pi 4 cooling system are as follows:

CPU TEMP | FAN POWER
:------: | :-------:
55 C     | 10%
60 C     | 55%
65 C     | 100%

However, you may change or configure the FAN to your desired settings by clicking the Argon ONE V2 Pi 4 Config icon on your Desktop.
Or via "Terminal" by typing and following the specified format:

```
argonone-config
```

## Uninstalling Argon ONE V2 Pi 4 Script
To uninstall the Argon ONE V2 Pi 4 script you may do so by clicking the Argon One V2 Pi 4 Uninstall icon on your Desktop.
You may also remove the script via "Terminal" by typing:

```
argonone-uninstall
```

Always reboot after changing any configuration or uninstallation for the revised settings to take effect.


## Built-In Infrared Receiver
The latest version has a programmable infrared receiver installed that can turn ON and OFF the device using the proprietary Argon 40 remote.  
To configure the Infrared Receiver ON/OFF signal of Argon One V2 and M2 type in the Terminal App:

```
argonone-ir
```

Then follow the instructions included.  

For more information please visit:  
~~https://www.argon40.com/learn/~~



