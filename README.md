# xcap
Xcap is a windows based packet generator &amp; sender tool, you can use it to create a packet, then send it through a specified interfaces on you computer.

## Purpose of this repo
The official site of xcap is http://xcap.weebly.com. It's a bit of slow in China, so I put its binary for personal backup.

## Source of xcap
Xcap is not open now. 

> Tool is free, source code is not open.
> If you find any problems, please tell me, cxxxap@gmail.com
> From: http://xcap.weebly.com/source-code.html 

You can find it's old version source code in google code, [link](https://code.google.com/p/xcap/). 

## Requirements
Windows XP/Windows7
Winpcap 4.0.2 or higher version, you can download it from http://www.winpcap.org/

## xcap's functionality:
Constructing packet
Sending packet through networking interface

## where xcap can be used:
networking stack test
ethernet device test
networking protocol training

## Now it supports a lot of protocols, including:
1. Arp/ipv4/ipv6/icmpv4/icmpv6/tcp/udp/udplite/igmp
2. mpls/pppoe/gre
3. rsvp/l2tp/radius/snmp/esp/ah
4. rip/ripng/pim/ospf/igrp/vrrp
5. 802.3/8021x
6. l2 switch protocl, such as stp/lacp
7. other l2/l3 protocols

## How to run this tool:
1. you should install winpcap 4.0.2 or higher version at first, if you have already installed wireshark, that is OK.
2. download the zip file
3. unzip it
4. double click xcap.exe
5. please read help(in menu help) at first

## What you can do through this tool:
1. create a packet by a packet creating wizard, edit any byte in this packet, to create a packet, you should create a packet group at first, then create new packet in this packet group, double click the new created packet, follow the wizard to complete the packet
2. send the packet you created, you should refresh all interfaces in your computer, you can select one interface and start it, then in the packet group panel, select this interface to send the packets you created.
3. create ipv4&ipv6 fragments, you can create a long packet(can not exceed 16K bytes), then right click the packet, click "create fragments", input length for each fragment, this tool will divid the long packet into some fragments.
4. browse the packet by wireshark, when you create some packets in this tool, if you have installed wireshark in you computer, you can browse this packet in wireshark, to use this function, you should choolse "auto" in system tab in configuration dialog, right on packet group or packet, click "view" command to browse this packet in wireshark.

