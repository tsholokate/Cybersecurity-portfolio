# Cisco Packet Tracer — Simple Network

## Overview

This project demonstrates the creation, configuration, and testing of a simple network using Cisco Packet Tracer.

The network includes wired and wireless devices connected through a wireless router, cable modem, and Internet cloud.

## Objectives

* Build a simple network topology in Cisco Packet Tracer
* Connect devices using appropriate network cabling
* Configure end devices for network connectivity
* Obtain IPv4 addresses using DHCP
* Configure a laptop for wireless connectivity
* Verify connectivity using network testing tools

## Network Topology

The completed network consists of:

* PC
* Laptop
* Wireless Router
* Cable Modem
* Internet Cloud

The PC is connected to the wireless router using Ethernet. The laptop connects to the wireless router through a wireless connection. The wireless router connects to the cable modem, which connects to the Internet cloud.

## Configuration

### PC

The PC was configured to obtain its IPv4 address automatically using DHCP.

The assigned address was verified using:

`ipconfig /all`

The PC was then used to test connectivity to:

`cisco.srv`

using:

`ping cisco.srv`

### Laptop

The laptop's wired Ethernet module was replaced with the **WPC300N wireless module**.

The laptop was then connected to the wireless network:

`HomeNetwork`

Connectivity was tested by accessing:

`cisco.srv`

through the Packet Tracer web browser.

## Networking Concepts Practiced

* IPv4 addressing
* DHCP
* Ethernet
* Wireless networking
* Network interfaces
* Coaxial cabling
* Connectivity testing
* Basic network troubleshooting

## Tools Used

* Cisco Packet Tracer

## Project Files

The completed Cisco Packet Tracer project file (`.pkt`) is included in this repository.

## Evidence

Screenshots documenting the completed topology, IP configuration, connectivity tests, and wireless connection will be included in this project.

## Key Learning

This practical exercise strengthened my understanding of how end devices communicate through a wireless router and how DHCP provides IP addressing automatically. It also provided hands-on experience with wired and wireless connectivity and basic network verification.
