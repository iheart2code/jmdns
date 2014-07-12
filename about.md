---
layout: page
title: About
permalink: /about/
---

JmDNS is a Java implementation of multi-cast DNS and can be used for service registration and discovery in local area networks. JmDNS is fully compatible with [Apple's Bonjour][bonjour].

The [Zeroconf][zeroconf] working group is working towards zero configuration IP networking. [Multi-cast DNS][mdns] and [DNS service discovery][dns_sd] provide a convient ways for devices and services to register themselves, and to discover other network-based services without relying on centrally administered services.

Java as a language is not appropriate for low-level network configuration, but it is very useful for service registration and discovery. JmDNS provides easy-to-use pure-Java mDNS implementation that runs on most JDK1.6 compatible VMs.

The code is released under the [Apache 2.0 license][apache_20] so that it can be freely incorporated into other products and services.

 [bonjour]: https://developer.apple.com/bonjour/index.html
 [zeroconf]: http://www.zeroconf.org/
 [mdns]: http://www.multicastdns.org/
 [dns_sd]: http://www.dns-sd.org/
 [apache_20]: http://www.apache.org/licenses/LICENSE-2.0.html

##History

The project was originally started in December 2002 by [Arthur van Hoff][arthur_email] at Stangeberry. In November 2003 the project was moved to SourceForge, and the name was changed from JRendezvous to JmDNS for legal reasons.

Many thanks to Stuart Cheshire for help and moral support.

In 2014, JmDNS was migrated to GitHub in an effort to revitalize the project. This migration was performed with the blessings of the original authors, and is supported by the [openHAB][openHAB] organization.

 [arthur_email]: mailto:javanator@users.sourceforge.net
 [openHAB]: http://www.openhab.org/
