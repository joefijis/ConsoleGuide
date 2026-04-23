---
title: "RxCheck : Configuring the Required Fields"
parent: "RxConsole User Guide"
nav_order: 21
---
Each State PDMP Administrator can configure the PMIX fields required in the request message to search for a patient in the PDMP system. The name-matching algorithm implemented within the PDMP system determines these required fields.

A PDMP administrator can configure these fields by navigating to the SRS Configuration page and clicking on the Patient Required Fields button.

![image-20251223-174300.png](attachments/185499678/184647725.png?width=258)

Set the required fields for the patient prescription drug history (PPDH) and the patient prescription picklist (PPPL) queries.

![image-20251223-174311.png](attachments/185499678/184647731.png?width=206)

When processing an integration request involving a federated query, you can choose to enforce your state’s data requirements by enabling the Home State Priority option. This will reject the entire request if it does not meet the required fields defined by your state.

![image-20251223-174326.png](attachments/185499678/185303056.png?width=225)