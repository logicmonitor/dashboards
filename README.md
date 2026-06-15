# Dashboards

This catalog lists dashboards available in this public repository; product provisioning availability may vary by environment and deployment status.

LogicMonitor dashboards for download and import into LogicMonitor portals. These dashboards are examples and starting points; LogicMonitor Support can help with adjustments for specific environments.

When importing dashboards into an existing account, review any `##defaultResourceGroup##` usage and set the dashboard token to the group of resources you want to visualize. Some dashboards use inherited or folder-level scoping when provisioned by LogicMonitor, but a manually imported dashboard may need an explicit token value.

These dashboards depend on current LogicModules and, for some dashboards, dynamic groups such as `Devices by Type/...`. Keep LogicModules up to date before importing dashboards. See [Keeping your LogicModules up to date](https://www.logicmonitor.com/support/settings/logicmodules/keeping-your-datasources-up-to-date/).

To preview dashboards, visit the [LogicMonitor Dashboard Gallery](https://www.logicmonitor.com/dashboards/).

To download grouped dashboard exports, see [Packages](Packages/). Package exports are provided for convenience and may lag individual dashboard files.

## Categories

- [AWS](#aws)
- [Azure](#azure)
- [GCP](#gcp)
- [OCI](#oci)
- [Cloud](#cloud)
- [Alerting](#alerting)
- [Applications](#applications)
- [Capacity Management](#capacity-management)
- [Databases](#databases)
- [Environmental](#environmental)
- [Hardware](#hardware)
- [Kubernetes](#kubernetes)
- [Linux](#linux)
- [LogicMonitor](#logicmonitor)
- [Logs](#logs)
- [Microsoft](#microsoft)
- [Network](#network)
- [SaaS](#saas)
- [Storage](#storage)
- [Virtualization](#virtualization)
- [Voice](#voice)
- [Websites](#websites)

## Dashboard Catalog

This draft lists `216` current dashboard JSON files. It excludes `Archive/` and `Packages/`.

Format: Dashboard | JSON File | Scope | Notes

Scope value legend: `*` means no specific group requirement; `Cloud-inherited` means cloud/provider provisioning supplies the scope at the dashboard group or folder level; `Inherited` means the dashboard references `##defaultResourceGroup##` but does not declare a local token value; `None` means no `defaultResourceGroup` usage was found in the dashboard JSON.

### AWS

| Dashboard | JSON File | Scope | Notes |
| --- | --- | --- | --- |
| AWS Account Overview | [`AWS/AWS_Account_Overview.json`](AWS/AWS_Account_Overview.json) | Cloud-inherited |  |
| AWS API Gateway | [`AWS/AWS_API_Gateway.json`](AWS/AWS_API_Gateway.json) | Cloud-inherited |  |
| AWS Application ELB | [`AWS/AWS_Application_ELB.json`](AWS/AWS_Application_ELB.json) | Cloud-inherited |  |
| AWS Aurora RDS | [`AWS/AWS_Aurora_RDS.json`](AWS/AWS_Aurora_RDS.json) | Cloud-inherited |  |
| AWS Auto Scaling | [`AWS/AWS_Auto_Scaling.json`](AWS/AWS_Auto_Scaling.json) | Cloud-inherited |  |
| AWS Billing | [`AWS/AWS_Billing.json`](AWS/AWS_Billing.json) | Cloud-inherited |  |
| AWS Cloudfront | [`AWS/AWS_Cloudfront.json`](AWS/AWS_Cloudfront.json) | Cloud-inherited |  |
| AWS DynamoDB | [`AWS/AWS_DynamoDB.json`](AWS/AWS_DynamoDB.json) | Cloud-inherited |  |
| AWS EBS | [`AWS/AWS_EBS.json`](AWS/AWS_EBS.json) | Cloud-inherited |  |
| AWS EC2 | [`AWS/AWS_EC2.json`](AWS/AWS_EC2.json) | Cloud-inherited |  |
| AWS EFS | [`AWS/AWS_EFS.json`](AWS/AWS_EFS.json) | Cloud-inherited |  |
| AWS ELB | [`AWS/AWS_ELB.json`](AWS/AWS_ELB.json) | Cloud-inherited |  |
| AWS EventBridge | [`AWS/AWS_EventBridge.json`](AWS/AWS_EventBridge.json) | Cloud-inherited |  |
| AWS Inventory | [`AWS/AWS_Inventory.json`](AWS/AWS_Inventory.json) | Cloud-inherited |  |
| AWS Lambda | [`AWS/AWS_Lambda.json`](AWS/AWS_Lambda.json) | Cloud-inherited |  |
| AWS NAT Gateway | [`AWS/AWS_NAT_Gateway.json`](AWS/AWS_NAT_Gateway.json) | Cloud-inherited |  |
| AWS Network ELB | [`AWS/AWS_Network_ELB.json`](AWS/AWS_Network_ELB.json) | Cloud-inherited |  |
| AWS OpenSearch | [`AWS/AWS_OpenSearch.json`](AWS/AWS_OpenSearch.json) | Cloud-inherited |  |
| AWS RDS | [`AWS/AWS_RDS.json`](AWS/AWS_RDS.json) | Cloud-inherited |  |
| AWS Redshift | [`AWS/AWS_RedShift.json`](AWS/AWS_RedShift.json) | Cloud-inherited |  |
| AWS Route 53 | [`AWS/AWS_Route_53.json`](AWS/AWS_Route_53.json) | Cloud-inherited |  |
| AWS S3 | [`AWS/AWS_S3.json`](AWS/AWS_S3.json) | Cloud-inherited |  |
| AWS Service Limits | [`AWS/AWS_Service_Limits.json`](AWS/AWS_Service_Limits.json) | Cloud-inherited |  |
| AWS SNS | [`AWS/AWS_SNS.json`](AWS/AWS_SNS.json) | Cloud-inherited |  |
| AWS SQS | [`AWS/AWS_SQS.json`](AWS/AWS_SQS.json) | Cloud-inherited |  |
| AWS Transit Gateway | [`AWS/AWS_Transit_Gateway.json`](AWS/AWS_Transit_Gateway.json) | Cloud-inherited |  |
| AWS VPN Tunnels | [`AWS/AWS_VPN_Tunnels.json`](AWS/AWS_VPN_Tunnels.json) | Cloud-inherited |  |
| AWS Workspaces | [`AWS/AWS_Workspaces.json`](AWS/AWS_Workspaces.json) | Cloud-inherited |  |


### Azure

| Dashboard | JSON File | Scope | Notes |
| --- | --- | --- | --- |
| Azure App Services | [`Azure/Azure_App_Services.json`](Azure/Azure_App_Services.json) | Cloud-inherited |  |
| Azure Application Gateways | [`Azure/Azure_Application_Gateways.json`](Azure/Azure_Application_Gateways.json) | Cloud-inherited |  |
| Azure Application Insights | [`Azure/Azure_Application_Insights.json`](Azure/Azure_Application_Insights.json) | Cloud-inherited |  |
| Azure Automation Account | [`Azure/Azure_Automation_Account.json`](Azure/Azure_Automation_Account.json) | Cloud-inherited |  |
| Azure Billing: Cost Management | [`Azure/Azure_Billing__Cost_Management.json`](Azure/Azure_Billing__Cost_Management.json) | Cloud-inherited |  |
| Azure Blob Storage | [`Azure/Azure_Blob_Storage.json`](Azure/Azure_Blob_Storage.json) | Cloud-inherited |  |
| Azure Cosmos DB | [`Azure/Azure_Cosmos_DB.json`](Azure/Azure_Cosmos_DB.json) | Cloud-inherited |  |
| Azure Event Hub | [`Azure/Azure_Event_Hub.json`](Azure/Azure_Event_Hub.json) | Cloud-inherited |  |
| Azure Express Route Circuits | [`Azure/Azure_Express_Route_Circuits.json`](Azure/Azure_Express_Route_Circuits.json) | Cloud-inherited |  |
| Azure File Storage | [`Azure/Azure_File_Storage.json`](Azure/Azure_File_Storage.json) | Cloud-inherited |  |
| Azure Firewall | [`Azure/Azure_Firewall.json`](Azure/Azure_Firewall.json) | Cloud-inherited |  |
| Azure Functions | [`Azure/Azure_Functions.json`](Azure/Azure_Functions.json) | Cloud-inherited |  |
| Azure Inventory | [`Azure/Azure_Inventory.json`](Azure/Azure_Inventory.json) | Cloud-inherited |  |
| Azure Key Vault | [`Azure/Azure_Key_Vault.json`](Azure/Azure_Key_Vault.json) | Cloud-inherited |  |
| Azure Load Balancers | [`Azure/Azure_Load_Balancers.json`](Azure/Azure_Load_Balancers.json) | Cloud-inherited |  |
| Azure Logic Apps | [`Azure/Azure_Logic_Apps.json`](Azure/Azure_Logic_Apps.json) | Cloud-inherited |  |
| Azure MariaDB | [`Azure/Azure_MariaDB.json`](Azure/Azure_MariaDB.json) | Cloud-inherited |  |
| Azure Network Interfaces | [`Azure/Azure_Network_Interfaces.json`](Azure/Azure_Network_Interfaces.json) | Cloud-inherited |  |
| Azure PostgreSQL | [`Azure/Azure_PostgreSQL.json`](Azure/Azure_PostgreSQL.json) | Cloud-inherited |  |
| Azure Public IP Addresses | [`Azure/Azure_Public_IP_Addresses.json`](Azure/Azure_Public_IP_Addresses.json) | Cloud-inherited |  |
| Azure Queue Storage | [`Azure/Azure_Queue_Storage.json`](Azure/Azure_Queue_Storage.json) | Cloud-inherited |  |
| Azure Recovery Services | [`Azure/Azure_Recovery_Services.json`](Azure/Azure_Recovery_Services.json) | Cloud-inherited |  |
| Azure Redis Cache | [`Azure/Azure_Redis_Cache.json`](Azure/Azure_Redis_Cache.json) | Cloud-inherited |  |
| Azure Service Bus | [`Azure/Azure_Service_Bus.json`](Azure/Azure_Service_Bus.json) | Cloud-inherited |  |
| Azure Service Limits | [`Azure/Azure_Service_Limits.json`](Azure/Azure_Service_Limits.json) | Cloud-inherited |  |
| Azure SQL Databases (DTU) | [`Azure/Azure_SQL_Databases_(DTU).json`](Azure/Azure_SQL_Databases_(DTU).json) | Cloud-inherited |  |
| Azure SQL Databases (Non-DTU) | [`Azure/Azure_SQL_Databases_(Non-DTU).json`](Azure/Azure_SQL_Databases_(Non-DTU).json) | Cloud-inherited |  |
| Azure SQL Managed Instances | [`Azure/Azure_SQL_Managed_Instances.json`](Azure/Azure_SQL_Managed_Instances.json) | Cloud-inherited |  |
| Azure Storage Account | [`Azure/Azure_Storage_Account.json`](Azure/Azure_Storage_Account.json) | Cloud-inherited |  |
| Azure Subscription Overview | [`Azure/Azure_Subscription_Overview.json`](Azure/Azure_Subscription_Overview.json) | Cloud-inherited |  |
| Azure Table Storage | [`Azure/Azure_Table_Storage.json`](Azure/Azure_Table_Storage.json) | Cloud-inherited |  |
| Azure Traffic Manager | [`Azure/Azure_Traffic_Manager.json`](Azure/Azure_Traffic_Manager.json) | Cloud-inherited |  |
| Azure Virtual Desktop | [`Azure/Azure_Virtual_Desktop.json`](Azure/Azure_Virtual_Desktop.json) | Cloud-inherited |  |
| Azure Virtual Machine Scale Sets | [`Azure/Azure_Virtual_Machine_Scale_Sets.json`](Azure/Azure_Virtual_Machine_Scale_Sets.json) | Cloud-inherited |  |
| Azure Virtual Machines | [`Azure/Azure_Virtual_Machines.json`](Azure/Azure_Virtual_Machines.json) | Cloud-inherited |  |
| Azure Virtual Machines Backup | [`Azure/Azure_Virtual_Machines_Backup.json`](Azure/Azure_Virtual_Machines_Backup.json) | Cloud-inherited |  |
| Azure Virtual Network Gateways | [`Azure/Azure_Virtual_Network_Gateways.json`](Azure/Azure_Virtual_Network_Gateways.json) | Cloud-inherited |  |


### GCP

| Dashboard | JSON File | Scope | Notes |
| --- | --- | --- | --- |
| GCP App Engine | [`GCP/GCP_AppEngine.json`](GCP/GCP_AppEngine.json) | Cloud-inherited |  |
| GCP Billing | [`GCP/GCP_Billing.json`](GCP/GCP_Billing.json) | Cloud-inherited |  |
| GCP Cloud Functions | [`GCP/GCP_Cloud_Functions.json`](GCP/GCP_Cloud_Functions.json) | Cloud-inherited |  |
| GCP Cloud SQL | [`GCP/GCP_Cloud_SQL.json`](GCP/GCP_Cloud_SQL.json) | Cloud-inherited |  |
| GCP Cloud Storage | [`GCP/GCP_Cloud_Storage.json`](GCP/GCP_Cloud_Storage.json) | Cloud-inherited |  |
| GCP Compute Engine | [`GCP/GCP_Compute_Engine.json`](GCP/GCP_Compute_Engine.json) | Cloud-inherited |  |
| GCP Project Overview | [`GCP/GCP_Project_Overview.json`](GCP/GCP_Project_Overview.json) | Cloud-inherited |  |
| GCP VPN Tunnels | [`GCP/GCP_VPN_Tunnels.json`](GCP/GCP_VPN_Tunnels.json) | Cloud-inherited |  |


### OCI

| Dashboard | JSON File | Scope | Notes |
| --- | --- | --- | --- |
| OCI Autonomous Database | [`OCI/OCI_Autonomous_Database.json`](OCI/OCI_Autonomous_Database.json) | Cloud-inherited |  |
| OCI Block Storage | [`OCI/OCI_Block_Storage.json`](OCI/OCI_Block_Storage.json) | Cloud-inherited |  |
| OCI Compute | [`OCI/OCI_Compute.json`](OCI/OCI_Compute.json) | Cloud-inherited |  |
| OCI Object Storage | [`OCI/OCI_Object_Storage.json`](OCI/OCI_Object_Storage.json) | Cloud-inherited |  |


### Cloud

| Dashboard | JSON File | Scope | Notes |
| --- | --- | --- | --- |
| AWS Overview | [`Cloud/AWS_Overview.json`](Cloud/AWS_Overview.json) | None |  |
| Azure Overview | [`Cloud/Azure_Overview.json`](Cloud/Azure_Overview.json) | None |  |
| Cloud Cost Optimization | [`Cloud/Cloud_Cost_Optimization.json`](Cloud/Cloud_Cost_Optimization.json) | `*` | No specific group requirement |
| GCP Overview | [`Cloud/GCP_Overview.json`](Cloud/GCP_Overview.json) | None |  |


### Alerting

| Dashboard | JSON File | Scope | Notes |
| --- | --- | --- | --- |
| Alert List | [`Alerting/Alert_List.json`](Alerting/Alert_List.json) | `*` | No specific group requirement |
| Alert Map | [`Alerting/Alert_Map.json`](Alerting/Alert_Map.json) | `*` | No specific group requirement |
| Alert Map - Dynamic Weather | [`Alerting/Alert_Map_-_Dynamic_Weather.json`](Alerting/Alert_Map_-_Dynamic_Weather.json) | None |  |
| Alert Overview | [`Alerting/Alert_Overview.json`](Alerting/Alert_Overview.json) | `Devices by Type/*` | Any Devices by Type subgroup |
| SLA Overview | [`Alerting/SLA_Overview.json`](Alerting/SLA_Overview.json) | `*` | No specific group requirement |


### Applications

| Dashboard | JSON File | Scope | Notes |
| --- | --- | --- | --- |
| Apache | [`Applications/Apache.json`](Applications/Apache.json) | `Devices by Type/Linux Servers` | `isLinux()` |
| Citrix Virtual Apps and Desktops | [`Applications/Citrix_Virtual_Apps_and_Desktops.json`](Applications/Citrix_Virtual_Apps_and_Desktops.json) | `*` | No specific group requirement |
| Docker | [`Applications/Docker.json`](Applications/Docker.json) | `*` | No specific group requirement |
| Nginx | [`Applications/Nginx.json`](Applications/Nginx.json) | `Devices by Type/Linux Servers` | `isLinux()` |
| Nginx Ingress Controller | [`Applications/Nginx_Ingress_Controller.json`](Applications/Nginx_Ingress_Controller.json) | Inherited |  |
| Tomcat Server | [`Applications/Tomcat_Server.json`](Applications/Tomcat_Server.json) | `*` | No specific group requirement |
| Veeam Backup & Replication | [`Applications/Veeam_Backup_&_Replication.json`](Applications/Veeam_Backup_&_Replication.json) | `*` | No specific group requirement |


### Capacity Management

| Dashboard | JSON File | Scope | Notes |
| --- | --- | --- | --- |
| Resource Utilization | [`Capacity Management/Resource_Utilization.json`](Capacity%20Management/Resource_Utilization.json) | `Devices by Type/*` | Any Devices by Type subgroup |


### Databases

| Dashboard | JSON File | Scope | Notes |
| --- | --- | --- | --- |
| MongoDB | [`Databases/MongoDB.json`](Databases/MongoDB.json) | `*` | No specific group requirement |
| Oracle | [`Databases/Oracle.json`](Databases/Oracle.json) | `*` | No specific group requirement |
| Oracle MySQL | [`Databases/Oracle_MySQL.json`](Databases/Oracle_MySQL.json) | `*` | No specific group requirement |
| SQL Server | [`Databases/SQL_Server.json`](Databases/SQL_Server.json) | `Devices by Type/SQL Servers` | `hasCategory("MSSQL")` |


### Environmental

| Dashboard | JSON File | Scope | Notes |
| --- | --- | --- | --- |
| APC | [`Environmental/APC.json`](Environmental/APC.json) | `*` | No specific group requirement |


### Hardware

| Dashboard | JSON File | Scope | Notes |
| --- | --- | --- | --- |
| Cisco UCS | [`Hardware/Cisco_UCS.json`](Hardware/Cisco_UCS.json) | `*` | No specific group requirement |
| Cisco UCS Fabric Interconnects | [`Hardware/Cisco_UCS_Fabric_Interconnects.json`](Hardware/Cisco_UCS_Fabric_Interconnects.json) | `*` | No specific group requirement |
| Dell iDRAC | [`Hardware/Dell_iDRAC.json`](Hardware/Dell_iDRAC.json) | `*` | No specific group requirement |
| HP iLO | [`Hardware/HP_iLO.json`](Hardware/HP_iLO.json) | `*` | No specific group requirement |


### Kubernetes

#### Kubernetes / KSM (Modern)

| Dashboard | JSON File | Scope | Notes |
| --- | --- | --- | --- |
| Kubernetes API Server | [`Kubernetes/KSM (Modern)/Kubernetes_API_Server.json`](Kubernetes/KSM%20(Modern)/Kubernetes_API_Server.json) | Inherited |  |
| Kubernetes Cluster Overview | [`Kubernetes/KSM (Modern)/Kubernetes_Cluster_Overview.json`](Kubernetes/KSM%20(Modern)/Kubernetes_Cluster_Overview.json) | Inherited |  |
| Kubernetes Containers | [`Kubernetes/KSM (Modern)/Kubernetes_Containers.json`](Kubernetes/KSM%20(Modern)/Kubernetes_Containers.json) | Inherited |  |
| Kubernetes Controller Manager | [`Kubernetes/KSM (Modern)/Kubernetes_Controller_Manager.json`](Kubernetes/KSM%20(Modern)/Kubernetes_Controller_Manager.json) | Inherited |  |
| Kubernetes Daemonsets | [`Kubernetes/KSM (Modern)/Kubernetes_Daemonsets.json`](Kubernetes/KSM%20(Modern)/Kubernetes_Daemonsets.json) | Inherited |  |
| Kubernetes Deployments | [`Kubernetes/KSM (Modern)/Kubernetes_Deployments.json`](Kubernetes/KSM%20(Modern)/Kubernetes_Deployments.json) | Inherited |  |
| Kubernetes Endpoints | [`Kubernetes/KSM (Modern)/Kubernetes_Endpoints.json`](Kubernetes/KSM%20(Modern)/Kubernetes_Endpoints.json) | Inherited |  |
| Kubernetes etcd | [`Kubernetes/KSM (Modern)/Kubernetes_etcd.json`](Kubernetes/KSM%20(Modern)/Kubernetes_etcd.json) | Inherited |  |
| Kubernetes Helm Charts | [`Kubernetes/KSM (Modern)/Kubernetes_Helm_Charts.json`](Kubernetes/KSM%20(Modern)/Kubernetes_Helm_Charts.json) | Inherited |  |
| Kubernetes Inventory | [`Kubernetes/KSM (Modern)/Kubernetes_Inventory.json`](Kubernetes/KSM%20(Modern)/Kubernetes_Inventory.json) | Inherited |  |
| Kubernetes Jobs | [`Kubernetes/KSM (Modern)/Kubernetes_Jobs.json`](Kubernetes/KSM%20(Modern)/Kubernetes_Jobs.json) | Inherited |  |
| Kubernetes Nginx Ingress Controller | [`Kubernetes/KSM (Modern)/Kubernetes_Nginx_Ingress_Controller.json`](Kubernetes/KSM%20(Modern)/Kubernetes_Nginx_Ingress_Controller.json) | Inherited |  |
| Kubernetes Nodes | [`Kubernetes/KSM (Modern)/Kubernetes_Nodes.json`](Kubernetes/KSM%20(Modern)/Kubernetes_Nodes.json) | Inherited |  |
| Kubernetes Overview | [`Kubernetes/KSM (Modern)/Kubernetes_Overview.json`](Kubernetes/KSM%20(Modern)/Kubernetes_Overview.json) | `Kubernetes Cluster*` | Wildcard resource group match |
| Kubernetes Persistent Volume Claims | [`Kubernetes/KSM (Modern)/Kubernetes_Persistent_Volume_Claims.json`](Kubernetes/KSM%20(Modern)/Kubernetes_Persistent_Volume_Claims.json) | Inherited |  |
| Kubernetes Persistent Volumes | [`Kubernetes/KSM (Modern)/Kubernetes_Persistent_Volumes.json`](Kubernetes/KSM%20(Modern)/Kubernetes_Persistent_Volumes.json) | Inherited |  |
| Kubernetes Pod Disruption Budget | [`Kubernetes/KSM (Modern)/Kubernetes_Pod_Disruption_Budget.json`](Kubernetes/KSM%20(Modern)/Kubernetes_Pod_Disruption_Budget.json) | Inherited |  |
| Kubernetes Pods | [`Kubernetes/KSM (Modern)/Kubernetes_Pods.json`](Kubernetes/KSM%20(Modern)/Kubernetes_Pods.json) | Inherited |  |
| Kubernetes Replicasets | [`Kubernetes/KSM (Modern)/Kubernetes_Replicasets.json`](Kubernetes/KSM%20(Modern)/Kubernetes_Replicasets.json) | Inherited |  |
| Kubernetes Schedulers | [`Kubernetes/KSM (Modern)/Kubernetes_Schedulers.json`](Kubernetes/KSM%20(Modern)/Kubernetes_Schedulers.json) | Inherited |  |
| Kubernetes Services | [`Kubernetes/KSM (Modern)/Kubernetes_Services.json`](Kubernetes/KSM%20(Modern)/Kubernetes_Services.json) | Inherited |  |
| Kubernetes Statefulsets | [`Kubernetes/KSM (Modern)/Kubernetes_Statefulsets.json`](Kubernetes/KSM%20(Modern)/Kubernetes_Statefulsets.json) | Inherited |  |


### Linux

| Dashboard | JSON File | Scope | Notes |
| --- | --- | --- | --- |
| Linux | [`Linux/Linux.json`](Linux/Linux.json) | `Devices by Type/Linux Servers` | `isLinux()` |
| Linux - Monitored Processes | [`Linux/Linux_Monitored_Processes.json`](Linux/Linux_Monitored_Processes.json) | `Devices by Type/Linux Servers` | `isLinux()` |
| Linux - SSH | [`Linux/Linux_-_SSH.json`](Linux/Linux_-_SSH.json) | `*` | No specific group requirement |


### LogicMonitor

| Dashboard | JSON File | Scope | Notes |
| --- | --- | --- | --- |
| LM Config Collection | [`LogicMonitor/LM_Config_Collection.json`](LogicMonitor/LM_Config_Collection.json) | `*` | No specific group requirement |
| LogicMonitor Alerts | [`LogicMonitor/LogicMonitor_Alerts.json`](LogicMonitor/LogicMonitor_Alerts.json) | `*` | No specific group requirement |
| LogicMonitor Collectors | [`LogicMonitor/LogicMonitor_Collectors.json`](LogicMonitor/LogicMonitor_Collectors.json) | `Devices by Type/Collectors` | `hasCategory("Collectors")` |
| LogicMonitor Dashboards & Reports | [`LogicMonitor/LogicMonitor_Dashboards_&_Reports.json`](LogicMonitor/LogicMonitor_Dashboards_&_Reports.json) | `*` | No specific group requirement |
| LogicMonitor Overview | [`LogicMonitor/LogicMonitor_Overview.json`](LogicMonitor/LogicMonitor_Overview.json) | `*` | No specific group requirement |
| LogicMonitor Resources | [`LogicMonitor/LogicMonitor_Resources.json`](LogicMonitor/LogicMonitor_Resources.json) | `*` | No specific group requirement |
| LogicMonitor Users | [`LogicMonitor/LogicMonitor_Users.json`](LogicMonitor/LogicMonitor_Users.json) | `*` | No specific group requirement |
| LogicMonitor Websites | [`LogicMonitor/LogicMonitor_Websites.json`](LogicMonitor/LogicMonitor_Websites.json) | `*` | No specific group requirement |
| Minimal Monitoring | [`LogicMonitor/Minimal_Monitoring.json`](LogicMonitor/Minimal_Monitoring.json) | `*Minimal Monitoring*` | Minimal Monitoring resources |
| Welcome to LogicMonitor | [`LogicMonitor/Welcome_to_LogicMonitor.json`](LogicMonitor/Welcome_to_LogicMonitor.json) | `*` | No specific group requirement |


### Logs

| Dashboard | JSON File | Scope | Notes |
| --- | --- | --- | --- |
| Log Collection - Overview | [`Logs/LM_Logs_Collection.json`](Logs/LM_Logs_Collection.json) | `*` | No specific group requirement |


### Microsoft

| Dashboard | JSON File | Scope | Notes |
| --- | --- | --- | --- |
| Active Directory | [`Microsoft/Active_Directory.json`](Microsoft/Active_Directory.json) | `Devices by Type/Windows Servers` | `isWindows()` |
| DHCP Servers | [`Microsoft/DHCP_Servers.json`](Microsoft/DHCP_Servers.json) | `Devices by Type/Windows Servers` | `isWindows()` |
| DNS Servers | [`Microsoft/DNS_Servers.json`](Microsoft/DNS_Servers.json) | `Devices by Type/Windows Servers` | `isWindows()` |
| Exchange Servers | [`Microsoft/Exchange_Servers.json`](Microsoft/Exchange_Servers.json) | `Devices by Type/Windows Servers` | `isWindows()` |
| Failover Clustering | [`Microsoft/Failover_Clustering.json`](Microsoft/Failover_Clustering.json) | `Devices by Type/Windows Servers` | `isWindows()` |
| File Servers | [`Microsoft/File_Servers.json`](Microsoft/File_Servers.json) | `Devices by Type/Windows Servers` | `isWindows()` |
| IIS | [`Microsoft/IIS.json`](Microsoft/IIS.json) | `Devices by Type/Windows Servers` | `isWindows()` |
| Microsoft .NET Framework | [`Microsoft/Microsoft_.NET_Framework.json`](Microsoft/Microsoft_.NET_Framework.json) | `Devices by Type/Windows Servers` | `isWindows()` |
| Microsoft Message Queue | [`Microsoft/Microsoft_Message_Queue.json`](Microsoft/Microsoft_Message_Queue.json) | `Devices by Type/Windows Servers` | `isWindows()` |
| Windows Servers | [`Microsoft/Windows_Servers.json`](Microsoft/Windows_Servers.json) | `Devices by Type/Windows Servers` | `isWindows()` |
| Windows Time | [`Microsoft/Windows_Time.json`](Microsoft/Windows_Time.json) | `Devices by Type/Windows Servers` | `isWindows()` |


### Network

| Dashboard | JSON File | Scope | Notes |
| --- | --- | --- | --- |
| Arista | [`Network/Arista.json`](Network/Arista.json) | `Devices by Type/Network` | `isNetwork()` |
| Aruba Wireless | [`Network/Aruba_Wireless.json`](Network/Aruba_Wireless.json) | `*` | No specific group requirement |
| Cato SD-WAN | [`Network/Cato SD-WAN.json`](Network/Cato%20SD-WAN.json) | `Devices by Type/Cato` | Cato resources group |
| F5 BIG-IP | [`Network/F5_BIG-IP.json`](Network/F5_BIG-IP.json) | `*` | No specific group requirement |
| Fortinet FortiGate | [`Network/Fortinet_FortiGate.json`](Network/Fortinet_FortiGate.json) | `*` | No specific group requirement |
| Infoblox | [`Network/Infoblox.json`](Network/Infoblox.json) | `*` | No specific group requirement |
| Juniper Mist | [`Network/Juniper_Mist.json`](Network/Juniper_Mist.json) | `*Mist Organization*` | Mist organization resources |
| Pulse Secure | [`Network/Pulse_Secure.json`](Network/Pulse_Secure.json) | `*` | No specific group requirement |
| Ubiquiti Unifi | [`Network/Ubiquiti_Unifi.json`](Network/Ubiquiti_Unifi.json) | `*` | No specific group requirement |

#### Network / Arista Velocloud SD-WAN

| Dashboard | JSON File | Scope | Notes |
| --- | --- | --- | --- |
| Arista VeloCloud SDWAN Overview | [`Network/Arista Velocloud SD-WAN/Arista_VeloCloud_SDWAN_Overview.json`](Network/Arista%20Velocloud%20SD-WAN/Arista_VeloCloud_SDWAN_Overview.json) | `VeloCloud*` | VeloCloud resources |
| Arista VeloCloud SDWAN Performance | [`Network/Arista Velocloud SD-WAN/Arista_VeloCloud_SDWAN_Performance.json`](Network/Arista%20Velocloud%20SD-WAN/Arista_VeloCloud_SDWAN_Performance.json) | `VeloCloud*` | VeloCloud resources |

#### Network / Aruba EdgeConnect SD-WAN

| Dashboard | JSON File | Scope | Notes |
| --- | --- | --- | --- |
| Aruba EdgeConnect SDWAN Overview | [`Network/Aruba EdgeConnect SD-WAN/Aruba_EdgeConnect_SDWAN_Overview.json`](Network/Aruba%20EdgeConnect%20SD-WAN/Aruba_EdgeConnect_SDWAN_Overview.json) | `*` | No specific group requirement |
| Aruba EdgeConnect SDWAN Performance | [`Network/Aruba EdgeConnect SD-WAN/Aruba_EdgeConnect_SDWAN_Performance.json`](Network/Aruba%20EdgeConnect%20SD-WAN/Aruba_EdgeConnect_SDWAN_Performance.json) | `*` | No specific group requirement |

#### Network / Cisco

| Dashboard | JSON File | Scope | Notes |
| --- | --- | --- | --- |
| Cisco APIC | [`Network/Cisco/Cisco_APIC.json`](Network/Cisco/Cisco_APIC.json) | `*` | No specific group requirement |
| Cisco ASA | [`Network/Cisco/Cisco_ASA.json`](Network/Cisco/Cisco_ASA.json) | `Devices by Type/Cisco ASA` | Devices by Type dynamic group |
| Cisco Catalyst SD-WAN - Devices | [`Network/Cisco/Cisco_SD-WAN_Catalyst_-_Devices.json`](Network/Cisco/Cisco_SD-WAN_Catalyst_-_Devices.json) | `*` | No specific group requirement |
| Cisco Catalyst SD-WAN - Manager | [`Network/Cisco/Cisco_SD-WAN_Catalyst_-_Manager.json`](Network/Cisco/Cisco_SD-WAN_Catalyst_-_Manager.json) | `*` | No specific group requirement |
| Cisco DNA Center | [`Network/Cisco/Cisco_DNA_Center.json`](Network/Cisco/Cisco_DNA_Center.json) | `*` | No specific group requirement |
| Cisco Meraki Overview | [`Network/Cisco/Cisco_Meraki_Overview.json`](Network/Cisco/Cisco_Meraki_Overview.json) | `*Meraki*` | Meraki resources |
| Cisco Meraki Performance | [`Network/Cisco/Cisco_Meraki_Performance.json`](Network/Cisco/Cisco_Meraki_Performance.json) | `*Meraki*` | Meraki resources |
| Cisco Wireless | [`Network/Cisco/Cisco_Wireless.json`](Network/Cisco/Cisco_Wireless.json) | `*` | No specific group requirement |

#### Network / Common

| Dashboard | JSON File | Scope | Notes |
| --- | --- | --- | --- |
| BGP | [`Network/Common/BGP.json`](Network/Common/BGP.json) | `Devices by Type/Network` | `isNetwork()` |
| EIGRP | [`Network/Common/EIGRP.json`](Network/Common/EIGRP.json) | `*` | No specific group requirement |
| Netflow | [`Network/Common/Netflow.json`](Network/Common/Netflow.json) | `*` | No specific group requirement |
| Network Latency | [`Network/Common/Network_Latency.json`](Network/Common/Network_Latency.json) | `*` | No specific group requirement |
| Network Performance | [`Network/Common/Network_Performance.json`](Network/Common/Network_Performance.json) | `Devices by Type/Network` | `isNetwork()` |
| NTP | [`Network/Common/NTP.json`](Network/Common/NTP.json) | `*` | No specific group requirement |
| OSPF | [`Network/Common/OSPF.json`](Network/Common/OSPF.json) | `Devices by Type/Network` | `isNetwork()` |
| SSL Certificates | [`Network/Common/SSL_Certificates.json`](Network/Common/SSL_Certificates.json) | `*` | No specific group requirement |

#### Network / Palo Alto Networks

| Dashboard | JSON File | Scope | Notes |
| --- | --- | --- | --- |
| Palo Alto Networks | [`Network/Palo Alto Networks/Palo_Alto_Networks.json`](Network/Palo%20Alto%20Networks/Palo_Alto_Networks.json) | `Devices by Type/Palo Alto` | `hasCategory("PaloAlto")` |
| Palo Alto Networks - BGP | [`Network/Palo Alto Networks/Palo_Alto_Networks_-_BGP.json`](Network/Palo%20Alto%20Networks/Palo_Alto_Networks_-_BGP.json) | `Devices by Type/Network` | `isNetwork()` |
| Palo Alto Networks - IPSEC Tunnels | [`Network/Palo Alto Networks/Palo_Alto_Networks_-_IPSEC_Tunnels.json`](Network/Palo%20Alto%20Networks/Palo_Alto_Networks_-_IPSEC_Tunnels.json) | `Devices by Type/Palo Alto` | `hasCategory("PaloAlto")` |
| Palo Alto Networks - Predefined Reports | [`Network/Palo Alto Networks/Palo_Alto_Networks_-_Predefined_Reports.json`](Network/Palo%20Alto%20Networks/Palo_Alto_Networks_-_Predefined_Reports.json) | `*` | No specific group requirement |


### SaaS

| Dashboard | JSON File | Scope | Notes |
| --- | --- | --- | --- |
| SaaS Lite Overview | [`SaaS/SaaS_Lite_Overview.json`](SaaS/SaaS_Lite_Overview.json) | `*` | No specific group requirement |
| Webex | [`SaaS/Webex.json`](SaaS/Webex.json) | `*` | No specific group requirement |
| Zoom (SaaS) | [`SaaS/Zoom.json`](SaaS/Zoom.json) | `*` | No specific group requirement |

#### SaaS / Airbrake

| Dashboard | JSON File | Scope | Notes |
| --- | --- | --- | --- |
| Airbrake Overview | [`SaaS/Airbrake/Airbrake_Overview.json`](SaaS/Airbrake/Airbrake_Overview.json) | `*` | No specific group requirement |

#### SaaS / Collector-Based

| Dashboard | JSON File | Scope | Notes |
| --- | --- | --- | --- |
| Slack | [`SaaS/Collector-Based/Slack.json`](SaaS/Collector-Based/Slack.json) | `*` | No specific group requirement |

#### SaaS / MongoDB

| Dashboard | JSON File | Scope | Notes |
| --- | --- | --- | --- |
| MongoDB Atlas Account Overview | [`SaaS/MongoDB/MongoDB_Account_Overview.json`](SaaS/MongoDB/MongoDB_Account_Overview.json) | None |  |
| MongoDB Atlas Process | [`SaaS/MongoDB/MongoDB_Process.json`](SaaS/MongoDB/MongoDB_Process.json) | None |  |

#### SaaS / Office 365

| Dashboard | JSON File | Scope | Notes |
| --- | --- | --- | --- |
| Office 365 Mail | [`SaaS/Office 365/Office_365_Mail.json`](SaaS/Office%20365/Office_365_Mail.json) | Inherited |  |
| Office 365 OneDrive | [`SaaS/Office 365/Office_365_OneDrive.json`](SaaS/Office%20365/Office_365_OneDrive.json) | Inherited |  |
| Office 365 Overview | [`SaaS/Office 365/Office_365_Overview.json`](SaaS/Office%20365/Office_365_Overview.json) | Inherited |  |
| Office 365 Service Health | [`SaaS/Office 365/Office_365_Service_Health.json`](SaaS/Office%20365/Office_365_Service_Health.json) | Inherited |  |
| Office 365 SharePoint | [`SaaS/Office 365/Office_365_SharePoint.json`](SaaS/Office%20365/Office_365_SharePoint.json) | Inherited |  |
| Office 365 Subscriptions | [`SaaS/Office 365/Office_365_Subscriptions.json`](SaaS/Office%20365/Office_365_Subscriptions.json) | Inherited |  |
| Office 365 Teams | [`SaaS/Office 365/Office_365_Teams.json`](SaaS/Office%20365/Office_365_Teams.json) | Inherited |  |

#### SaaS / OpenAI

| Dashboard | JSON File | Scope | Notes |
| --- | --- | --- | --- |
| OpenAI SaaS | [`SaaS/OpenAI/OpenAI_SaaS.json`](SaaS/OpenAI/OpenAI_SaaS.json) | Inherited |  |

#### SaaS / Salesforce

| Dashboard | JSON File | Scope | Notes |
| --- | --- | --- | --- |
| SalesForce Overview | [`SaaS/Salesforce/SalesForce_Overview.json`](SaaS/Salesforce/SalesForce_Overview.json) | Inherited |  |


### Storage

| Dashboard | JSON File | Scope | Notes |
| --- | --- | --- | --- |
| Dell EMC Isilon | [`Storage/Dell_EMC_Isilon.json`](Storage/Dell_EMC_Isilon.json) | `*` | No specific group requirement |
| Dell EMC Unity | [`Storage/Dell_EMC_Unity.json`](Storage/Dell_EMC_Unity.json) | `*` | No specific group requirement |
| HP 3PAR | [`Storage/HP_3PAR.json`](Storage/HP_3PAR.json) | `*` | No specific group requirement |
| NetApp 7-Mode | [`Storage/NetApp_7-Mode.json`](Storage/NetApp_7-Mode.json) | `*` | No specific group requirement |
| NetApp Cluster Mode | [`Storage/NetApp_Cluster_Mode.json`](Storage/NetApp_Cluster_Mode.json) | `*` | No specific group requirement |
| Nimble | [`Storage/Nimble.json`](Storage/Nimble.json) | `*` | No specific group requirement |
| Pure Storage | [`Storage/Pure_Storage.json`](Storage/Pure_Storage.json) | `*` | No specific group requirement |


### Virtualization

| Dashboard | JSON File | Scope | Notes |
| --- | --- | --- | --- |
| Cisco Hyperflex | [`Virtualization/Cisco_Hyperflex.json`](Virtualization/Cisco_Hyperflex.json) | `*` | No specific group requirement |
| Hyper-V | [`Virtualization/Hyper-V.json`](Virtualization/Hyper-V.json) | `Devices by Type/Hyper-V` | `hasCategory("HyperV")` |
| Nutanix | [`Virtualization/Nutanix.json`](Virtualization/Nutanix.json) | `*` | No specific group requirement |

#### Virtualization / VMware

| Dashboard | JSON File | Scope | Notes |
| --- | --- | --- | --- |
| VMware ESXi (Managed) | [`Virtualization/VMware/VMware_ESXi_(Managed).json`](Virtualization/VMware/VMware_ESXi_(Managed).json) | `Devices by Type/VMware ESXi Hosts` | Devices by Type dynamic group |
| VMware ESXi (Standalone) | [`Virtualization/VMware/VMware_ESXi_(Standalone).json`](Virtualization/VMware/VMware_ESXi_(Standalone).json) | `Devices by Type/VMware Hosts` | `system.virtualization =~ "VMware ESXi Host"` |
| VMware vCenter Server Appliance | [`Virtualization/VMware/VMware_vCenter_Server_Appliance.json`](Virtualization/VMware/VMware_vCenter_Server_Appliance.json) | `*` | No specific group requirement |
| VMware vSphere | [`Virtualization/VMware/VMware_vSphere.json`](Virtualization/VMware/VMware_vSphere.json) | `Devices by Type/VMware vCenters` | `system.virtualization =~ "VMware ESXi vCenter"` |


### Voice

| Dashboard | JSON File | Scope | Notes |
| --- | --- | --- | --- |
| Cisco Unified Border Element | [`Voice/Cisco_Unified_Border_Element.json`](Voice/Cisco_Unified_Border_Element.json) | `*` | No specific group requirement |
| Cisco Unified Communications | [`Voice/Cisco_Unified_Communications.json`](Voice/Cisco_Unified_Communications.json) | `*` | No specific group requirement |


### Websites

| Dashboard | JSON File | Scope | Notes |
| --- | --- | --- | --- |
| LM Uptime | [`Websites/LM_Uptime.json`](Websites/LM_Uptime.json) | `*` | No specific group requirement |
