# COIT20246_Final

week 4

![Screenshot (48)](https://user-images.githubusercontent.com/128441040/235819408-50346bc4-193c-4910-857b-f8f74817ad57.png)

![Screenshot (49)](https://user-images.githubusercontent.com/128441040/235819425-0a736789-8b64-48ee-bfe5-27ae17d4fbfb.png)
IP Address Table
Device/Interface         IP Address/Mask          Default Gateway
---------------------------------------------------------------
Router 1 LAN Interface   192.168.1.1/24           N/A
Router 1 WAN Interface   10.0.0.1/30              N/A
Router 2 LAN Interface   192.168.2.1/24           N/A
Router 2 WAN Interface   10.0.0.2/30              N/A
PC 1                     192.168.1.2/24           192.168.1.1
PC 2                     192.168.1.3/24           192.168.1.1
PC 3                     192.168.1.4/24           192.168.1.1
PC 4                     192.168.2.2/24           192.168.2.1
PC 5                     192.168.2.3/24           192.168.2.1

Network Diagram
![Screenshot (52)](https://user-images.githubusercontent.com/128441040/235821943-a8aeb116-6e4c-47c6-ae33-a22ad3e3a733.png)

Router 1
Destination     Mask            Next Hop
---------------------------------------------------
192.168.1.0     255.255.255.0   N/A
10.0.0.0        255.255.255.252 10.0.0.2

Router 2
Destination     Mask            Next Hop
---------------------------------------------------
192.168.2.0     255.255.255.0   N/A
10.0.0.0        255.255.255.252 10.0.0.1

PC1

Destination     Mask            Next Hop
---------------------------------------------------
0.0.0.0         0.0.0.0         192.168.1.1

PC2
Destination     Mask            Next Hop
---------------------------------------------------
0.0.0.0         0.0.0.0         192.168.1.1

PC3
Destination     Mask            Next Hop
---------------------------------------------------
0.0.0.0         0.0.0.0         192.168.

