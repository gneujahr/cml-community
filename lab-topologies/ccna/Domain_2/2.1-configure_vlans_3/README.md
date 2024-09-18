# Configure and verify VLANs (normal range) spanning multiple switches

CML Version used: 2.7.0+build.4 In this Lab, we'll explore the fundamental components of network infrastructure and their crucial roles in enabling seamless communication and data exchange. From routers directing internet traffic to access points providing wireless connectivity, we'll delve into the functions of Layer 2 and Layer 3 switches, next-generation firewalls, controllers like Cisco DNA Center and WLC, endpoints, servers, and Power over Ethernet technology. By understanding these components and their analogies to everyday scenarios, we'll gain insights into the intricate workings of networks and their significance in modern connectivity. notes: |- #Task-1.1 Do a small research on Network components and role and functionality. We will see small topology in solution Lab and devices roles and function. title: Task - 1.1[ Netwotk Fundamentals ]
New Value:
CML Version used: 2.7.0+build.4 Welcome to our lab on setting up VLANs, which are like separate virtual networks, on multiple switches! VLANs (Virtual LANs): Think of VLANs as dividing a big house into different rooms. Each room can have its own stuff and people, but they're all still in the same house. Similarly, VLANs let us divide a big network into smaller, separate parts. This helps keep things organized and secure. Access Ports: Imagine these as doors to rooms in our house. Access ports connect devices (like computers or phones) to the network. We have two types: one for regular data and another for voice (like phones). Default VLAN: Every switch has a default room where devices automatically go when they're connected. It's like when you first move into a house, you're assigned a room until you decide where you want to be. The default VLAN is similar; devices are initially put there until we assign them to another VLAN. InterVLAN Connectivity: This is like having secret passages or corridors between rooms in our house. Normally, devices in one room can't talk to devices in another, but with InterVLAN connectivity, they can. This lets different VLANs communicate with each other. So, in this lab, we'll learn how to set up these VLANs, connect devices to access ports, deal with the default VLAN, and make sure devices in different VLANs can talk to each other. Ready to dive in? Let's go! notes: |- #Task-2.1 step1: Configure Vlan 10, 20, 30 and give names managment, HR Team , VIP in IOL-L2-0 switch. step 2: verfiy the working of Vlan step 3: configure the router and switch so that inter vlan communication can happen. step 4: configure the router or switch so that inter vlan communication can happen. step 5: Verfiy the connectvity between managment desktop and infra employee desktop. title: Task-2.1[Configure and verify VLANs]
Reason:


![Lab Topology](https://github.com/CiscoDevNet/cml-community/blob/master/lab-topologies/ccna//Domain_2/2.1-configure_vlans_3/Lab_at_Mon_06_26_AM____CML²_-_Google_Chrome_29-04-2024_12_35_21.png)