![IRIS Broadcast](logo-iris.png)

Home - [About ACIP](README_ABOUT.md) - [Contributers](README_CONTRIBUTERS.md)

# Welcome
IRIS Broadcast is a project founded in Sweden to publish Open Source software for professional radio broadcast. The IRIS Codec Call Monitor (CCM) is available for download on GitHub.com.

CCM contains both a live overview of the current broadcasts in our SIP-based contribution network as well as a management platform and a discovery service frequently described as the “Active Phonebook”. The platform is used 24/7 producing over 2500 hours of live radio every month.

The journey from our launch in May 2017 to the initial release of the software November 1st 2017 has been be covered on this website as well as on Twitter (@irisbroadcast). Now the journey continues – forming an open project, creating a dialog with our users and interacting to produce better software.

Our solutions are based on the EBU and IETF standards and are built for national public radio to manage our external contribution platform.

The CCM software is the heart of the IP based contribution network, giving users an overview of the live calls. It also provides a dynamic directory service to all codecs.

The CCM code is now available on [Github.com/irisbroadcast](http://github.com/irisbroadcast) for download, testing and improvements. We invite you to test it and give us feedback!


![IRIS Broadcast System Diagram](system-diagram.png)

# THE SOFTWARE - IRIS

The IRIS Broadcast Platform is a management software for live broadcast using ACIP-compatible codec equipment in a professional radio environment.  A versatile and extensible solution based on many years of experience and thousands of hours of live radio produced.

It's a software suite:
#### IRIS Codec Call Monitor + Discovery (.NET MVC + MySQL /MSSQL) (Windows Server)
- Kamailio event reciever
- Discovery REST API [https://github.com/IrisBroadcast/CCM/tree/master/CCM.DiscoveryApi](Description)
- General Query REST API + Web Socket (SignalR)
- Administrative Interface + Monitor + Statistics

[Github.com/irisbroadcast/CCM](https://github.com/IrisBroadcast/CCM)

#### IRIS Connect (Kamailio + MySQL + RTPengine media server 'Open Source') (Debian Linux)
- Kamailio configuration for sending events to CCM

[Github.com/irisbroadcast/Connect](https://github.com/IrisBroadcast/Connect)

#### IRIS Codec Control (.NET CORE MVC) (Windows/Linux) *Add this if you need codec control*
- Proxy for Codec Control requests, protocol translation and unification
- Query's CCM with SIP-address for getting IP-address to control
- REST API + Web Socket (SignalR) interface for codec control

[Github.com/irisbroadcast/CodecControl](https://github.com/IrisBroadcast/CodecControl)

#### IRIS Dialer (Release May 2019)
- A dialer implementation with the Active Phonebook (IRIS Discovery) and Codec Control API. 

## Platform-independent user friendly interface

Built with the user in focus, IRIS Broadcast delivers a lot of flexibility in a graphical user interface built to support a professional broadcast production. Delivered as a web-based application, the monitor can be used on many devices – from mobile units to wall displays updated in real time.

## Modular design

The platform consists of several modules that together support the contribution network. IRIS Codec Call Monitor and IRIS Discovery are the management platforms. IRIS Connect is the companion SIP server configuration for the Kamailio Open Source SIP server.

## Free to use, modify and put in production

The IRIS Platform is licensed using an Open Source license. We are working on finding out which one, based on the libraries used in building the software. The license will mean that IRIS Broadcast can be freely used in your production, also giving you the rights to modify the software as you wish. We want to build a strong community surrounding the platform and invite you to participate!

___

## Features

- Realtime monitoring of all active sessions, including details about the sessions
- Check availability of all connected devices
- Optimize call setup based on network properties, equipment capability
- Integration with many different codecs
- SIP server configuration optimised for live radio contribution

## Benefits

- Best possible audio used in every session
- Gives the master control room an overview of current sessions
- Get statistics over usage per codec type, region or user
- Helps users find available codecs
- Standardised SIP server platform supporting all standard SIP user agents.
- Ready-to-run configuration
- Scalable to thousands of devices and calls

## Technical features

- SIP registrar and proxy supporting standard SIP codecs
- Open Source software and configuration
- Failover between datacenters
- Realtime replication between servers
- Integration with IRIS CCM and discovery using HTTPS
- Support for SIP using UDP, TCP and TLS
- Support for IPv6 and IPv4

## Availability

The IRIS Codec Call Monitor and Discovery platform is available for free download on github.com/irisbroadcast. The software is licensed with the BSD 3-clause license, an Open Source license. Follow us on Twitter as @irisbroadcast or check the web site for further updates.
