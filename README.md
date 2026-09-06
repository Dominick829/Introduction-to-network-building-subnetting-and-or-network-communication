# Introduction-to-network-building-subnetting-and-or-network-communication
Project Summary-

This project will go over how to create a network. How to subnet that network and allow all the devices to communicate with one another. This project is a walkthrough and a lesson. I will show you what subnetting is and how it works. Components of a network, what each network device does, and finally how to make all of these network devices communicate with one another. 

Languages used-

We will use a command-line interface to interact with and program the devices shown in the walkthrough. 

Environment used-

This project will be done in Packet Tracer. You can download Packet Tracer in order to follow along with the walkthrough later in the project by following this link. 
https://www.netacad.com/courses/getting-started-cisco-packet-tracer?courseLang=en-US
________________________________________________________________________________________________________________________________________________________________________________________________________________________________

Subnetting-

Subnetting is the practice of splitting a single, large network into smaller, logical sub-networks called subnets. 

It divides IP Address blocks into smaller pieces so that networks can communicate efficiently.

So one simple way to learn, remember, and then apply is to remember that the subnet mask determines the size of the network. Now, say for example you have a /27 network. A /27 translates to 255.255.255.224, leaving 32 addresses per subnet. However, only 30 of those addresses are usable because the 192.168.1.0/27 address is the network address for the subnet, and the 192.168.1.31/27 address is the broadcast and these are not usable for hosts and devices. The other 30 addresses in between are usable. The subnets are then divided into increments of 32, so the next subnet would be 192.168.1.32, then .64, then so on until 192.168.1.224; this would be the last subnet. After that, you would move to 192.168.2.0/27; however, now the 192.168.1.0 network and 192.168.2.0 are separate networks, and this is where routers (or Layer 3 switches) come in to allow these two networks to communicate with each other. 

Below is an image that you can use to help you understand subnetting more and to use to subnet yourself.

<img width="600" height="600" alt="image" src="https://github.com/user-attachments/assets/3e3cce49-0ce3-4c01-899a-8dc5382975d1" />
____________________________________________________________________________________________________________________________________________________

Components of a network- 

For communication between networks, you use devices known as routers, or you can also use layer 3 switches. 

Routers: A router is a hardware device that forwards data packets between different computer networks, such as connecting your home network to the internet.

Layer 3 switches: A Layer 3 switch is a high-speed networking device that combines traditional Layer 2 switching (forwarding data using MAC addresses) with Layer 3 routing (forwarding data using IP addresses) inside a single unit.

For communication within a network, you use Layer 2 switches, also known as switches. 

Switch: A network switch is a hardware device that connects multiple devices—like computers, printers, and servers—together to form a local area network (LAN).

Below is an image with more information on network devices. 

<img width="600" height="600" alt="image" src="https://github.com/user-attachments/assets/00cbdb78-a82b-4f42-aab7-a3788053f979" />
_____________________________________________________________________________________________________________________________________________________

Now is the practical follow-along portion where we will combine these concepts into a real network. Watch and follow along with this video. 

[![Watch the demo](<img width="552" height="513" alt="image" src="https://github.com/user-attachments/assets/7888ed46-c59b-448e-9f2c-a71a3bab16aa" />
)](https://youtu.be/1nbD2payPJo)

Thanks for following along with this project I hope you learned something and it was all digestable and understandable if you have any questions about what I showed today please either reach out to me or do some independent reasearch about whatever questions you may have. 
