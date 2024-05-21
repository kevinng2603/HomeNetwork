<h1>Packet Tracer - Configure a Wireless Router and Clients</h1>
<!--
 ### [YouTube Demonstration]
!-->

<h2>Project Summary</h2>
This lab involves configuring a home network for a friend, Natsumi, using Packet Tracer. The steps include connecting devices to the network, configuring a wireless router, setting up IP addressing, and verifying internet connectivity for all devices. The goal is to ensure that Natsumi's home network is fully functional, secure, and provides reliable internet access.
<br />

<h2>Objectives</h2>

- <b>Connect devices to a home network </b>
- <b>Configure a wireless router </b>
- <b>Configure IP addressing and test connectivity </b>

<h2>Step by Step Instruction</h2>

- <b>[PT Activity](HomeNetwork/Configure.md) </b>

<h2>Languages and Utilities Used</h2>

#### Download and Install these 2 files:

- <b>Cisco Packet Tracer - [[Download the version of Cisco Packet Tracer you require]](https://skillsforall.com/resources/lab-downloads?courseLang=en-US)</b> 
- <b>Configure Wireless and Router Package - [[Download Packet Tracer Project]](4.4.4-packet-tracer-configure-a-wireless-router-and-clients.pka) </b>



<h2>Environments Used </h2>

- <b>Windows 10</b>

<h2>Program walk-through:</h2>

### Connect devices to a home network 

##### Part 1: Connect the Devices
- **Coaxial Cables Connected:** Cable Splitter connected to the cable modem, and connected to the television.
  ![Coaxial Cables](https://i.imgur.com/hvjyvcx.png)
  
- **Internet Connection:** Home Wireless Router connected to the cable modem for internet access.
  ![Internet Connection](https://i.imgur.com/ogkWFW8.png)

- **Network Cables Connected:** Office PC and Bedroom PC connected to the Home Wireless Router using Ethernet cables.
  ![Network Cables](https://i.imgur.com/6oNDHaf.png)

##### Part 2: Configure the Wireless Router
- **Router GUI Accessed:** Logged into the Home Wireless Router GUI via Office PC.
  ![Router GUI](https://i.imgur.com/6zjXNnN.png)
- **DHCP Configuration:** Set to limit to 10 devices.
  ![DHCP Configuration](https://i.imgur.com/fzReXOW.png)
- **Admin Password Changed:** Default password changed to `MyPassword1!`.
  ![Admin Password](https://i.imgur.com/ZQ4x1zq.png)
- **Wireless Network Configured:** SSID set to `MyHome`, security set to WPA2 Personal with passphrase `MyPassPhrase1!`.
  ![Wireless Configuration](https://i.imgur.com/ubyfLnR.png)
  ![Wireless Configuration](https://i.imgur.com/raxtUjW.png)
  
##### Part 3: Configure IP Addressing and Test Connectivity
- **Laptop Connected to Wireless Network:** Successfully connected to `MyHome` network and accessed the internet.
  ![Laptop Connection](https://i.imgur.com/bJtTfLT.png)
- **Laptop DHCP Configturation :** Check Laptop Wireless Network Status
  ![Laptop Connection](https://i.imgur.com/oJkdzHS.png)
- **Laptop Web Brownser :** Verify that the Laptop can now connect to skillsforall.srv
  ![Laptop Connection](https://i.imgur.com/haZSM3b.png)
- **Office PC Internet Access Verified:** Office PC connected to the internet.
  ![Office PC Internet](https://i.imgur.com/tORkfex.png)
- **Bedroom PC Configured and Connected:** Bedroom PC set to DHCP and connected to the internet.
  ![Bedroom PC Internet](https://i.imgur.com/GZscIYR.png)
- **TV Connected:**
  ![TV Connection On](https://i.imgur.com/eUbxtvb.png)
## Conclusion
All devices are connected to the home network and have internet access. The home network is fully operational, and Natsumi is ready to enjoy her new setup.

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
