---
title: "RxCheck : RxCheck Hub Service Host Endpoint"
parent: "RxConsole User Guide"
nav_order: 59
---
The RxCheck Hub Service Host Endpoint section is a critical part of configuring the hub connection with the RxConsole application. The RxCheck Hub, a core component of the PMIX architecture, functions as a fully operational data-sharing system that allows states to securely and efficiently exchange Prescription Drug Monitoring Program (PDMP) data with other states and integration partners (e.g. Health Information Exchanges (HIE) and Electronic Health Records (EHR).

All data fields in this section are auto-populated by the system, based on the information originally entered by the Super Administrator during site creation. State PDMP Administrators can review this information and should contact the RxCheck technical team if any discrepancies or concerns arise.

The screenshot below shows the configuration interface for this section. The accompanying table provides details descriptions for each data field presented.

![image-20251223-170830.png](attachments/184778762/185499671.png?width=471)

| **Data Field Name** | **Description** |
| --- | --- |
| Protocol | This value cannot be changed and is set to “HTTPS”.This value cannot be changed and is set to “HTTPS”. |
| Domain | This value cannot be changed and is automatically set to the hub domain name. |
| Port Number | This value cannot be changed and is automatically set to the port on which the Hub is running. |
| IP Address | This value cannot be changed and is automatically set to the IP address for the Hub. |
| PMIX2 Hub Endpoint URL | ***This field is auto-populated.*** It is a fully qualified URL for the PMIX2 NIEM4 service on the RxCheck Hub. |