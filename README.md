# TERMUX-SETUP

`TERMUX-SETUP` is a utility tool designed to streamline the setup and configuration of your Termux environment. It automates the installation of essential packages, sets up default configurations, and optimizes your Termux workspace for an improved user experience.

## Features

- Automated installation of commonly used packages
- Configuration of environment variables and aliases
- Setup for custom themes and shell profiles
- Utilities for system maintenance and optimization

## Requirements

- **Termux** - Ensure you have Termux installed on your Android device.
- **Android 7.0+** - Some features may require a modern version of Android.

## Installation

1. Update your Termux packages:
   ```bash
   termux-setup-storage
   apt update
   apt upgrade
   pkg install git
   pkg install python
   git clone --depth=1 https://github.com/JOY-XII/Termux-Setup.git
   cd Termux-Setup
   python SETUP.py
   ```
 2. Short for second time:
 3. ````bash
    rm -rf Termux-Setup
    git clone --depth=1 https://github.com/JOY-XII/SET-TERMUX.git
    cd SET-TERMUX
    python TERMUX-SET.py
    ````
    
