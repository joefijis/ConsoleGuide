---
title: "RxCheck : Provider Validation Overview"
parent: "RxConsole User Guide"
nav_order: 51
---
The term “Provider” refers to a licensed healthcare professional or organization legally authorized to deliver medical services to the public. Federal regulations recognize a wide range of provider types, including pharmacies, physicians, and nurse practitioners.

Most providers in the US are uniquely identified by a 10-digit National Provider Identifier (NPI), issued by the Centers for Medicare and Medicaid Services (CMS). Additionally, the Drug Enforcement Agency (DEA) in the US also assigns practitioners with a DEA Registration Number, authorizing them to prescribe controlled substances. Providers must also hold a valid state license, evidenced by a State License Number (SL#) specific to the state in which they practice.

Whenever a healthcare entity sends or receives a prescription data request via RxCheck, the provider’s NPI, DEA, and/or SL# is included in the data payload.

The Provider Validation feature in RxConsole allows State PDMP Administrators to configure whether the validation of the NPI, DEA, SL# and/or OTHER# is required, optional, or not validated prior to processing a request.

The following sections explain each option in detail.