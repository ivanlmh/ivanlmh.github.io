---
title: Accessing the BeoLiving Intelligence
layout: pagetoc
---

The _BLI_ has a web interface that can be accessed from a network browser. By default, _BLI_ is configured on DHCP mode,
meaning that it gets the IP address from the router it's connected to.

### IP address discovery suggestions

- Look up "\_hipservices.\_tcp" using an application that supports Zero-configuration, such as the Safari browser or the avahi-browse command.
- Use a network scanner/IP-scanner (e.g. Fing) on the same network as the _BLI_.
- Access your LAN router and search for the IP assigned to _BLI_. 

### Set static IP address mode

A static IP-address can be set to the _BLI_ by accessing through the web interface, as described in the [*Network*](./06-web_interface_usage#network-conf) section.

### Direct access

The _BLI_ can be set to the factory default IP-address *192.168.1.10* by activating the Setup button function (3); see [Button Functions](./05-user_button). 
Once this address is set, you can access it directly using a network browser and an Ethernet crossover cable. Note that the computer must
have an IP address in the same range, e.g. 192.168.1.11 with subnet mask 255.255.255.0.
