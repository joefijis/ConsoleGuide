---
title: "RxCheck : SRS Certificate"
parent: "RxConsole User Guide"
nav_order: 61
---
Each state is responsible for generating its own digital certificate using Microsoft PowerShell. Detailed instructions for this process are provided in the SRS Installation Guide for PDMP.

The certificate, created by the PDMP state implementing the SRS software, supports secure end-to-end message encryption. The SRS certificate uses a public key/private key infrastructure:

* The **public key** (contained in the certificate) is used to encrypt outgoing messages.
* The **private key** is used by the receiving system to decrypt the message.

**Important:** The certificate includes two components:

1. **Private Key—**Must be kept confidential and never shared, including within the RxCheck Network.
2. **Public Key—**Uploaded to the RxConsole and shared with other participating states in the RxCheck Network.

The State PDMP Administrator must input the required data into the fields provided under the SRS Certificate section.

The screenshot below illustrates the configuration interface for this section. For added clarity, the subsequent table provides descriptions for each data field shown in the screenshot.

![image-20251223-173724.png](attachments/185139213/185401357.png?width=471)

| **Data Field Name** | **Description** |
| --- | --- |
| Private Key Subject | The key generated at the time of Site Certificate creation. The private key is in .pfx format. The Private key must be kept confidential by the PDMP State. |
| Public key (DER Format) | The key generated at the time of Site Certificate creation and is in .der format. The Public key is shared by the PDMP State with other PDMP States in the RxConsole Application. |
| Certificate Expiry Date | The date when the uploaded certificate expires. |