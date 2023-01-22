# The Unbeyond Team: Main Hub

![Current Issues](https://img.shields.io/github/issues-raw/LeeXDA21/TheUnbeyondHub?color=red&label=Current%20Issues%3A)
![Closed Issues](https://img.shields.io/github/issues-closed-raw/LeeXDA21/TheUnbeyondHub?color=green&label=Closed%20Issues%3A)
![](https://img.shields.io/github/downloads/LeeXDA21/TheUnbeyondHub/total?color=Green&label=Kit%20Downloads)
![](https://img.shields.io/github/v/release/LeeXDA21/TheUnbeyondHub?color=greeen&include_prereleases&label=Current%20Kit%20Version%3A)
[![Channel](https://img.shields.io/badge/Follow-Telegram-blue.svg?logo=telegram&label=Beyond%20News)](https://t.me/+P7IDXNOdDHNmNGZk)
[![Channel](https://img.shields.io/badge/Follow-Telegram-blue.svg?logo=telegram&label=Unbound%20News)](https://t.me/+KyU1HBv6Q2RjMzY0)
[![Download](https://img.shields.io/github/v/release/LeeXDA21/TheUnbeyondHub?color=green&logoColor=orange&label=Download%20Latest%20Kit&logo=DocuSign)](https://github.com/LeeXDA21/TheUnbeyondHub/releases/latest)

![alt text](https://i.imgur.com/OWw45sg.png)

**Credits to Anan1211 for the Logging Kit.**

### How to Report a bug or a request a feature:

* Go to the "Issues" tab
* Select the correct template for your report (There is only 2 options)
* Follow the instructions correctly within the form and provide what is asked.
* Low effort or missing information in the report will see your report being closed & ignored.
* Specifically for bug reports, GATHER LOGS! *Bug reports without logs will be closed.

### XDA Links for The Unbeyond Team:


* [BeyondROM S10]()
* [BeyondROM S20]()
* [BeyondROM S21]()
* [BeyondROM S22]()
* [Project Unbound S20](https://forum.xda-developers.com/t/rom-project-unbound-v2-1-g98x-dvl3-oneui5-0.4429851/)
* [Project Unbound S21](https://forum.xda-developers.com/t/rom-project-unbound-v1-1-g99xb-dvl3-oneui5-0.4521367/)


### How to gather logs with **LoggingKit**
* Download the latest release via [LoggingKit_v5](https://github.com/LeeXDA21/TheUnbeyondHub/releases/download/v5.0/LoggingKit_v5.zip) and follow the legend.

### [With booted System] - **Intended for Crashes, FCs and other SYSTEM Logs**

1) 1. For Windows users: Install **Universal ADB drivers** or **Brand specific ADB drivers** if you don't have them
    2. For Linux and macOS users: To make the files executable, type in Terminal `chmod +x` and drag the files
2) On your phone **enable USB debugging** under `Developer options`
3) Launch your required log type (to find out which logs you should gather, check [Legend](#Legend))
4) Grant `ADB Keys`
5) Close your log type
6) Launch the needed log, again
7) After recording log, attach the created file to your GitHub issue post.

### **Legend**

| Log type | Description |
| :------: | :------: |
| log-ball | Full buffer logcat. Don't use unless requested|
| log-all | Verbose logcat, messy but records everything|
| log-e | Log for Error filter, only shows crashes|
| log-ril | Log for Modem/SIM and other RIL issues|
| log-kmsg | Log for Kernel msg when the kernel panics|
| log-dmsg | Log for Kernel on an active system|
| log-ActiveDmesg 	| Looping Log for Kernel on active system|
| log-dump 	| Get the prev_dump.log (Don't use unless requested by Dev)|

* Being stuck at **`"Waiting For Device"`** means you either **did not auth the adb key** or your **device does not even have debugging enabled**
* **Extra**: You can skip step 3/4 by running **`ADB_Keys.bat`** if you previously allowed your computer ADB
