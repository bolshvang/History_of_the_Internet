Home &nbsp; &nbsp; About &nbsp; &nbsp; Fun Facts &nbsp; &nbsp; Important People and Dates &nbsp; &nbsp; Wires WIFI and Binary Code &nbsp; &nbsp; IP and DNS &nbsp; &nbsp; Packets and Routing &nbsp; &nbsp; Contact

&nbsp;


# **Packets, Routing, and Reliabilty**

![packets](https://cdn.kastatic.org/googleusercontent/HR2g096sZ_5ZKoDeY5G_f8FRD7tEXVaGV2CfsKPBUhKSkdtORn9vpHH2Y9hHc6BGo-9nQq6JNYFHlb2CzXEHi-wv)

---
-  Paul Baran borrowed an idea from the telegraph, and decided to chop up each message (data) into small equal size pieces called **Packets**
- Each packet was like a postcard with a TO and From address. No dedicated path. Packets take any path available to them until they find their way to the destination
- Then the packets stop at different **Nodes**, these nodes collect the info, make copies, and keep sending the info out till it arrives successfully to the next node 
- *Hot Potato Routing* meant a message transmitting a network could be delivered even if part of the network was destroyed 
- Transmission Control Protocol - manages the sending and receiving of all your data as packets (Guaranteed Mail Service)
    - For example, when you request a song on your device, Spotify sends you the song broken up into many packets, when your packets arrive, TCP does a full inventory check and sends back acknowledgements of each packet recieved, if all packets are there, TCP signs for your delivery and you're done
        - If TCP finds some packets are missing, it will not sign, and your song won't sound as good or will not play fully, for each missing or incomplete packet, Spotify will resend them, once TCP verifies the delivery for that song request, your song will start to play
- What is great about the TCP and router systems is that they are scalable, they can work with 8 devices or 8 billion devices
    - Because of these principles, the fault tolerance and redundancy, the more routers we add, the more reliable the internet becomes
- Devices can connect, communicate, and collaborate because of agreed upon standards for how data is sent around the internet 
