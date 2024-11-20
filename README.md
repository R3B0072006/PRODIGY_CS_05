# PRODIGY_CS_05
Network Packet Analyzer
## Description
A Network Packet Analyzer is a tool used to capture and analyze packets that flow through a network. It allows you to examine key information such as the source and destination IP addresses, the protocol used (e.g., TCP, UDP, ICMP), and the payload data carried by each packet. This tool can be used for network troubleshooting, security analysis, and learning about how networks operate.

## Ethical Considerations
1. Authorization: You must have explicit permission to capture and analyze network traffic on the network you're monitoring. Unauthorized packet sniffing is illegal and violates privacy rights.
2. Educational Use: This tool should only be used for educational purposes, within a controlled environment or authorized networks.
3. Respect Privacy: Avoid intercepting or logging sensitive data such as passwords, personal messages, or any confidential information unless it's part of a legitimate and authorized network analysis.
   
## Features
Capture all network packets sent and received on the local machine.

Display essential packet details such as:
1. Source IP address
2. Destination IP address
3. Protocol (TCP, UDP, ICMP, etc.)
4. Payload data (the content of the packet)
5. Real-time packet analysis to understand the network activity.
6. Filtering of packets based on specific criteria (e.g., by protocol type).

## How to Run
1. Install the Required Library:
To install scapy, which is used for packet sniffing and manipulation, run the following command:

pip install scapy

2. Run the Packet Sniffer:
Once the code is ready, execute the Python script in your terminal:

python network_packet_analyzer.py

3. View the Captured Packets:
The tool will display details of the captured packets in real-time, showing the source and destination IP addresses, the protocol, and the payload data.

## Example:
1. If you're using Windows, open the Command Prompt, navigate to the folder with your Python script, and type:

python network_packet_analyzer.py

2. After this, you'll start seeing something like:

-Source IP: 192.168.1.2
-Destination IP: 192.168.1.1
-Protocol: TCP
-Payload: b'GET / HTTP/1.1\r\nHost: www.example.com\r\n'
--------------------------------------------------
-Source IP: 192.168.1.1
-Destination IP: 192.168.1.2
-Protocol: UDP
-Payload: b'UDP data packet'
--------------------------------------------------


