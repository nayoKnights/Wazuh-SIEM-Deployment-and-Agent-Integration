# Wazuh-SIEM-Deployment-and-Agent-Integration
A complete VM-based Wazuh SIEM setup with Windows/Linux agents.
## Objective

This project aims to build a functional SIEM environment in a local virtual SOC lab by installing and configuring the Wazuh indexer, server, and dashboard on a Linux server, and connecting endpoint agents to demonstrate effective log collection, threat detection, and security monitoring.

### Pre-requisites
- Linux server (Ubuntu preferrably)
- Windows/Linux VMs as endpoint agents
- A virtual machine
- Minimum of 8GB ram and 50GB of storage

### Skills Learned

- Deploying and configuring Wazuh Indexer, Server, and Dashboard
- Installing and connecting Wazuh endpoint agents on Windows and Linux Systems.
- Understanding SIEM event ingestion and log analysis workflows
- Basic security monitoring and alert interpretation within Wazuh
- Managing Linux-based servers (Ubuntu Server)

### Tools Used

- Wazuh Indexer
- Wazuh Server
- Wazuh Dashboard
- Ubuntu Server 24.04.3 LTS (for Wazuh stack)
- Windows Server 2022 (Endpoint agent)
- Kali Linux (Endpoint agent)
- Windows 11 home (Endpoint agent)
- VMWare Workstation 17 Pro
- Web browser for accessing the Wazuh Dashboard

## Steps

- The Wazuh docs was used as installation guide for both wazuh deployment and agent integration. <br> 
Refer: <a href="https://documentation.wazuh.com/current/installation-guide/index.html"> Wazuh installation guide </a>
- Tip: For a hassle free process, the assisted installation is prefered over the step-by-step installation.
- After completion, the following commands were run to ensure successful deployment of Wazuh. <br>
  See commands and expected output below:


*sudo systemctl status wazuh-indexer* <br>
<img width="940" height="391" alt="image" src="https://github.com/user-attachments/assets/d05ea4ac-41d7-4ba5-8e6f-e25fc89e1a63" />
<br>

*sudo systemctl status wazuh-manager* <br>
<img width="940" height="551" alt="image" src="https://github.com/user-attachments/assets/304b8eb2-f118-4492-871c-866e8a270e3f" />
<br>

*sudo systemctl status wazuh-dashboard* <br>
<img width="940" height="395" alt="image" src="https://github.com/user-attachments/assets/c2a1023b-dac0-424c-8b87-f11f0872137a" />
<br> <br>

*Wazuh Dashboard* <br>
<img width="960" height="540" alt="{9054D565-B487-4CFF-AED6-51F216548A28}" src="https://github.com/user-attachments/assets/ca17fe62-c488-4b10-b99c-42e3556084b1" />

