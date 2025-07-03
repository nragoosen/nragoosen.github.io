---
layout: post
title:  "Network week one #4"
date:   2025-07-03 10:00:00 +0200
categories: jekyll update
---

Ports

Starting off with what  a port is; *A port is a virtual point where network connections start and end.* To put this in perspective, we can compare it to the number of a house in a street. Lets say the name of the street is the address, then we can use the port as the number of the house. So for example: 127.0.0.1("streetname"):5000("number"). This way the data that is sent knows where exactly to deliver it. 

Port numbers range from 0-65535, in this range the numbers are divided in three ranges: *the well-known ports*, *the registered ports* and *the dynamic of private ports*. The well known parts range from 0-1023 (in the source you can find notable well-known port numbers). The registered ports range from 1024 to 49151. The dynamic or private ports are those in range from 49152 to 65535.

When using ports in the web-browser, HTTP uses port 80 by default and HTTPS uses port 443 by default. When entering a URL in the web-browser, depending whether its HTTP or HTTPS the browser uses the default port. If you want to use a different port you need to specify that in the URL you want to go to.

*sources: [https://www.cloudflare.com/learning/network-layer/what-is-a-computer-port/](https://www.cloudflare.com/learning/network-layer/what-is-a-computer-port/)[https://en.wikipedia.org/wiki/Port_(computer_networking)](https://en.wikipedia.org/wiki/Port_(computer_networking))*