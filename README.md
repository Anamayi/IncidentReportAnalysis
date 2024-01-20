<h1>INCIDENT REPORT ANALYSIS.</h1>

<h2>PROJECT OBJECTIVES</h2>

- <b>To build preactical knowledge of the NIST Cybersecurity Framework,</b>
- <b>To carry out incident analysis and analyse situations,</b>
- <b>To create an incident report.</b>

<h2>SCENARIO</h2>

You are a cybersecurity analyst working for a multimedia company that offers web design services, graphic design, and social media marketing solutions to small businesses. Your organization recently experienced a DDoS attack, which compromised the internal network for two hours until it was resolved.
During the attack, your organization’s network services suddenly stopped responding due to an incoming flood of ICMP packets. Normal internal network traffic could not access any network resources. The incident management team responded by blocking incoming ICMP packets, stopping all non-critical network services offline, and restoring critical network services. 
The company’s cybersecurity team then investigated the security event. They found that a malicious actor had sent a flood of ICMP pings into the company’s network through an unconfigured firewall. This vulnerability allowed the malicious attacker to overwhelm the company’s network through a distributed denial of service (DDoS) attack.
To address this security event, the network security team implemented:

- <b>A new firewall rule to limit the rate of incoming ICMP packets</b>
- <b>Source IP address verification on the firewall to check for spoofed IP addresses on incoming ICMP packets</b>
- <b>Network monitoring software to detect abnormal traffic patterns</b>
- <b>An IDS/IPS system to filter out some ICMP traffic based on suspicious characteristics</b>

As a cybersecurity analyst, you are tasked with using this security event to create a plan to improve your company’s network security, following the National Institute of Standards and Technology (NIST) Cybersecurity Framework (CSF). The framework includes the following steps: Identify, Protect, Detect, Respond and Recover.


<h2>Incident Report Analysis</h2>

<img src="https://i.imgur.com/OPdyMbn.png" height="80%" width="80%" alt="Incident Report"/>
<br />
<br />





<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
