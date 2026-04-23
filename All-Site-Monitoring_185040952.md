---
title: "RxCheck : All Site Monitoring"
parent: "RxConsole User Guide"
nav_order: 11
---
To navigate to *All Sites* monitoring, follow the steps below.


<div class="step-image-layout" markdown="1">
<div class="steps-col" markdown="1">

1. Click on the *State Routing Service* button, followed by the *Heartbeat & Health Monitoring* option, located on the left-hand side of the screen.

</div>
<div class="images-col">

![image-20251223-175541.png](attachments/185040952/184614932.png?width=214)

</div>
</div>


<div class="step-image-layout" markdown="1">
<div class="steps-col" markdown="1">

1. Click on the *All Sites* button in the top right corner of the screen.

</div>
<div class="images-col">

![image-20251223-175600.png](attachments/185040952/184877086.png?width=450)

</div>
</div>


<div class="step-image-layout" markdown="1">
<div class="steps-col" markdown="1">

1. The next screen is the *SRS: Heartbeat and Health Monitoring* screen and includes a United States Map.

</div>
<div class="images-col">

![image-20251223-175623.png](attachments/185040952/185466892.png?width=463)

</div>
</div>

1. The map allows you to hover your cursor over a state and get the current status of their SRS server.

The states are color coordinated based on their SRS status. Please see the following table to better understand the colors.

![image-20251223-175718.png](attachments/185040952/184614938.png?width=157)

1. Scrolling down on this screen, you are able to see a list of the States and their connection status in a table. The table also allows you to see the most recent query to or from a state.

The following table includes a description of each of the table headers.

![image-20251223-175750.png](attachments/185040952/185106480.png?width=452)

1. You can search for a specific site by:

   1. Finding the state on the list using the page buttons under the table, or
   2. Searching for the state in the search box above the table.

2. Scrolling down further, the last table displays a list of the connected healthcare entities and the last time a query was received from them. A healthcare entity can be found by:

   1. Using the page buttons on the bottom of the table and looking for the entity, or
   2. Search for the site in the search bar above the table.

a)

![image-20251223-175833.png](attachments/185040952/184746001.png?width=124)

b)

![image-20251223-175924.png](attachments/185040952/184975398.png?width=213)

a)

![image-20251223-180028.png](attachments/185040952/185040960.png?width=124)

b)

![image-20251223-180122.png](attachments/185040952/185270296.png?width=216)

| **Status** | **Color Code** | **Color** |
| --- | --- | --- |
| **Up** | Green | ![image-20251223-180321.png](attachments/185040952/185434174.png?width=24) |
| **Down** | Yellow | ![image-20251223-180332.png](attachments/185040952/185303069.png?width=24) |
| **N/A** | Gray | ![image-20251223-180342.png](attachments/185040952/184877092.png?width=24) |
| **Currently Hovering** | Blue | ![image-20251223-180350.png](attachments/185040952/185794568.png?width=24) |

## PDMP Transaction Status Table

| **Heading** | **Description** |
| --- | --- |
| Name | Name and 2 letter abbreviation for the state. |
| From [State Code] (Outbound) | The date and time of the last query from your state to listed state. |
| To [State Code] (Inbound) | The date and time of the last query from this state to the users state. |
| Connection Status | The current status of that states SRS. |

## HCE Transaction Status to TT (Inbound)

| **Heading** | **Description** |
| --- | --- |
| Name | The HCE code to identify the appropriate healthcare entity. |
| Last Transaction Timestamp | The date and time of the last query from the healthcare entity to your state PDMP. |