# Dashboards

LogicMonitor dashboards, provisioned with all new LogicMonitor accounts. When importing to an existing account, change the value of the ##defaultResourceGroup## or ##defaultResourceName## token to select the relevant group of devices (or individual device) for which you wish to visualize data. Intended to be examples to get the creativity flowing! (LogicMonitor Support can always help with adjustments)

These dashboards depend on the presence of the latest versions of LogicMonitor datasources, and dynamic groups in the 'Devices by Type' device group. If these groups don't exist, they can be created using the out-of-box PropertySources from LogicMonitor together with the below documentation. [So make sure you have the latest PropertySources (and DataSources) from the repository!](https://www.logicmonitor.com/support/settings/logicmodules/keeping-your-datasources-up-to-date/)

To see a preview of what some of these dashboards look like, visit the [LogicMonitor Dashboard Gallery](https://www.logicmonitor.com/dashboards/).

To download all dashboards as a single file, see the [LogicMonitor Dashboard Packages](https://github.com/logicmonitor/dashboards/tree/master/Packages) resource.

**LogicMonitor Default Dashboards** 

Format: Dashboard Name | Required Dynamic Group Name | Dynamic Group Definition

**Alerting**
- Alert List | * | (No specific group requirement)
- Alert Map | * | (No specific group requirement)
- Alert Map - Dynamic Weather | * | (No specific group requirement)
- Alert Overview | * | (No specific group requirement)
- SLA_Overview | * | (No specific group requirement)

**Applications**
- Apache | Devices by Type/ Linux Servers | isLinux()
- Citrix XenApp / XenDesktop | * | (No specific group requirement)
- Docker | Devices by Type/ Linux Servers | isLinux()
- Nginx | Devices by Type/ Linux Servers | isLinux()
- Tomcat Server | * | (No specific group requirement)
- Veeam Backup & Replication | * | (No specific group requirement)

**Capacity Management**
- Resource Utilization | * | (No specific group requirement)

**Databases**
- MySQL | * | (No specific group requirement)
- Oracle | * | (No specific group requirement)
- SQL Server | Devices by Type/ SQL Servers | hasCategory("MSSQL")

**Environmental**
- APC | * | (No specific group requirement)

**Hardware**
- Cisco UCS | * | (No specific group requirement)
- Dell iDRAC | * | (No specific group requirement)
- HP iLO | * | (No specific group requirement)

**Kubernetes**
- Kubernetes Cluster Overview | * | (No specific group requirement)
- Kubernetes Containers | * | (No specific group requirement)
- Kubernetes Deployments | * | (No specific group requirement)
- Kubernetes Inventory | * | (No specific group requirement)
- Kubernetes Nodes | * | (No specific group requirement)
- Kubernetes Pods | * | (No specific group requirement)
- Kubernetes Services | * | (No specific group requirement)

**Linux**
- Linux | Devices by Type/ Linux Servers | isLinux()
- Linux - Monitored Processes | Devices by Type/ Linux Servers | isLinux()
- Linux - SSH | Devices by Type/ Linux Servers | isLinux()

**LogicMonitor**
- Collectors | Devices by Type/ Collectors | hasCategory("Collectors")
- LogicMonitor Portal Metrics | * | (Requires the LogicMonitor Portal Metrics datasource)
- Minimal Monitoring | \*Minimal Monitoring\* | *
- Welcome to LogicMonitor | * | (No specific group requirement)

**Microsoft**
- Active Directory | Devices by Type/ Windows Servers | isWindows()
- DHCP Servers | Devices by Type/ Windows Servers | isWindows()
- DNS Servers | Devices by Type/ Windows Servers | isWindows()
- Exchange Servers | Devices by Type/ Windows Servers | isWindows()
- Failover Clustering | Devices by Type/ Windows Servers | isWindows()
- File Servers | Devices by Type/ Windows Servers | isWindows()
- IIS | Devices by Type/ Windows Servers | isWindows()
- Microsoft .NET Framework | Devices by Type/ Windows Servers | isWindows()
- Microsoft Message Queue | Devices by Type/ Windows Servers | isWindows()
- Windows Servers| Devices by Type/ Windows Servers | isWindows()

**Network**

- Arista | * | (No specific group requirement)
- Aruba Wireless | * | (No specific group requirement)
- BGP | * | (No specific group requirement)
- Cisco APIC | * | (No specific group requirement)
- Cisco ASA | * | (No specific group requirement)
- Cisco DNA Center | * | (No specific group requirement)
- Cisco Meraki | * | (No specific group requirement)
- Cisco Viptela | * | (No specific group requirement)
- Cisco Wireless | * | (No specific group requirement)
- EIGRP | * | (No specific group requirement)
- F5 BIG-IP | * | (No specific group requirement)
- Fortinet Fortigate | * | (No specific group requirement)
- Infoblox | * | (No specific group requirement)
- Local Network Latency | Devices by Type/* | (No specific group requirement)
- Network Performance | Devices by Type/ Network | isNetwork()
- OSPF | * | (No specific group requirement)
- Palo Alto Networks | Devices by Type/ Palo Alto | hasCategory("PaloAlto")
- Palo Alto Networks - BGP | Devices by Type/ Palo Alto | hasCategory("PaloAlto")
- Pulse Secure | * | (No specific group requirement)
- SSL Certificates | * | (No specific group requirement)
- Ubiquiti Unifi | Devices by Type/ Network | isNetwork()

**SaaS**
- Office 365 | * | (No specific group requirement)
- SaaS Lite Overview | * | (No specific group requirement)
- Slack | * | (No specific group requirement)
- Zoom | * | (No specific group requirement)

**Storage**
- Dell EMC Isilon | * | (No specific group requirement)
- HP 3PAR | * | (No specific group requirement)
- NetApp 7-mode | * | (No specific group requirement)
- NetApp Cluster Mode | * | (No specific group requirement)
- Nimble | * | (No specific group requirement)
- Pure Storage | * | (No specific group requirement)

**Virtualization**
- Cisco Hyperflex | * | (No specific group requirement)
- Hyper-V | Devices by Type/ Hyper-V | hasCategory("HyperV")
- Nutanix | * | (No specific group requirement)
- vCenter Server Appliance | * | (No specific group requirement)
- vSphere ESXi Overview | Devices by Type/ VMware Hosts | system.virtualization =~ "VMware ESXi Host"
- vSphere vCenter Overview | Devices by Type/ VMware vCenters | system.virtualization =~ "VMware ESXi vCenter"

**Voice**
- Cisco Unified Border Element | * | (No specific group requirement)
- Cisco Unified Communications | * | (No specific group requirement)
