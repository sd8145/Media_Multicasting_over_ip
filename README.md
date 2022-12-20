# Media_Multicasting_over_ip
The purpose of this project was to explore the IP multicast and the nature of multimedia traffic. We developed an internet TV/radio. We used our experience of sending data over a TCP connection, sending multimedia over a UDP connection, and sending data in a structured manner from the previous labs. The Any Source Multicast (ASM) model was used for multicasting .

•	A single host –Unicast = (TCP and UDP)

•	All hosts -Broadcast – (UDP only)

•	A group of hosts – Multicast -(UDP only)

This project will work as mentioned below.First, Client will send a join request to the server to join the multicast group.After that Server will provide station list, site info to the client through TCP. Then whichever station it selects from the station list, it is connected to that station.All the stations are sending data, irrespective of client is connected or not. This functionality is incorporated to relate more with real life situation, e.g Tv/radio sends data even though there is no receiver connected.Whenever receiver connects to a particular station, it starts receiving live-streaming videos from that station. Receiver can pause, resume, change station or even terminate at any given time from GUI using thread.
