# Download and Install

Installing S4A requires you to install software both in your PC and your Arduino board. Here you'll find the detailed steps to get it up and running.
Installing S4A into your computer

S4A works in the three major consumer operating systems. Download and install the one that fits your configuration:
    Windows
    Mac
    Linux (Debian)
    Linux (Fedora) (version 1.5)
    Raspbian (Debian for RaspberryPi) (version 1.5)

## Installing the Firmware into your Arduino

This firmware is a piece of software you need to install into your Arduino board to be able to communicate with it from S4A.

    Download and install the Arduino environment by following the instructions on http://arduino.cc/en/Main/Software
    Take in account Arduino Uno requires at least version 0022.
    Download our firmware from here
    Connect your Arduino board to a USB port in your computer
    Open the firmware file (S4AFirmware16.ino) from the Arduino environment
    In the Tools menu, select the board version and the serial port where the board is connected
    Load the firmware into your board through File > Upload

## Arduino drivers

If you are a Microsoft Windows user, you may need to install the Arduino drivers into your computer:
Arduino drivers for Microsoft Windows
For Developers

S4A is free software distributed under an MIT license.

Since Scratch is actually a Squeak Smalltalk image, all of its code is actually shipped with the final user version itself. To access it, just shift + left click on the S4A "File" menu and select "Exit User Mode". You're now in front of a classic Squeak 2.8 image, and have access to a Browser, Workspace and all tools you're used to.

However, in the final user version some code has been compiled and you'll be missing several variable and message argument names, which is why we are also providing you with a clean source code image for developers, downloadable here:


https://www.dropbox.com/sh/5odhz6vin339sgy/AADbe_aQHezQb8JOpaLuvJu1a?dl=0
