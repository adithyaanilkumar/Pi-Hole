
---
name: 'Ad blocker'
description: 'Pi-Hole :  A black hole for all your internet advertisements '
author: '@adithyaanilkumar'
---

Are you tired of those pesky ads popping up when watching your favourite videos online or while playing your favourite games?
Want a better internet experience without these ads? Don't worry, Pi-Hole is here to save the day!

In this workshop, you’re going to create a network wide ad blocker that can block ads across all the devices on your local network.  



## What is  Pi Hole?
Pi Hole is a network-wide ad blocker. It disables almost all ads from all devices connected to  your home network, without having to install an ad blocker on every single device. 
Visit the [Official Website](https://pi-hole.net/) to know in detail.

**Pi-hole intercepts requests for advertisements and prevents them from being downloaded**

## How does Pi-Hole work?
In technical terms, Pi hole is a DNS server which prevents the ads from being located.  In order to understand how Pi Hole works, we first need to understand what a DNS server is.

In simple words, a DNS server is is the phonebook of the Internet. It is a server which looks up the internet address registry to help locate a particular website or a page on the internet. For example, When you type domain names such as ‘google.com’ or ‘hackclub.com’ into web browsers, the DNS server is responsible for finding the correct [IP address](https://www.cloudflare.com/learning/dns/glossary/what-is-my-ip-address/) for those sites.



You can read more about the working of Pi-Hole [here](https://discourse.pi-hole.net/t/how-does-pi-hole-work/3141) .

## Requirements

 - Raspberry Pi/ Linux Machine/ Machine which can run Docker 
 - Minimum 2 GB Micro SD card
 - Ethernet cable or WiFi
## Pi- Hole setup
### Step 1 : Install Raspberry Pi OS
The first thing to do after you have all the requirements above is to install the operating system to run Pi - Hole on your Raspberry Pi.

I personally use Raspberry Pi OS (previously called Raspbian) Lite which operates headlessly and requires very little resources to run.Download the image from [Raspberry Pi OS Download Page](https://www.raspberrypi.org/downloads/raspberry-pi-os/ ) .

After downloading the image you have to write it to the SD card so that the Raspberry Pi can boot from it. To do that we use a tool called [Balena Etcher](https://www.balena.io/etcher/)

Follow the instructions [here]() to know more on how to set up the Raspberry Pi

 

<!--stackedit_data:
eyJoaXN0b3J5IjpbMTg1ODM1NTAyMiwtNzYzMTA5NTY0LC0xMj
EyMjc0MDY1LDEwODA4ODQxNzUsLTIwNjY3NTQ3OCw0OTQxMzQ4
MjYsMTcxMzcwNTQ3LDE5MTgxMjU1NDMsMTczNjY2MjQ2NywtMj
czMTUxODAzLC0xNDA2OTU4MzQxLC0xNDIxMDU2ODY1LDIwNjI1
MDQ4NDZdfQ==
-->