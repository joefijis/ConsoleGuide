---
title: "RxCheck : Vendor Connection Requirements"
parent: "RxConsole User Guide"
nav_order: 80
---
An organization that wishes to provide EHR integrations of PDMP information must meet several requirements before being able to utilize the vendor connect enhancement feature of RxCheck.

1. Obtain a vendor administrator account as part of the onboarding process to become an authorized RxCheck vendor. You can find information on this process in the chapter titled, *Getting Started as a Vendor*, above.
2. Update your existing SRS server or set up a new SRS server utilizing version 3.2.1 of the SRS server software. This version can be found at the following link: <http://builds.rxcheck.org/SRS/v3.2.1/final/hce/>
3. Set up the SRS server running version 3.2.1 in your vendor administrator account. Instructions on this process can be found in the chapter titled, *State Routing Service (SRS) Configuration*, found above.
4. You can now migrate these integrated sites to the SRS server you configured in step 3 above.

By following the steps above, a vendor will be able to utilize the vendor connect enhancement.

A vendor will know that a HCE has been assigned to them, by noting its presence in the site selection window. An assigned HCE will be viewable in the site selection window.

![image-20260121-151634.png](attachments/209321985/209158152.png?width=373)

The screenshot above does not have any HCE’s assigned to the vendor.

---

## Vendor Connect Setup Checklist

---

☐ Become an authorized RxCheck Vendor by submitting an application to the RxCheck Team and receiving approval.

☐ Log into the RxConsole using your new vendor administrator account, created as part of becoming an authorized RxCheck Integration vendor.

☐ Update the SRS server to at least version 3.2.1.

☐ Configure the SRS server running version 3.2.1 in your vendor administrator account. *Ensure you have selected the state PDMP you are providing integrations for, as each PDMP site will need a different server.*

☐ Request the PDMP administrator for that state to assign the HCE’s you provide integrations for to you.

☐ Once the HCE’s have been assigned to you, migrate the HCE’s to the SRS you configured in your vendor administrator account.

☐ Reach out to the RxCheck Team if you experience any issues or have any questions.