# snowfetch
### An efficient system information fetch tool for Mac OS X Snow Leopard, written entirely in Bash 3.2.

**snowfetch** is a simple, shell-based system information fetch utility written specifically for Mac OS X Snow Leopard (10.6). It displays essential system information in a clean terminal interface together with an ASCII art of Apple logo.

Built with native Bash 3.2 scripting, **snowfetch** requires no additional dependencies and is designed to work with the original Snow Leopard environment.

## Screenshot

<img width="1024" height="768" alt="snowfetch" src="https://github.com/user-attachments/assets/c3a1f972-b9e8-48f2-aa62-48f76a5c2df2" />

## Features

**snowfetch** displays the following system information:

- **OS:**
  Operating system name and version.
- **Kernel:**
  Kernel version and architecture.
- **Init:**
  System PID1 (initialization) process.
- **Uptime:**
  System uptime.
- **Packages:**
  Installed packages from pkgutil, MacPorts and Homebrew.
- **Applications:**
  Applications found in /Applications.
- **Shell:**
  Current shell.
- **Desktop Environment:**
  Aqua, which is always Aqua on OS X.
- **Terminal:**
  Terminal application and build version.
- **CPU:**
  Processor information.
- **GPU:**
  Graphics processor information.
- **Memory:**
  Total RAM capacity and usage.
- **Storage:**
  Total disk capacity and usage.
- **Colors:**
  Terminal color palette.

**Additional highlights**:
- ASCII art of the Apple logo.
- Written entirely in Bash 3.2.
- Designed for retro/legacy Macs.
- Lightweight and easy to run.
- No complicated installation process, no dependency hell, *just simple and stupid*.

## Requirements

- Mac OS X Snow Leopard (10.6),
- Bash 3.2,
- A terminal emulator of choice,
- Nerd Fonts.

> **About Nerd Fonts:** You can grab a Nerd Font of your choice from [Nerd Fonts Download Page](https://www.nerdfonts.com/font-downloads) and install it via Font Book on OS X. Then, select the Nerd Font in your terminal configuration.

## Installation & Usage

No install, compiling or complicated process is required. Even your grandma can use it!

Simply download or clone the repository:
```
git clone https://github.com/m4china/snowfetch.git
cd snowfetch
```

Grant execution permissions to script by giving **snowfetch** executable flag:
```
$ chmod +x snowfetch
```

Finally, **just execute the script!**
```
$ ./snowfetch
```

**To install snowfetch system-wide:**
Move **snowfetch** to `/usr/local/bin`.
```
$ sudo mv /path/to/snowfetch /usr/local/bin
```
(Enter your password if asked.)

## Compatibility
**snowfetch** is developed exclusively for **Mac OS X Snow Leopard (10.6)**. 

Other macOS|OS X versions have not been tested and are not supported, Compatibility with other macOS|OS X releases is not planned. Even if you run **snowfetch** on other macOS|OS X versions, **snowfetch** is written for **Snow Leopard**. 

This project aims to work and run on the good old Snow Leopard rather than provide a universal macOS|OS X system information tool.

## Project Goal

**snowfetch** is built for retro computing hobbyists, classic Mac OS X fans and to respect old terminal guerillas!

I wrote this tool to fetch system information on my Snow Leopard-powered ThinkPad T61 and wanted to share it with everyone. Use **snowfetch** and enjoy yourself while you take a sip of your coffee!

Its purpose is very simple, very stupid: Bring a modern fetch-style system information display to Mac OS X Snow Leopard while staying compatible with its original, out of the box environment.

## License

Please check ``LICENSE`` file in the repository. **snowfetch** is 100% free software!
