---
title: "RxCheck : Interstate Data"
parent: "RxConsole User Guide"
nav_order: 41
---
The Interstate Data-Sharing feature enables State PDMP Administrators to designate which state are authorized to send prescription data requests to their PDMP and to restrict access from unauthorized states.

Only states that have executed a formal Memorandum of Understanding (MOU) can establish a secure digital connection via the RxCheck platform. These states must be designated as “Selected States” with the Interstate Data-Sharing portal by the State Administrator to enable bidirectional data-sharing.

States that have not finalized a formal agreement cannot participate in interstate data exchange through RxCheck. If such a state attempts to send a request, it will receive a system-generated message stating: “Access denied by disclosing state”.

The screenshot below illustrates the configuration interface, showing the list of state authorized and unauthorized for interstate data-sharing.

![image-20260108-183143.png](attachments/196804611/197001217.png?width=490)

Within the Interstate Data Sharing interface, two lists are displayed to manage site-level authorization:

* Available Sites (left): This list displays PDMP sites that have not yet been authorized to connect with the host (disclosing) state. Sites in this list are unable to submit data requests to the host state, and any such attempts will result in failed transactions.
* Selected Sites (right): This list includes states that have been authorized to establish a bilateral connection with the disclosing state. These sites are permitted to send data requests and receive responses from the host PDMP system.

The following subsections provide step-by-step instructions for selecting and deselecting sites for interstate data sharing within the RxConsole Application. Each step is accompanied by a screenshot for visual reference.