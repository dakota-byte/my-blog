---
title: Scapy Tools
description: A couple of tools I wrote in Scapy
date: 2025-04-12 12:00:00 -0400
categories: [Project]
tags:  [Python, Scapy]
image:
  path: /assets/img/scapy.png
---

I used Scapy to write two networking tools as a part of my Offensive Security class. The first tool is a packet sniffer, and the other
is a network scanner. Both are command-line tools.

### capture.py

The first tool captures HTTP, DNS, and TLS traffic on any given interface. 
The output includes timestamps, source and destination IP, and information regarding what the request or response holds.

[add screenshots]

### tcpscan.py

The second tool performs a TCP port scan on a domain and a number of port(s).
The tool listens for responses & sends probe requests in an attempt to fingerprint the service running on that port.
The tool is capable of differentiating between 6 types of services and outputs the response (if any) received.

The six types of services are:
1. TCP server-initiated
2. TCP

[add screenshots]
