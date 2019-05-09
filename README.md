# ADB-Over-Wifi-Bash
This is Bash Scripts that help you select and enable adb over wifi.

## Setup

First time setup, change file permission to excultable 

- Open terminal and locate "set_adb_over_wifi" bash script 
- Run command 
```
chmod +x set_adb_over_wifi 
```

Now you are ready to use this Bash script

## Usage
- Connect your devices via cable to your computer first.
- Make sure you already enable USB debugging in Developer option.
- Open terminal and locate "set_adb_over_wifi" bash script.
- Run command 
```
./set_adb_over_wifi 
```
- Terminal will show list of your devices
![alt text](https://raw.githubusercontent.com/ammarptn/ADB-Over-Wifi-Bash/master/src1.png)
- Select devices that you wish to setup ADB over Wifi by Enter number (If you have only one devices connected, it will skip this step)
![alt text](https://raw.githubusercontent.com/ammarptn/ADB-Over-Wifi-Bash/master/src2.png)
- Wait for a sec , unplug connection and your devices will ready to access over wifi.
![alt text](https://raw.githubusercontent.com/ammarptn/ADB-Over-Wifi-Bash/master/src3.png)

## Remark
- if you change wifi network, you need to connect and run command again.
- if you kill ADB, you need to connect and run command again.

## Bonus
- You can add the bash script as external tool in Android studio
 - Go to Preference > tools > external tools
![alt text](https://raw.githubusercontent.com/ammarptn/ADB-Over-Wifi-Bash/master/src4.png)

 - click plus sign at the bottom to add.
 - Enter name, Description and browse for the "set_adb_over_wifi" bash script
![alt text](https://raw.githubusercontent.com/ammarptn/ADB-Over-Wifi-Bash/master/src5.png)

 - Now it ready to use. You can access from Tools > External tools
![alt text](https://raw.githubusercontent.com/ammarptn/ADB-Over-Wifi-Bash/master/src6.png)
## More Bonus
- you also can make it super convininet to use by assign keymap to it.
- Go to Preference > keymap > Search for "ADB over wifi"
- Set your prefered key to it.
- Now, Connect your devices and press your key combo
- unplug
- back to work

