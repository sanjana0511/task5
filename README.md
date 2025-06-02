# task5
**📝 Steps Performed**
Started Wireshark and selected the active network interface (e.g., Wi-Fi).
Began live packet capture.
Generated network traffic by:
Opening websites like google.com
Running the ping command
Stopped the capture after approximately 1 minute.
Filtered and analyzed the traffic using protocol filters like:   
  http
  dns
  tcp
Saved the captured file as network_capture.pcap.

**🔎** **Protocols Identified**
**HTTP (HyperText Transfer Protocol):**
Used for web traffic.
Common on ports like 80.
Easily visible in Wireshark.

**DNS (Domain Name System):**
Resolves domain names into IP addresses.
Uses port 53.
Query/response packets easily filtered with dns.

**TCP (Transmission Control Protocol):**
Reliable transport layer protocol.
Shows 3-way handshakes (SYN, ACK, FIN) in Wireshark.
Used by HTTP, HTTPS, FTP, etc.
