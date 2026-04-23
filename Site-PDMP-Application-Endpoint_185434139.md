---
title: "RxCheck : Site PDMP Application Endpoint"
parent: "RxConsole User Guide"
nav_order: 68
---
This section defines the technical parameters of the state’s PDMP application necessary for message routing and integration. To configure this section, the State PDMP Administrator must enter the required information into the designated data fields.

The screenshot below demonstrates the configuration interface for this section. For additional clarity, the accompanying table provides descriptions for each data field shown in the screenshot.

![image-20251223-173307.png](attachments/185434139/185139207.png?width=471)

| **Heading** | **Data Field Name** | **Description** |
| --- | --- | --- |
|  | Protocol | This value can be set to “HTTP” or “HTTPS”. |
|  | Domain | The website address of the PDMP state.  This field is optional – if the domain is not provided, the system will automatically take the IP address. |
|  | Port Number | Port number where the website is hosted. |
|  | IP Address | IP address of the state PDMP server where the website is hosted. |
|  | URL Path | This is the base URL or path for the PDMP Application endpoint for all the requests. The value for this field is based on the IEPD option selected by Super Administrator at the time of PDMP Site creation. |
|  | PDMP URL | ***This field is auto-populated*** based on the values selected/entered in Protocol, Domain/IP Address, Port Number. |
| Security Credentials (HTTP Basic Authentication) | Inbound Username | A username and is an optional parameter which enables basic authentication on PDMP Site. |
| Inbound Password | A password and is an optional parameter which enables basic authentication on PDMP Site. |