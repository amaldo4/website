---
author:
  name: "Austin Maldonado"
date: 2021-08-26
linktitle: Getting Started With Raspberry Pi
type:
- post
- posts
title: Getting Started With Raspberry Pi
weight: 10
series:
- Raspberry-Pi
---


## Introduction

The Raspberry Pi has made it incredibly easy for someone to get access to a quality computing experience without having to break the bank. As a college student this is a perfect machine for me.
I can get it up and running quickly, the form factor is small, and Raspberry Pi OS is based on Linux so it is helpful for many of my college classes as a computer science student.
With the release of the Pi 4 in June of 2019, the Raspberry Pi now sports a 2GB, 4GB, and 8GB model, all of which have gigabit ethernets ports, USB 3.0 ports, and an ARM processor. These credit card sized machines are perfect for many applications. 

Getting started with one is easy and you can get it up and running quickly without much effort. 
Below I'll walk through the steps of setting up a Raspberry Pi. 
I personally am using a Pi 4 4GB, but the instructions will be the same regardless of your Pi model.

## Items You'll Need

You'll need the following items in order to get your Pi up and running:
* Raspberry Pi 4 in whatever RAM config you want
* A USB-C power supply (if using Raspberry Pi 4,  Pi 3 and below would use a micro-usb charger)
* MicroSD card (At least 8GB required)
* Keyboard, mouse, and display

Optional items: 
* MicroSD card reader to load items onto SD card, not necessary if computer has a built-in SD card slot.
* Ethernet cable. Not necessary if you plan to use WIFI, but good to have.

## Prepping SD Card
We are going to be using the Raspberry-Pi OS Imager in order to prep our SD card. You can find the Imager [here](https://www.raspberrypi.org/software/).
If you scroll down a little you will see the button to download for Windows. Underneath that are the links for macOS as well as Ubuntu. Click on whatever operating system you are using and wait for the download to finish.

Once your download is finished, you'll want to connect your miscroSD card to your computer, through either a microSD reader or the SD card port that might exist already on your PC/Laptop. Once the card is connected to the computer, run the imager you downloaded.
Running the Imager will install it on your machine. If you are on Windows and receive a "Windows protected your PC" prompt, simply click on "More Info" and then "Run Anyway".
After you install the Imager you will see several boxes were you can choose information.

1. The first box is the OS that we want to install on our microSD card. If you click on the box a drop-down menu will appear, and you can select the OS you want. For this write-up we will use "Raspberry-Pi OS (32-Bit)". Select it and the drop-down will disappear.

2. The second box is the storage we want to use for our OS. Like the OS menu, clicking on the box will open a drop-down of usable storage. Select you microSD and the menu should disappear.

3. The third box will be grayed out until the other two have been selected. After they have been selected, the "write" box will change color. You can now click it to start writing the OS to the microSD card. 
Once the Imager finishes writing to the microSD you will see a pop up titled "Write Successful". Click continue, and your microSD is now ready to insert into your PI.

## Connecting Raspberry-Pi
Before we power up our Raspberry-Pi, we still have some more set-up to do. We want to connect I/O and display devices as well as ethernet or other devices before we start the PI up the first time.
The order or what you plug in doesn't really matter, but you want to make sure it's all set-up before powering the PI on. We will connect the following:
1. Our microSD card. Remove the microSD from the SD adapter or from the SD reader you are using. Insert the microSD into the card slot on the underside of the Pi.
2. Our I/O devices like keyboard and mouse. These can be plugged into any of the USB slots but I prefer to use the non-blue ones, therefore saving our USB 3.0 ports for other things.
3. The monitor we want to use. These can be connected via HDMI. Connect the monitor to the HDMI0 port. It is the port nearest the power cable port.
4. Ethernet cable if we want to use enternet. If you want to use WIFI we can configure that at a later step.
5. If your monitor does not offer audio for some reason, you can connect headphones or speakers to the 3.5mm audio port.

After connecting everything to the Pi, we are ready to start it for the first time.

## Starting the Pi
To start the Pi, simply plug in the power cable to power, then plug the other end into the power port on the Pi. There is no power button on the standard power supply sold by Raspberry Pi, so there is no need to press an "On" button.
Once you plug it in, you will see a red light on the Pi signalling that it is on. While booting, you will also see raspberries on the top left-hand corner of your monitor. Once the Pi is booted you will see the [standard](https://projects.raspberrypi.org/en/projects/custom-pi-desktop/1) background appear.

## Finishing Set-up
We are almost finished but there are a few extra things to set up once the Pi succesfully boots for the first time. 
* After the first boot you will get a "Welcome to Raspberry Pi" application pop up that will help you set up the last parts of your system. Click "Next".
* The next window will allow you to set your Country, Language, and Timezone. Once these are set click "Next" again.
* The next window is where you will set a password for your Pi. The stock password is "raspberry". I'd recommend that you change it to something you will remember. After you have entered your new password, hit "Next"
* The next window is where you can select WIFI networks if your PI has wireless connectivity. If you have already plugged in ethernet then you will not see this prompt. Once you select a network, you'll have to supply the password if there is one. After selecting your network hit "Next".
* The Update wizard will now check for update for the Pi and install them. This part could take a while depending on your network speeds. When it is finished you can click on the "Restart" button to finish setup.

After rebooting your Raspberry-Pi is now ready to use, congrats!

## Closing
The Raspberry-Pi is an awesome piece of computing equipment that offers a lot of bang for the buck. Whether it is used as a media server, a regular desktop computer, or something else, the Raspberry-Pi is a great piece of tech for professionals, students, and hobbyists alike!


