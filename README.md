# CyberSecurity_thread_Analysis
This project aims to analyse a cybersecurity dataset to understand better the types of attacks, the frequency of occurrences, targets, and the effectiveness of preventative measures. The analysis will help detect cyber-attack patterns, assess their damage, and evaluate how well different cybersecurity protocols have mitigated these threats.
## Objective 
### 1. Distribution of Attack Types:
- Objective:- Categorize and analyze the distribution of various attacks (e.g. DDoS, phishing, malware) to understand which are most reventable.
- Approach:- Group the attack types from the dataset and visualize the distribution to identify the most common types.
  
### 2. Attack Frequency (Time Series Analysis):
- Objective:- Perform a time series analysis on the occurence of attacks to reveal trends, spikes, and periods with higher attack frequency.
- Approach:- Use the timestamp data to create a time series and observe the frequency and trends of attacks over time, identifying peak periods.

### 3. Target Analysis (Region and Organization):
- Objective:- Analyze the geo-location and user information to determine which regions, organizations, or industries are the most trageted.
- Approach:- Use geographic and organisational information to break down attacks by location and industry, helping to identify hight-risk areas.

### 4. Damage Assess:
- Objective:- Assess the finacial or operational damage caused by attacks, if avilable in the dataset (via anomaly scores, finacial indicators, or other damage matrics).
- Approach:- Compare the damage across different attack types and regions to quantify the impact of each type of cyber attack.

### 5. Preventive Measures (Effectiveness of Protocols):
- Objective:- Evaluate the effectiveness of different cybersecurity measures by examining responses such as blocking or logging attacks.
- Approach:- Analyze the action taken (e.g., blocked, logged) and protocol performance metrics to measure how well different security systems handled the attacks.

## DataSet Description:
The dataset contains 40,000 entries with 25 columns, many capturing various technical details related to cyber-attacks.

1. Timestamp : The date and time when the attack occured.
2. Source IP Address : The IP Address of the originator of the attack.
3. Destination IP Adress : The IP Aderss of the target system.
4. Source Port : The port number used by the scorce system.
5. Destination Port : The port number targeted on the destination system.
6. Protocol : The communication portocol used (e.g., TCP, UDP, ICMP).
7. Packet Lenght : Size of the packet in bytes.
8. Packet Type : Type of the packet (e.g., Data, Control).
9. Traffic Type : Type of traffic (e.g., HTTP, DNS).
10. Payload Date : Cotents of the packets in bytes.
11. Malware Indicators : Indicators of potentical malware in the packet.
12. Anomaly Scores : A score indicating how unsual the network activety is.
13. Alerts/Warning : Alerts or warnings triggered by the attack.
14. Attack Type : The type of attack (e.g., DDoS, Malware).
15. Attacks Signature : A unique identifler for the attack pattern.
16. Action Taken : Action taken by the system (e.g., Bocked, Logged).
17. Severity Level : Severity of the attack (e.g., Low, Medium, High).
18. User Information : User associated with the attack or the target.
19. Device Information : Details about the device involved.
20. Network Segment : The network segment where the attack occurred.
21. Geo-location Date : Location of the source IP (city and region)
22. Proxy Information : Details of the proxy used in the attack.
23. Firewall Logs : Logs related to firewall activity during the attack.
24. IDP/IPS : Alerts generated by the Intrusion Detection/Prevention System.
25. Log Source : The system that logged the events (e.g., Sever, Firewall).

This dataset contains information that can be used for a detailed analysis of the cybersecurity threats, attack patterns, and the effectiveness of responses.











