---
title: "RxCheck : NCPDP Taxonomy Code Mapping Overview"
parent: "RxConsole User Guide"
nav_order: 46
---
Taxonomy codes are 10-character alphanumeric identifiers used to classify healthcare providers and organizations based on the primary services they offer. These codes are assigned at both the individual and organization provider levels are used to represent the provider’s type, classification, and specialization for claim-level identification.

The taxonomy code structure consists of three hierarchical levels:

1. Provider Type
2. Classification
3. Specialization

Each successive level adds greater specificity. All taxonomy codes are 10 characters long and end with the letter “X”. The first four characters represent the Level 2 Classification, while the middle 5 characters vary depending on the Level 3 Specialization.

Within the RxCheck application, the roles configured in the *Interstate Data Sharing* and *Role Management* sections are derived from the NCPDP Taxonomy Code Mapping list. State PDMP Administrators can browse the complete list or search for specific codes or roles as needed.

The screenshot below shows a sample page from the NCPDP Taxonomy Code Mapping list. The accompanying table provides detailed descriptions for each column heading displayed in the screenshot.

![image-20260113-212955.png](attachments/202309646/202670093.png?width=471)

| **Heading** | **Description** |
| --- | --- |
| **Taxonomy Code** | Administrative codes set for identifying the provider type and area of specialization for health care providers.  They consist of ten alphanumeric characters always terminating with the letter “X.” |
| **Description** | A brief description of the Healthcare Professional Role displayed for that taxonomy code. |
| **PMIX Role** | The PMIX role that the corresponding taxonomy code is mapped to. |
| **PDMP** | The PDMP state for which the taxonomy code was created. |
| **Source** | Defines the origin of the taxonomy code. |

The following section contains step-by-step instructions on how to search for a NCPDP code in the RxConsole application. For additional clarity, each step is accompanied by a corresponding image or screenshot that depicts the action described.