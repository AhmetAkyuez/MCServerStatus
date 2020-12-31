# MCServerStatus

A lightweight rainmeter skin to visualize query information of a minecraft server build around [mcstatus](https://github.com/Dinnerbone/mcstatus)

<img src="https://i.imgur.com/1kulne1.png" width="1100" />

---

## Usage

- By **double left clicking** you can enter the servername, which can be an IP address `123.456.789.123` or Host name `minecraftserver.com`; Server port can be specified e.g. `minecraftserver.com:25570`
  - <img src="https://i.imgur.com/3ACvwoS.png" width="300" />
- By **scrolling** you can change the font size
  - <img src="https://i.imgur.com/GEuC1A0.gif" width="300" />
- By **right clicking** you can easily change the update rate
  - <img src="https://i.imgur.com/xeKdR4p.png" width="400" />
- By middle clicking you do a full reload of the skin

---

## Installation

### Using .rmskin (Recommended)

- Download the latest .rmskin file from the [releases](https://github.com/AhmetAkyuez/MCServerStatus/releases)

### Manual

- [Download](https://github.com/AhmetAkyuez/MCServerStatus/archive/main.zip) the whole repository and extract the folder to your Rainmeter skins folder `%USER%\Documents\Rainmeter\Skins\`

#### Requirements

- Rainmeter v4.3

---

### Known issues

- Because of changes in V3, the status command occasionally timeouts
- The `mcstatus servername json` command fails on servers like `hypixel.net / 172.65.238.120`
  > - Afaik this is a problem of the [mcstatus](https://github.com/Dinnerbone/mcstatus) python script
  > - Possible circumvention for ping information: use Run command: `ping 172.65.238.120`

---

## License

[![License: CC BY-SA 4.0](https://licensebuttons.net/l/by-sa/4.0/80x15.png)](https://creativecommons.org/licenses/by-sa/4.0/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)


- [mcstatus](https://github.com/Dinnerbone/mcstatus)(Apache License 2.0) python script was compiled into a portable executable to eliminate the requirement of a [python](https://www.python.org/downloads/) installation
- MCServerStatus is licensed under CC BY-SA 4.0 & MIT License
