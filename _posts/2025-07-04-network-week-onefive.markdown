---
layout: post
title:  "Network week one #5"
date:   2025-07-04 10:00:00 +0200
categories: jekyll update
---

# A004 Network week one (5)

**(04/07/2025)**

*Transport Layer Security, or TLS, is a widely adopted security protocol designed to facilitate privacy and data security for communications over the Internet. A primary use case of TLS is encrypting the communication between web applications and servers, such as web browsers loading a website. TLS can also be used to encrypt other communications such as email, messaging, and voice over IP (VoIP). In this article we will focus on the role of TLS in web application security.*

TLS evolved from a previous encryption protocol called Secure Sockets Layers (SSL). *HTTPS is an implementation of TLS encryption on top of the HTTP protocol, which is used by all websites as well as some other web services. Any website that uses HTTPS is therefore employing TLS encryption.*

There are three main components to what the TLS protocol accomplishes: Encryption, Authentication, and Integrity.

*-Encryption: hides the data being transferred from third parties.*
*-Authentication: ensures that the parties exchanging information are who they claim to be.*
*-Integrity: verifies that the data has not been forged or tampered with.*

A TLS connection is initiated using a sequence known as the TLS handshake. When a user navigates to a website that uses TLS, the TLS handshake begins between the user's device (also known as the client device) and the web server.

During the TLS handshake, the user's device and the web server:

*-Specify which version of TLS (TLS 1.0, 1.2, 1.3, etc.) they will use*
*-Decide on which cipher suites (see below) they will use*
*-Authenticate the identity of the server using the server's TLS certificate*
*-Generate session keys for encrypting messages between them after the handshake is complete*

To see more info about how the handshake works please check out the source.

*Source: [https://www.cloudflare.com/learning/ssl/transport-layer-security-tls/](https://www.cloudflare.com/learning/ssl/transport-layer-security-tls/)*
