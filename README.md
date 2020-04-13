# Dashboards

A collection of (tokenized) LogicMonitor dashboards that can be re-used across accounts. When importing, change the value of the ##defaultResourceGroup## or ##defaultResourceName## token to select the relevant group of devices (or individual device) for which you wish to visualize data. Intended to be examples to get the creativity flowing! (LogicMonitor Support can always help with adjustments)

These dashboards largely rely on both the latest versions of LogicMonitor datasources, and dynamic groups in the 'Devices by Type' device group. If these groups don't exist, they can be created using the out-of-box PropertySources from LogicMonitor together with the below documentation. [So make sure you have the latest PropertySources (and DataSources) from the repository!](https://www.logicmonitor.com/support/settings/logicmodules/keeping-your-datasources-up-to-date/)

To see a preview of what some of these dashboards look like, visit the [LogicMonitor Dashboard Gallery](https://www.logicmonitor.com/sales/dashboards/index.html).

To download all dashboards as a single file, see [LogicMonitor Dashboards](https://github.com/kdevilbiss/Dashboards/blob/master/Dashboard%20Groups/LogicMonitor%20Dashboards.json) in the [Dashboard Groups](https://github.com/kdevilbiss/Dashboards/tree/master/Dashboard%20Groups) directory.

**Default Dashboards 3.0** 

Format: Dashboard Name | Required Dynamic Group Name | Dynamic Group Definition

**Alerting**
- Alert List | * | (No specific group requirement)
- Alert Overview | * | (No specific group requirement)
- Geo_Alert_Map | * | (No specific group requirement)
- SLA_Overview | * | (No specific group requirement)

**Applications**
- Apache | Devices by Type/ Linux Servers | isLinux()
- Citrix XenApp / XenDesktop | * | (No specific group requirement)
- Docker | Devices by Type/ Linux Servers | isLinux()
- Nginx | Devices by Type/ Linux Servers | isLinux()
- Office 365 | * | (No specific group requirement)
- Zoom | * | (No specific group requirement)

**Capacity Management**
- Resource Utilization | * | (No specific group requirement)
- Under Utilized Devices - On-Prem | * | (Target the device group you wish to visualize)
- Under Utilized Devices - Public Cloud | AWS or Azure account | (Requires local collector monitoring of cloud VMs)

**Databases**
- SQL Server | Devices by Type/ SQL Servers | hasCategory("MSSQL")

**Hardware**
- APC | * | (No specific group requirement)
- Dell iDRAC | * | (No specific group requirement)
- HP iLO | * | (No specific group requirement)

**Kubernetes**
- Kubernetes Cluster Overview | * | (No specific group requirement)
- k8s Cluster | * | (No specific group requirement)
- k8s Pods | * | (No specific group requirement)

**Linux**
- Linux | Devices by Type/ Linux Servers | isLinux()
- Linux (SSH) | Devices by Type/ Linux Servers | isLinux()

**LogicMonitor**
- Collectors | Devices by Type/ Collectors | hasCategory("Collectors")
- LogicMonitor Portal Metrics | * | (Requires the LogicMonitor Portal Metrics datasource)
- Resource Utilization | * | (No specific group requirement)
- Welcome to LogicMonitor | * | (No specific group requirement)

**Microsoft**
- Active Directory | Devices by Type/ Windows Servers | isWindows()
- DHCP Servers | Devices by Type/ Windows Servers | isWindows()
- DNS Servers | Devices by Type/ Windows Servers | isWindows()
- Exchange Server | Devices by Type/ Windows Servers | isWindows()
- Failover Clustering | Devices by Type/ Windows Servers | isWindows()
- SQL Server | Devices by Type/ SQL Servers | hasCategory("MSSQL")
- IIS | Devices by Type/ Web Servers | hasCategory("MicrosoftIIS")
- Microsoft .NET Framework | Devices by Type/ Windows Servers | isWindows()
- Microsoft Message Queue | Devices by Type/ Windows Servers | isWindows()
- Remote Desktop Server | Devices by Type/ Windows Servers | isWindows()
- Windows | Devices by Type/ Windows Servers | isWindows()

**Network**
- Aruba Wireless | Devices by Type/ Aruba | hasCategory("Aruba")
- Brocade | Devices by Type/ Brocade | hasCategory("Brocade")
- Checkpoint | Devices by Type/ Checkpoint | system.sysoid == "1.3.6.1.4.1.2620.1.6.123.1.49"
- Cisco ASA | Devices by Type/ Cisco ASA | hasCategory("CiscoASA")
- Cisco Wireless | Devices by Type/ Network | (No specific group requirement)
- F5 BIG-IP | Devices by Type/ F5 | hasCategory("F5")
- Fortinet Fortigate | Devices by Type/ Fortinet | hasCategory("Fortigate")
- Local Network Latency | Devices by Type/* | (No specific group requirement)
- Meraki | Devices by Type/ Meraki | hasCategory("MerakiCloudController")
- Network Performance | Devices by Type/ Network | isNetwork()
- Palo Alto | Devices by Type/ Palo Alto | hasCategory("PaloAlto")
- SonicWall | Devices by Type/ SonicWall | hasCategory("SonicWallFW")
- Ubiquiti Unifi | Devices by Type/ Network | isNetwork()

**Storage**
- EMC VNX | Devices by Type/ EMC | hasCategory("EMC") || hasCategory("EMC_VNX") || hasCategory("EMC_VNX2")
- HP 3PAR | * | (No specific group requirement)
- NetApp | * | (No specific group requirement)
- Nimble Storage | Devices by Type/ Nimble | hasCategory("Nimble")
- Pure Storage | Devices by Type/ Pure Storage | purestorage.apitoken.pass

**Virtualization**
- Cisco Hyperflex | * | (No specific group requirement)
- Hyper-V | Devices by Type/ Hyper-V | hasCategory("HyperV")
- Nutanix | * | (No specific group requirement)
- vSphere_ESXi_Overview | Devices by Type/ VMware Hosts | system.virtualization =~ "VMware ESXi Host"
- vSphere_vCenter_Overview | Devices by Type/ VMware vCenters | system.virtualization =~ "VMware ESXi vCenter"
