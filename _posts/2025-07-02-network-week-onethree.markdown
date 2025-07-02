---
layout: post
title:  "Network week one #3"
date:   2025-07-02 10:00:00 +0200
categories: jekyll update
---

# A003 Network week one (3)

**(02/07/2025)**

Internet Protocol, or short known as IP.  Same as with previous blog posts I'll try to keep this shallow. Most topics have a rabbitholes deep enough to write essays about and as mentioned earlier, I'm not here to do that *at all*.

We've all(hopefully) heard about an IP address once in our life. The weird numbers ranging from 0.0.0.0 to 255.255.255.255, those ones. These numbers are IPv4, there's also a later version because believe it or not, we've started to run out of IPv4 addresses. That's where IPv6 got introduced, which has even *weirder* numbers, i.e. 2001:0db8:0000:0000:0000:ff00:0042:8329 (full form), we can make this shorter but this gives us an idea.

The IP has a pretty straight-forward task; delivering packets from the source host to the destination host solely based on the IP addresses in the packet headers.  The way this is split up is; IP defines packet structures that encapsulate the data to be delivered. This encapsulation turns into a datagram(what actually goes over the internet), each datagram has two components: a *header* and a *payload*. The header includes a source IP address, a destination IP address and metadata that is needed to deliver the datagram. The payload is the data that is transported. This method is called encapsulation(what was mentioned earlier).

For more information about this protocol, help yourself.

*source: [https://en.wikipedia.org/wiki/Internet_Protocol](https://en.wikipedia.org/wiki/Internet_Protoco)*