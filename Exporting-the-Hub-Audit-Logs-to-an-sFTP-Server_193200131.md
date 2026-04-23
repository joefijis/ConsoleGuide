---
title: "RxCheck : Exporting the Hub Audit Logs to an sFTP Server"
parent: "RxConsole User Guide"
nav_order: 29
---
RxConsole enables PDMP Administrators to export RxCheck Hub audit logs to their state’s sFTP server by providing the required sFTP configuration—hostname, port, username, and password—via the “Log Extract” section on the Hub Audit Logs page.

![image-20260107-204826.png](attachments/193200131/193003523.png?width=281)

After clicking the *Log Extract* button, you will see the following window.

![image-20260107-204838.png](attachments/193200131/193560577.png?width=337)

The following table includes a description of each of the fields available.

| **Field** | **Description** |
| --- | --- |
| **Host Name** | The domain name or IP address of the remote SFTP server.  Example: sftp.example.com or 192.168.1.100. |
| **Port** | The port number used for the sFTP connection. The default is “22”, but it can be configured to other values by the server administrator. |
| **File Path** | The directory path on the remote server where files will be uploaded to or downloaded from.  Example: /home/sftp,\_user/uploads, or /data/incoming. |
| **Username** | The login name used to authenticate the user with the SFTP server. It is typically assigned by the server administrator. |
| **Password** | The secret key or password corresponding to the username for authentication. This can be omitted if key-based authentication is used. |
| **Active** | Allows a user to enable and disable the log extract function. When the box is green, it is enabled. When red, the functionality is disabled. |

After the sFTP configuration is saved, the system will activate the *Export Logs (sFTP)* button for the PDMP administrator. To initiate the log export, click this button. The system will process the request and send an email notification once the export is complete.

![image-20260107-205031.png](attachments/193200131/193200138.png?width=141)