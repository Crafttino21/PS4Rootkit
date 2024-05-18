# PS4Rootkit
a "easy-to-use" automation script for the PPPwn Exploit by TheFlow and LightningMods.

[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/X8X7MF230)

- Original PoC Payload by TheFlow: [PPPwn PoC](https://github.com/TheOfficialFloW/PPPwn).
- LightningMods Loader for PPPwn: [LM Loader](https://github.com/LightningMods/PPPwn)
- SiSTR0 Loader for GoldHEN: [SiSTR0 Loader](https://github.com/SiSTR0/PPPwn)
- GoldHEN Payload by SiSTR0: [GoldHEN](https://github.com/GoldHEN/GoldHEN/tree/2.4b17)

## READ BEFORE USING GOLDHEN PAYLOAD!
**At First GoldHEN Released by SiSTR0 is FInally Supported by PS4ROOTKIT!**
But there are Limitations!
If you wanna use GoldHEN for 9.00 you need to Manually Update the Payload!
PS4Rootkit **DOSN'T** do the part for the USB! You need to do that by your own!


**Features**
* Install all needed packages for PPPwn 
* Run the Exploit easy and userfriendly
* Minimize the Risk of errors by a step to step way to got.

**What is PPPwn?**
PPPwn is a Exploit for the Playstation that allows running Remote code on Kernel layer.
This is an Important part for a jailbreak. The vulnerabilities was found and reported by TheFlow.
This Tool use his PoC Exploit. GoldenHEN Payload will be added if they Release the Port for 11.00!

**IMPORTANT**
This Tool is ONLY for Ubuntu-based Linux Distros and NOT FOR WINDOWS!!

**If you need help**
Contact me Here: [Twitter](https://twitter.com/WeepingTheReal)

## How to install
**Prerequisites**  
* [Python](https://www.python.org/downloads) 3.9/3.10/3.11
* Pip (In PATH)

## IMPORTANT
I'm often asked why the exploit doesn't work on some consoles. 
I read that the models listed below are **possibly** not supported and the exploit doesn't work there:
* `CUH-22xx (SAF-006 motherboard)`
* `SAE-003 (1-982-481-11) Motherboard`

In some tests the here listed Models and Motherboards reacted with kernel panics or
the PPPwn exploit failes 100% of the Time at "cannot find corrupted object".
There are maybe other models with the same problems of Incompatibility.

Source: [Twitter](https://x.com/CelesteBlue123/status/1791768630285254774)
 
### Linux:
* `sudo apt update`  
* `sudo apt-get install git` <== Skip this if you have it already  
* `git clone https://github.com/Crafttino21/PS4Rootkit.git`
* `cd PS4Rootkit`
* `pip3 install -r requirments.txt`
* `sudo python3 ps4rootkit.py`.

## Thanks to:
* SiSTR0 for GoldHEN, the stage2 Loader and for your part on the Modding Community
* TheFlow for the PPPwn Exploit
* MODDED WARFARE for the helpfull Videos
* LightningMods for the LM Loader and the Really got Homebrews
* All the other people that takes a part in the GoldHEN Development and Modding Community :)


  
 


