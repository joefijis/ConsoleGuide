---
title: "RxCheck : Heartbeat Notifications"
parent: "RxConsole User Guide"
nav_order: 34
---
Using the Heartbeat Notifications feature, the PDMP Administrator can subscribe to receive email notifications and text messages about the PDMP and HCE connections.

To navigate to the Heartbeat notifications, follow the instructions below.


<div class="step-image-layout" markdown="1">
<div class="steps-col" markdown="1">

1. Click on the *State Routing Service* button, followed by the *Heartbeat Notifications* option, located on the left-hand side of the screen.

</div>
<div class="images-col">

![image-20251223-181542.png](attachments/185663506/185696283.png?width=250)

</div>
</div>

![image-20251223-181640.png](attachments/185663506/185729052.png?width=471)

1. Select the desired boxes to subscribe to that notification.

   1. If the *Email* option is checked, the user will receive emails to the mailbox associated with their RxConsole application login.
   2. If the *SMS* option is checked, the user will receive text messages on the mobile phone number specified in their RxConsole application profile.

You will need to email the RxCheck admin to add a phone number to enable the SMS notifications option.


<div class="step-image-layout" markdown="1">
<div class="steps-col" markdown="1">

1. After making any changes, a user will want to press the *Save* button to process any changes made to notifications.

</div>
<div class="images-col">

![image-20251223-181733.png](attachments/185663506/184614944.png?width=168)
![image-20251223-181755.png](attachments/185663506/184778776.png?width=50)

</div>
</div>

The table below explains the different subscription options that a PDMP administrator can subscribe to.

| **Heading** | **Subscription Option** | **Description** |
| --- | --- | --- |
| **PDMP Connection** | **Your PDMP SRS** | Receive alerts for connection disruptions that affect your state connection to the Hub. |
| **Performance** | Receive alerts for performance degradation in SRS instances affecting your state connection. |
| **Partnering PDMP SRS** | Receive alerts for connection disruptions for partnering states connected to yours. |
| **HCE Connection** | **Integration SRS** | Receive alerts for connection disruptions that affect integration connection to the Hub. |

Notifications are not immediate. A subscribed user will receive an email or SMS notification approximately 15 minutes after the first missed heartbeat is detected.