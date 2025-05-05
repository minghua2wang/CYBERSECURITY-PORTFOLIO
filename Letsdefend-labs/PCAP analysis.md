## PCAP Analysis

Tool: Wireshark

We have captured this traffic from P13's computer. Can you help him?


File Location: /root/Desktop/ChallengeFile/Pcap_Analysis.pcapng

1. Identify the sender and receiver's IP addresses of a network communication. 
Open the PCAPNG file using Wireshark. Use filter [frame contains "P13"] to see packets containing P13, as the victim computer is named P13.
Right-click a packet, select the Follow tab, and select TCP stream.
![image](https://github.com/user-attachments/assets/41a20aeb-42d1-4c3a-9722-79330e8ce603)
Click on any message from P13 to identify the sender and receiver's IP address.
The sender IP address is 192.168.235.137, the receiver IP address is 192.168.235.131.
![image](https://github.com/user-attachments/assets/d63dd268-8781-418e-b692-46128116fcb8)

2. P13 uploaded a file to the web server. Identify the IP address of the server.
Use the filter [frame contains "upload"] and identify the packet using a POST HTTP request method.
The server IP address is 192.168.1.7.
![image](https://github.com/user-attachments/assets/8d3f2cd6-c25a-4906-b7d5-76b57c46ace2)

3. Identify the name of the file that was sent through the network. Right-click on the same packet where we found the server IP address, select the Follow tab, and select HTTP stream.
![image](https://github.com/user-attachments/assets/f1114af9-2088-4a8f-af0b-c65dc3899467)
The file name is [file].
![image](https://github.com/user-attachments/assets/23c45aa0-0358-43cf-ae8a-6ee945828eaa)

4. Identify the name of the server where the file was uploaded. In the same HTTP stream, scroll to the bottom, and we can find server information.
The server name is Apache.
![image](https://github.com/user-attachments/assets/e729c37c-5141-46cf-8563-fe9f4f11777d)

6. Identify the directory where the file was uploaded. In the same section, we can find the location where the file was uploaded
The file was uploaded to [uploads].
![image](https://github.com/user-attachments/assets/0fb0b56f-75eb-4613-a42a-e5afabb8c87f)

8. How long did it take the sender to send the encrypted file?  Select the Statistics tab and open the Conversation. In the IPv4 tab, find the receiver and sender's IP addresses.
The duration is 0.0073.
![image](https://github.com/user-attachments/assets/76fd2d88-d88f-45cd-b2a4-633abe0ca01f)
