# Analysing Wifi Network with Wireshark
## Objective 
This project mainly focuses on analysing the web traffic on a Wi-Fi network using Wireshark, to detect if there is any communication with malicious websites, dropped packets, TCP, and UDP connections. Analysis of web traffic gives us the crucial understanding of web communication, detects potential threats and anomalies in network traffic.
### Skills Learned
- Understanding of network traffic.
- How two devices communicate through the network.
- Analysis of traffic through IP addresses and protocols.
- Capturing and filtering of packets.
- Detecting potential threats in the network and troubleshooting them.
### Tools Used
- Wireshark installed on your computer.
- Web browser to generate the traffic.
### Steps
#### Step 1: Capturing
- Download and install Wireshark on Windows OS.
- Open and select the wifi interface to capture the packets.
- Go to the capture tab and select start to capture the web traffic.
- To generate more traffic, open a browser and browse some of the topics, and visit any HTTP websites.
- Now click the stop button and start analysing the captured traffic, which contains TCP, UDP, HTTP, ARP, ICMP, and other protocols.

  ![Wire3](https://github.com/user-attachments/assets/3362c2c5-c595-4cd5-8d36-d4a0b532a2eb)

### Step 2: Filtering
Now, to see only HTTP traffic, you need to filter the packets.
- Go to the filter bar at the top and type HTTP and press enter.
- Now, Wireshark will only display HTTP traffic from the entire capture.

![Wire2](https://github.com/user-attachments/assets/3789e82b-5217-4010-b765-40a35642053a)


### Step 3: Analysing HTTP Request
- In the filtered display, locate the HTTP GET Request and click on that to view the details of the GET Request. 
- In the detail pane, you can view the  URL to which the request was made, the search engine used, and whether the Request is successful.

![Wire4](https://github.com/user-attachments/assets/650610f9-1677-4387-a7e1-887c8172c88a)


### Step 4: Analysing HTTP Response
- Locate the HTTP Response for the GET Request and click on that to view the details of the response.
- In the details pane, expand ' Hypertext Transfer Protocol' to view the HTTP details.
  

  ![wire 5](https://github.com/user-attachments/assets/1578a70d-5c15-4cf6-8abf-00973252f7e8)


### Step 5: Analysing Payload data
- In the HTTP traffic, look for the HTML content that is loaded.
- Right click on that, then Follow-> TCP Stream, then press enter.
- Now you can view the entire HTTP conversation and examine the content being transferred between two users.

  ![wire6](https://github.com/user-attachments/assets/9764b2d7-1dc4-46aa-954e-cf9a4cac98a5)


### Conclusion:
In this way, you can capture the traffic to understand the web communication, perform security investigations, and improve network security to prevent any suspicious activity and take preventative measures to avert the potential risks.



