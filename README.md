# Wireshark Network Traffic Capture and Analysis

This project demonstrates basic network traffic capture using *Wireshark* and provides analysis of various network protocols observed during a live capture session.


## Steps Performed

1. *Installed Wireshark* on the local machine.
2. *Started a packet capture* on the active network interface (e.g., Wi-Fi).
3. *Generated traffic* by:
   - Visiting websites in a browser.
   - Running ping google.com in terminal.
4. *Stopped the capture* after ~1 minute of activity.
5. *Filtered captured packets* using protocol filters like:
   - usp
   - dns
   - arp
6. *Identified at least 3 different protocols*:
   - *UDP* – for live data feed.
   - *DNS* – resolving domain names.
   - *ARP* – for resolution of dynamic ip addres.
7. *Exported the capture* as a .pcap file using:
   - Save → Wireshark/tcpdump/... - pcap (*.pcap)

## Protocol Analysis Summary

UDP ->	Connectionless transport protocol	Used to carry DNS queries and responses.
DNS ->	Resolves domain names to IPs	Query/response for websites like google.com.
ARP ->	Maps IP addresses to MAC addresses	Seen as request/reply on local network.


*Added screenshots and pcap file as proof*
