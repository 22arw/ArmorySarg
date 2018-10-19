# ArmorySargeantApp

The goal of this project is for XPX to develop a cross platform application to employ the M6E Nano RFID reader. With this project specifically focusing on RFID implementation for the 22 SFS Armory in mind.

At the moment we have the chip mounted on an arduino and have to use the native IDE to open a serial monitor to scan/write tags. The final product should resemble the following:

- [ ] A cross-platform deployable application
- [ ] A custom built PCB featuring the M6E Nano, applicable microcontroller, and supporting hardware housed in a custom enclosure.
- [ ] Site infrastructure to make RFID automation possible

## Getting Started

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 6.2.5.

- [ ] ```npm i -g @angular/cli```
- [ ] Navigate to the directory you wish to store this repo
- [ ] ```git clone https://github.com/22arw/ArmorySarg```
- [ ] cd into the newly created folder
- [ ] ```npm install```
- [ ] ```npm run electron```

## Task Listings

### Initial Approach (10/19/2018 - completed)
- [x] Create base Angular app with latest release
- [x] Integrated Electron
- [x] Integrated ClarityUI

### Application Layout (10/19/2018 - updated)
- [x] App level alert in place
- [x] Basic navigation element in place
- [ ] Develop relevant menu items
- [ ] Make connection status icon function (red dot/green dot)
