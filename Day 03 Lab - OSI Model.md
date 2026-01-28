# DAY 03 - OSI Model

## What was conducted in this lab?
In this lab, I utilized simulation mode in Packet Tracer to get a visual understanding of how data traverses through a network and changes at every layer. I was able to see data encapsulate and de-encapsulate between the layers as it traversed between network devices. For example, from Layer 1, I was able to see that ports F0/1 and G0/1 on SW2 were in use, and at Layer 2, they were using the 802.3 standard where bits encapsulated into a frame using the Spanning Tree Protocol. 
Fast forward to when the frame reaches a Layer 3 device, R3, it then becomes a packet and gets source and destination IP addresses. It then uses OSPF protocol to traverse the network. Finally, to see the data at a higher layer, I used the command line to release and renew the IP address of PC1. This used DHCP, a Layer 7 protocol, and allowed me to see data travel among the OSI model.

## Lessons learned?
In this lab, I learned how to read and understand information transmitted between devices in Packet Tracer. It also allowed me to use commands to further interact with the devices, broadening my user experience.
