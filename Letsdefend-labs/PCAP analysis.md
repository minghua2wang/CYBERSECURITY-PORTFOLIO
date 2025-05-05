1. Identify the sender and receiver's IP addresses of a network communication. 
Open the PCAPNG file using Wireshark. Use filter [frame contains "P13"] to see packets containing P13, as the victim computer is named P13.
Right-click a packet, select the Follow tab, and select TCP stream.
Click on any message from P13 to identify the sender and receiver's IP address.
The sender IP address is 192.168.235.137, the receiver IP address is 192.168.235.131.

2. P13 uploaded a file to the web server. Identify the IP address of the server.
Use the filter [frame contains "upload"] and identify the packet using a POST HTTP request method.
The server IP address is 192.168.1.7.

3. Identify the name of the file that was sent through the network. Right-click on the same packet where we found the server IP address, select the Follow tab, and select HTTP stream.
The file name is [file].

4. Identify the name of the server where the file was uploaded. In the same HTTP stream, scroll to the bottom, and we can find server information.
The server name is Apache.

5. Identify the directory where the file was uploaded. In the same section, we can find the location where the file was uploaded
The file was uploaded to [uploads].

6. How long did it take the sender to send the encrypted file?  Select the Statistics tab and open the Conversation. In the IPv4 tab, find the receiver and sender's IP addresses.
The duration is 0.0073.
