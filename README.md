# MCServerStatus

A lightweight rainmeter skin to visualize query information of a minecraft server by [mcstatus](https://github.com/Dinnerbone/mcstatus)

<img src="https://i.imgur.com/IV4BmUE.png" width="600" />

---

## Installation

### Using .rmskin (Recommended)

- Download the latest .rmskin file from the [releases](https://github.com/AhmetAkyuez/MCServerStatus/releases)

### Manual

- [Download](https://github.com/AhmetAkyuez/MCServerStatus/archive/main.zip) the whole repository and extract the folder to your Rainmeter skins folder `%USER%\Documents\Rainmeter\Skins\`

#### Requirements

- Rainmeter v4.3

---

### Usage

- By **double left clicking** you can enter the servername, which can be an IP address `123.456.789.123` or Host name `minecraftserver.com`; Server port can be specified e.g. `minecraftserver.com:25570`
- By **scrolling** you can change the font size
- By **right clicking** you can easily change the update rate
- By middle clicking you do a full reload of the skin

---

### Known issues

- If the query port deviates from the standard, the query command will fail
  - Can be manually fixed if the query port is known
- If the MotD includes Unicode characters, the MotD and subsequently the Player information cannot be displayed; Even with the following command I wasn't able to resolve this
    <details><pre>
    powershell -NoProfile -ExecutionPolicy Bypass -NonInteractive -Command "[Console]::OutputEncoding = New-Object -typename System.Text.UnicodeEncoding; & .\mcstatus.exe #Servername# status"
    </pre></details>
- The json command fails on servers like `hypixel.net`, Afaik this is a problem of the [mcstatus](https://github.com/Dinnerbone/mcstatus) script

---

## License

[![License: CC BY-SA 4.0](https://licensebuttons.net/l/by-sa/4.0/80x15.png)](https://creativecommons.org/licenses/by-sa/4.0/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)


- [mcstatus](https://github.com/Dinnerbone/mcstatus)(Apache License 2.0) python script was compiled into a portable executable to eliminate the requirement of a python installation
- MCServerStatus is licensed under CC BY-SA 4.0 & MIT License
