# Wazuh-SIEM-Lab 🖥️

A hands-on security lab using Wazuh to build an automated threat detection and response system. The environment includes a central Wazuh manager (Ubuntu server) and two agents (Ubuntu and Windows 10). File Integrity Monitoring (FIM) detects file changes, VirusTotal integration validates malicious files, and an active response script automatically removes confirmed threats.



<br>



## Features :
-  Multi-OS agent deployment (Ubuntu + Windows)
-  File Integrity Monitoring (FIM)
-  VirusTotal threat intelligence integration
-  Custom active response script for malware removal
-  MITRE ATT&CK framework mapping
-  Real-time alerts and dashboards




<br>


##  How It Works :
1. **File Created** - Agent detects new file in monitored directory
2. **Hash Sent** - Wazuh manager queries VirusTotal
3. **Alert Triggered** - Malicious file detected 
4. **Active Response** - Manager commands agent to delete file
5. **Verification** - File removed, events logged in dashboard
   
<br>

##  Screenshots :

<h3> Project Diagram:</h3><br>

 <img src=".\Diagram.png"><br>

<h3> Wazuh Dashboard: </h3> <br>

 <img src=".\WazuhDashboard.png"><br>
 <h3> VirusTotal Alerts: </h3> <br>

 <img src=".\VirusTotal.png"><br>
<h3> Threat Hunting Overview: </h3> <br>

 <img src=".\ThreatHuntingOverview.png"><br>
<br>


## Technologies Used :

  - Wazuh 4.14.3 - SIEM platform

  - Ubuntu 24.04 - Server and agent OS

  - Windows 10 - Agent OS

  - VMware Workstation - Virtualization

  - VirusTotal API - Threat intelligence

