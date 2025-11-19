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

### Screenshot Demos <br>

*Wazuh Dashboard*
<br>
<img width="960" height="540" alt="{9054D565-B487-4CFF-AED6-51F216548A28}" src="https://github.com/user-attachments/assets/ca17fe62-c488-4b10-b99c-42e3556084b1" />
<br> <br>

*Connected Agents* <br>
<img width="960" height="540" alt="{8ECFADAF-3583-4138-A63B-03AE24080A9F}" src="https://github.com/user-attachments/assets/50087da2-f30b-4b02-9903-62b70b6be61e" /> 
<br> <br>

*Kali agent - detailed view*
<img width="960" height="540" alt="{A6D31BB2-ABDF-4263-8ACF-0F4E2FE59DA4}" src="https://github.com/user-attachments/assets/d96aa6cf-ecf8-4402-9f97-42d5088de7af" />
<br> <br>

*Windows 11 Home - detailed view*
<img width="960" height="540" alt="{0D2C2352-DA1A-40FE-82EC-09BDDF24DB3A}" src="https://github.com/user-attachments/assets/4b66e220-3e76-47b8-90d5-58e7a7b2651c" />
<br> <br>

*Windows Server 2022 - detailed view*
<img width="960" height="540" alt="{06517A22-842E-41EB-BDA6-C91A3F00A4D3}" src="https://github.com/user-attachments/assets/7a33b97e-3eda-4427-8ab9-bc1eab5000d9" />


*SIEM Event ingestion/Log collection/Basic Security Monitoring - Sample*
<br> <br>
<img width="960" height="540" alt="{56AD8FE6-D8A1-48D2-8288-A13DCAB5DE8C}" src="https://github.com/user-attachments/assets/cf325049-6e78-4717-8164-810eb00177d5" />






