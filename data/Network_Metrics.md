# Overview of network metrics
You are provided several values that can be used to identify problems (or opportunities) in a customer's home network. The following is some helpful information about how to use the data to help customers either troubleshoot their problems or select products that can improve their experience.<br>
* **RSSI (Received Signal Strength Indicator)** - The RSSI value is an indicator of the signal strength of a wireless connection. The lower (negative) value, generally, the worse the connection and the worse speed you will have. As values go below -60dBm, customers may even see drop outs, buffering, high latency (lag or ping times), and other symptoms of poor wireless connectivity. However, poor RSSI doesn't *always* mean poor experience. A Kindle or WiFi lightbulb doesn't **need** great speed or low latency, just "good enough" connectivity to be used.<br><br>
   > Commonly, the best way to improve RSSI is to move a device closer to the WIFI router, or add an extender mid-way between the device and the router. Alternately, you could connect your device to the router with an ethernet cable. Usually, this is reserved for gaming stations and high end PCs.
* **Extenders** - As stated, one way to improve network connectivity for wireless devices is to add an extender. This is a device you can add to your network that retransmits wireless signals to improve RSSI (and therefore, speed and connection quality). Adding too many extenders is also bad as you can "pollute" the network. Extenders are commonly placed midway between your router and the farthest device. This can be on a different floor or in a different part of the house (or garage, etc.). Extenders can either be wireless (they connect to the router wirelessly) or wired (using an Ethernet cable).<br><br>
   > Commonly, extenders are added based on square footage of a house. In most cases, you don't need an extender unless your house is > 2000 sq. ft., has multiple floors, or is made out of construction materials like concrete or steel (commonly found in hurricaine prone areas).
* **Bits per second (bps)** - You are provided several columns of throughput data. This can help you understand how heavily the customer uses their network. Generally, things like online games, streaming in HD or 4K, and security cameras can take a lot of bandwidth. However, other applications take a lot of bandwidth but not for very long and may not show up in averages (but do in maximums/95th percentile). E.g., downloading very large files (iPhone updates, new games), telemedicine (MRI images, X-Rays for doctors working at home), and other applications. Here's a list of some common devices and applications and what each of them might need (Mbps is Megabits per second or Millions of bits per second):

   |Device Type|Bandwidth Needed|
   |------------|----------------|
   |Smart speaker|1-3 Mbps|
   |Smart light bulb system| 1-3 Mbps|
   |Smart Appliances|1-2 Mbps per device|
   |Wi-Fi enabled door locks| 1-2 Mbps|
   |Smart thermostat| 1-2 Mbps|
   |Smart home hub/controller| 2-3 Mbps|
   |Video doorbell security camera| 5-7 Mbps|
   |In-home security camera system| 10+ Mbps per camera|
   |Smart TV streaming 4K video| 35+ Mbps|
   |Gaming console downloading games| 100+ Mbps|
   |Video calls via smartphones/laptops| 1-5 Mbps per device|
   |Connected Vehicles (like a Tesla)|10+ Mbps|
   |Microsoft Flight Simulator 2024|50+ Mbps|
   |Downloading Call of Duty:MW3 in < 30 minutes| 1,000 Mbps|
   |Downloading Baldur's Gate 3 in < 10 minutes| 1,200 Mbps|

   > In general improving the connectivity (either using a wired connection or improving RSSI) and increasing the network speed are the only ways to ensure these applications get the bandwidth they need.
* **Network Speed** - This is the speed most commonly associated with your network. E.g., "1 gig" is 1000 Megabits per second. On fiber networks, it is the same speed in both the transmit and receive  directions (up and down to the internet).<br><br>
  > More speed doesn't fix wireless problems. But it can improve things like latency, jitter, packet loss, slow ping times, etc. that many high-end customers complain about. However, selling a customer 7G when their equipment can only do 1Gbps leads to a poor experience and frequently support calls.
* **Number of Wireless Devices** - The number of wireless devices can impact the quality of your network. Having many (generally > 25) can mean a lot of devices all trying to transmit at once and not having enough wireless spectrum available. Also, obviously, more devices tend to need more network bandwidth.<br><br>
  > In some cases, adding an extender or ensuring that you have the most capable (latest generation) WIFI router can dramatically improve this.