---
layout: default
title: Reverse Engineering Freebox Revolution V6
permalink: /
---
OpenFreebox Revived is a reverse engineering project for the Freebox Revolution V6, a feature-packed ISP router + TV box combo from the French ISP "Free" (part of the "Iliad" group).

### Status
Project is still in a very early stage.

### Goal
My first goal with this project is successfully reverse engineering the OS from both boxes (Server, which is the router and NAS, and Player, which is the TV box with Blu-ray reader), in order to make it work anywhere in the world without a subscription from "Free".

My second goal is to successfully install a custom version of Linux on the Player (more info about the architecture of the boxes below).

### Box architecture and specs
Specs from: me, [CNX Software](https://www.cnx-software.com/2010/12/15/freebox-revolution-quadruple-play-set-top-box-internet-tv-voip-mobile/), and Tom's Hardware [Server](https://www.tomshardware.fr/freebox-revolution-ce-qui-se-cache-dans-le-serveur/) - [Player](https://www.tomshardware.fr/freebox-revolution-au-tour-du-player/)

**Server (router + NAS):**

* ARM9 1.2GHz processor

* 512MB RAM

* 250GB Hitachi Cinemastar C5K500.B HDD

* 4 Ethernet ports: 10 / 100 / 1000 Base-T

* ADSL / ADSL2+ ANSI T1 413 / ITU G.992.1, G.992.3, G.992.5 Annex A

* 2x USB 2.0 Ports, e-SATA Port, SFP port, FXS port

* Wi-Fi 802.11b/g/n 3×3 450 Mbps 2.4 Ghz

* Base Station DECT CAT I/Q

* OLED screen and touch-sensitive controls (on front)

**Player (TV + Blu-ray):**

* Intel Atom CE4150 1.2GHz (x86 CPU)

* PowerVR 400MHz (based on SGX535)

* 1GB DDR3-1333 RAM

* 256MB NAND (firmware)

* Video: SCART, HDMI 1.3

* 2x USB 2.0 Ports, e-SATA Port, SPDIF out

* DVB-T ETSI EN 300 744 (TNT TV)

* Slot-loading Blu-ray 3D + DVD drive: CD-DA, CD-ROM, CD-R, CD-RW, DVD-ROM, DVD+-R, DVD+-RW, BD-ROM, BD-R, BR-RE

### Useful links
[Comment dézoner la Freebox V6](https://korben.info/dezoner-freebox.html)

[OpenWRT, Freebox et IPv6](https://guillaume.vaillant.me/posts/2013-03-20-openwrt-freebox-et-ipv6/)

[Faire fonctionner le Freebox Player (TV) avec une Freebox en mode bridge](https://korben.info/tele-freebox-bridge.html)

[Freebox Revolution, routeur DDWRT et mDNS](https://clement.storck.me/blog/2011/08/freebox-revolution-routeur-ddwrt-et-mdns/)

[Les entrailles de la Freebox 6](https://www.oezratty.net/wordpress/2010/les-entrailles-de-la-freebox-6/)
