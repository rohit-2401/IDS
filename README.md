Suricata Intrusion Detection Scenarios
1. Detecting URL Access Containing "oracle"
We created a Suricata rule designed to alert whenever a browser attempts to access a URL containing the keyword "oracle". This scenario is especially useful in monitoring unauthorized access to sensitive corporate resources. When the rule was triggered, the corresponding log entry highlighted an HTTPS request to a domain containing the keyword, classifying it as a potential corporate privacy violation.

2. Detection of Ping Requests
The second rule implemented was to detect ICMP echo requests, commonly known as pings. This rule helps in identifying potential network scanning or reconnaissance activities. The logs show multiple instances where a host was pinged, demonstrating the rule's effectiveness in real-time monitoring of network health or unauthorized ping sweeps.

3. Monitoring Telnet Traffic
Our third rule targets the detection of Telnet traffic, a protocol often associated with insecure communications. This rule was triggered multiple times, indicating persistent Telnet attempts within the network, which could point to security policy violations or vulnerable services that need attention.

4. Detection of Specific Content in Network Traffic
Finally, we established a rule to detect specific content from a text file named lassie.txt being transmitted over the network. This type of monitoring is crucial for protecting against data leakage. The alerts generated confirmed the transmission of specified content, showcasing how well Suricata can be used to monitor for specific data patterns in network traffic.

These scenarios collectively illustrate the versatility and effectiveness of Suricata as a network intrusion detection system. Each setup highlights different aspects of network security monitoring, making Suricata a valuable tool for IT security professionals
