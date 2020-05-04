# Guide to Port Forwarding
!!! note
    This guide is work in progress.

## What is a port?
A port in port forwarding is simply a specific number that a service runs on. For example, most of the time websites use port 80 and a Minecraft server usually runs on port 25565. Let's say you have a Minecraft server. If you want other people to be able to connect you need to port forward which will give them permission to access the port the Minecraft server is running on and then connect.

## What is port forwarding?
Port forwarding is the process is allowing a port to be accessed from other devices outside of your network. An example of a network would be your Wi-Fi.

## What is TCP and UDP?
For information about TCP and UDP please see a guide on this by [clicking here](https://www.howtogeek.com/190014/htg-explains-what-is-the-difference-between-tcp-and-udp/).

## How do I port forward?
The process can be _very_ different depending on your router. If you don't know your router is the box that provides your internet. For example, your router might say "Netgear" on it. There a lots of different companies making different routers so this guide will obviously not cover them all but if you are a developer then feel free to create a pull request on GitHub to help add to this guide. Below I have provided instructions for port forwarding on different routers.

### Google Fiber
To port forward with Google Fiber it is actually more simple than most other routers in my opinion. Here are the steps.

1. Go to [fiber.google.com](https://fiber.google.com) and sign in with your Google account.
2. In the top right select "Fiber Account".
3. Select "Network" on the left.
4. Click on the device with the name of your network. It should look similar to the image below.
![](https://ihateyo.ga/wny)
5. Click on "Advanced".
6. Click on "Ports".
7. Click on "Add port forwarding rule".
8. Select the device/IP in the dropdown.
9. Select the service. If you don't know say "Custom".
10. Fill out the necessary information.
11. Click "Apply" and be patient for a few minutes. If it does not seem to work restart the network box in the "Admin" tab next to the "Ports" tab.

### TP-Link
To port forward on TP-Link routers please follow the instructions on [TP-Link support by clicking here](https://www.tp-link.com/us/support/faq/). Select Routers :arrow_right: WiFi Routers :arrow_right: Port Forwarding/Virtual Servers and select the FAQ the applies to your router. It should say the model number on the router.

### Netgear
To port forward on Netgear routers please [click here](https://kb.netgear.com/24290/a).


<br/><br/><br/>
_If you would like a router to be added feel free to create a pull request on GitHub. The GitHub repository can be found in the top right of this page._
