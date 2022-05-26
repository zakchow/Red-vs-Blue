# Red-vs-Blue
Project
As the Red Team, we will attack a vulnerable VM within your environment, ultimately gaining root access to the machine. As Blue Team, we will use Kibana to review logs taken during their Day 1 engagement. we'll use the logs to extract hard data and visualizations for their report.

Then, we will interpret your log data to suggest mitigation measures for each exploit that you've successfully performed.


### Unit Objectives

<details>
    <summary>Click here to view the daily unit objectives.</summary>
<br>

My project will prompt my knowledge of the following skills and tools:

- Penetration testing with Kali Linux.

- Log and incident analysis with Kibana.

- System hardening and configuration.

- Reporting, documentation, and communication.


</details>

### Lab Environment

<details>

<summary>Click here to view the lab environnement.</summary>

<br>

We will be using the Red vs Blue lab environment located in Windows Azure Lab Services. RDP into the Windows RDP host machine using the following credentials:

Username: `a****`
Password: `****'

Open the Hyper-V Manager to access the nested machines:

- **ELK machine credentials:** The same ELK setup that you created in my previous ELK Server Project. It holds the Kibana dashboards.
    - Username: `****`
    - Password: `***`
    - IP Address: `192.168.1.***`

- **Kali:** A standard Kali Linux machine for use in the penetration test on Day 1. 
    - Username: `***`
    - Password: `***`
    - IP Address: `192.168.1.***`

- **Capstone:** Filebeat and Metricbeat are installed and will forward logs to the ELK machine. 
   - IP Address: `192.168.1.***`
   - Please note that this VM is in the network solely for the purpose of testing alerts.
  
  ### Security+ Domains

This project covers portions of the following domains of Cybersecurity

- 1.0 Attacks, Threats, and Vulnerabilities 
- 2.0 Architecture and Design 
- 3.0 Implementation
- 4.0 Operations and Incident Response 
  following tools, in no particular order:

- Firefox
- Hydra
- Nmap
- John the Ripper
- Metasploit
- curl
- MSVenom
  
  Incident Analysis with Kibana
  Kibana to analyze logs taken during the Red Team attack. As we analyze, you will use the data to develop ideas for new alerts that can improve your monitoring.
 
Analyzing the logs is still valuable. will teach us
  
What your attack looks like from a defender's perspective.


How stealthy or detectable your tactics are.


Which kinds of alarms and alerts SOC and IR professionals can set to spot attacks like yours while they occur, rather than after.
  
following existing reports:

HTTP status codes for the top queries [Packetbeat] ECS
Top 10 HTTP requests [Packetbeat] ECS
Network Traffic Between Hosts [Packetbeat Flows] ECS
Top Hosts Creating Traffic [Packetbeat Flows] ECS
Connections over time [Packetbeat Flows] ECS
HTTP error codes [Packetbeat] ECS
Errors vs successful transactions [Packetbeat] ECS
HTTP Transactions [Packetbeat] ECS  
  
