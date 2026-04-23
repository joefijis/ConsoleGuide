---
title: "RxCheck : Breakdown of Healthcare Entity Site Details"
parent: "RxConsole User Guide"
nav_order: 19
---
Once a healthcare entity record is created, the user will be able to add, view and manage the following details by clicking on the respective menu options.

![image-20260108-172426.png](attachments/195592193/195788801.png?width=169)

The following subsections provide a detailed breakdown of each data field, as displayed on each menu option/section of a healthcare entity’s record.

---

## Site Details

This section displays information related to this specific HCE.

![image-20260108-172517.png](attachments/195592193/195854337.png?width=471)

| **Heading** | **Description** |
| --- | --- |
| **Healthcare Entity Name** | The name of the Healthcare Entity. |
| **Site Code** | A six-character code that follows the following format:   * Two letters to represent the state code. This is auto-populated. * An underscore (\_). * Three letters to represent a HCE site. These are entered by the PDMP administrator.    + When deciding on the three letters to represent a HCE, think of the initials for the company. Planning is often beneficial to avoid creating abbreviations that lead to confusion. One site code can cover multiple individual facilities within a state.   + Example: Walmart may be **WLT** or **WAL**, where Walgreens may be **WGN** or **WAL**. |
| **Site Type** | Refers to the site type. This value can be set as one of the following:   * EHR – Electronic Health Records * EMR – Electronic Medical Records * HIE – Health Information Exchange * PDS – Pharmacy Dispensing System |
| **Description** | A simple description of the HCE site. |
| **Status** | Status that indicates if a site is *Active* or *Inactive*. |
| **Interstate Query** | When checked, the HCE will be able to send interstate data requests. |
| **Select Vendor** | The integration vendor providing services to this healthcare entity. |
| **Number of Prescribers with DEA numbers** | A count of prescribers with DEA numbers at that HCE. |
| **Number of Pharmacists** | A count of pharmacists at that HCE. |
| **Number of Prescribers (Include All Providers With Prescriptive Authority)** | A count of all prescribers at that HCE. |
| **Select Interfaces** | The type of connection the HCE is using to connect to RxCheck or third-party integrator. The following options are available:   * NCPDP2017 * HTML * FHIR3 * FHIR4 * PMIX2 * JSON |

---

## Contact Details

This section contains the primary and secondary contact information for individuals to contact for further inquiries related to this specific HCE.

![image-20260108-172738.png](attachments/195592193/195985409.png?width=471)

| **Heading** | **Description** |
| --- | --- |
| **First Name** | Individual contact person’s first name. |
| **Last Name** | Individual contact person’s last name. |
| **Phone Number** | Individual contact person’s phone number. |
| **Extension** | Individual contact person’s phone number extension, if any. |
| **Email Address** | Individual contact person’s email address. |

---

## Vendor Details

This section contains the SRS hosting details and indicates if the healthcare entity’s integration is managed by the HCE IT team, the state, or by a vendor.

![image-20260108-173225.png](attachments/195592193/196083713.png?width=204)![image-20260108-173231.png](attachments/195592193/195100675.png?width=471)

| **Heading** | **Description** |
| --- | --- |
| **HCE IT** | This option indicates that the IT team of the HCE oversees the SRS hosting and managing responsibilities. |
| **State** | This option indicates that the IT team of the state oversees the SRS hosting and managing responsibilities. |
| **Vendor** | This option indicates that a third-party vendor (not the HCE) oversees the SRS hosting and managing responsibilities. |

**Note:** If the *Vendor* option is chosen, additional fields need to be populated.

| **Heading** | **Description** |
| --- | --- |
| **Where is it Hosted** | Refers to where the vendor hosts the SRS server for the HCE. The following options can be selected.   * HCE IT INFRA – Hosted by the healthcare entity’s infrastructure. * Vendor IT INFRA – Hosted by the vendors infrastructure. * Private Cloud – Hosted on a private cloud, accessible by only the HCE and/or vendor. * Government Cloud – Hosted on a government cloud, accessed by individuals outside the HCE or state PDMP team. |
| **Vendor Name** | The name of the vendor hosting the SRS. |
| **Vendor Address** | The address of the vendor hosting the SRS. |
| **Vendor Contact** | The name of the contact responsible for managing the SRS. |
| **Are the servers being accessed outside the US?** | A *Yes* or *No* question that asks if the SRS will be accessed for any reason outside the United States of America. |

---

## Manage Roles

This section enables the State PDMP Administrator to assign roles that authorize specific users within a healthcare entity to submit prescription data requests. Roles are assigned by selecting the appropriate tags associated with the healthcare entity.

Each tag corresponds to a recognized healthcare professional role or the type of services provided by the entity. These role assignments determine the level of access and functionality available to the entity within the RxCheck system.

All available roles are displayed by default as shown below. Clicking on a role will change the role to green. A green highlighted role is active or “Selected” and allows that role to initiate a query, while an off-white color indicates that the role is “Authorized” but inactive and cannot initiate a query.

![image-20260108-173531.png](attachments/195592193/194707461.png?width=471)

| **Button Name** | **Button Image** | **Functionality** |
| --- | --- | --- |
| **Assign All** | ![image-20260108-173634.png](attachments/195592193/195592200.png?width=66) | Automatically selects all displayed roles. |
| **Clear All** | ![image-20260108-173640.png](attachments/195592193/194772998.png?width=59) | Automatically deselects all displayed roles. |
| **Show List** | ![image-20260108-173647.png](attachments/195592193/195264514.png?width=70) | Will display all available roles in two separate lists, an *Authorized Roles* list and a *Selected Roles* list. |
| **Hide List** | ![image-20260108-173654.png](attachments/195592193/195264520.png?width=68) | Will display all available roles as tags (default).  **Note:** This option is only available when the roles are displayed as two separate lists. |

A screenshot of the *Show List* option is shown below and will only be displayed if the *Show List* button is clicked.

Clicking on a blue arrow transfers a role from the *Authorized Roles* list to the *Selected Roles* list. Clicking on an orange arrow transfers a role from the *Selected Roles* list to the *Authorized Roles* list.

![image-20260108-173718.png](attachments/195592193/196345857.png?width=471)

---

## Manage Facilities

This section provides details of the facilities related to this specific healthcare entity. These facilities and their active/ inactive statuses will be created and determined by the RxCheck PDMP Administrator or Super Administrator.

![image-20260108-173739.png](attachments/195592193/195428359.png?width=471)

There are two buttons available to an RxConsole user.

| **Button Name** | **Button Image** | **Functionality** |
| --- | --- | --- |
| **Add Facility** | ![image-20260108-173830.png](attachments/195592193/196018180.png?width=80) | Will display the *Facility* popup to enter a single facility. |
| **Add Multiple Facilities** | ![image-20260108-173835.png](attachments/195592193/195985415.png?width=128) | Will redirect the PDMP administrator to the *Add Facilities* page. |

---

### How to add a single healthcare facility

1. Click on the *Add Facility* button.

2. In the pop-up window, enter the requested information in the appropriate data fields.

To see a description of each field, see the table below.


<div class="step-image-layout" markdown="1">
<div class="steps-col" markdown="1">

1. Click on the *Save* button to save the populated information.

</div>
<div class="images-col">

![image-20260108-173925.png](attachments/195592193/195559440.png?width=83)
![image-20260108-173957.png](attachments/195592193/196313090.png?width=216)
![image-20260108-174010.png](attachments/195592193/196378625.png?width=49)

</div>
</div>

| **Heading** | **Description** |
| --- | --- |
| **Name** | Individual facility’s name. |
| **Facility Type** | Individual facility type. Options include:   * EHR – Electronic Health Record * PDS – Pharmacy Dispensing Software |
| **Facility Code** | Code specific to this individual facility. The HCE code is auto-populated, but the facility code is entered as an alphanumeric value. |
| **First Name** | Contact person’s first name at this individual facility. |
| **Last Name** | Contact person’s last name at this individual facility. |
| **Email** | Contact person’s email at this individual facility. |
| **Phone** | Contact person’s phone number at this individual facility. |
| **Extension** | Contact person’s phone number extension at this individual facility, if any. |

---

### How to add multiple healthcare facilities

1. Click on the *Add Multiple Facilities* button.

2. You will be directed to the *Add Facilities* screen.

3. Click on the *Standardized Facilities Template* link to download a template to populate. The template will download in an Excel workbook format (.xlsx).

   The first tab titled *Facilities File Template* contains columns to enter the same information available when adding a single facility. A table describing each heading is available in the previous subsection.

   The second tab titled *Field Definitions* provides an abbreviated summary of each field, its requirement status, and an example.

4. Populate the *Standardized Facilities Template* with each facility occupying a single row.

5. Press the *Click to select file* button to choose the populated template to upload into the system.

6. If all facilities share a single contact person, you can check the box labeled *One contact for all facilities* and data fields for that individual person will appear.

   A description of these fields can be found in the table in the previous subsection.

If contact information is included in both the uploaded data file and the UI (via “One contact for all facilities”), the UI entry will override and apply to all created facilities.

1. Click the *Upload* button to import the data populated in the file you selected in step 5.


<div class="step-image-layout" markdown="1">
<div class="steps-col" markdown="1">

2. The *Cancel* button will discard any changes made on this screen and return the user to the previous page.

</div>
<div class="images-col">

![image-20260108-174309.png](attachments/195592193/196444161.png?width=131)
![image-20260108-174324.png](attachments/195592193/196345863.png?width=356)
![image-20260108-174403.png](attachments/195592193/196509697.png?width=127)
![image-20260108-174407.png](attachments/195592193/195461122.png?width=180)
![image-20260108-174412.png](attachments/195592193/194838532.png?width=182)
![image-20260108-174417.png](attachments/195592193/195362820.png?width=356)
![image-20260108-174442.png](attachments/195592193/195264526.png?width=119)
![image-20260108-174527.png](attachments/195592193/196542465.png?width=154)
![image-20260108-174535.png](attachments/195592193/194740227.png?width=356)
![image-20260108-174613.png](attachments/195592193/196608001.png?width=137)
![image-20260108-174628.png](attachments/195592193/196476930.png?width=62)

</div>
</div>

---

## User Administration

This section lists details of the administrator(s) specific to this healthcare facility.

![image-20260108-174654.png](attachments/195592193/194707469.png?width=471)

| **Heading** | **Description** |
| --- | --- |
| **Email** | The email address used by the user to log into the RxConsole application. |
| **Name** | The first and last name of the HCE user. |
| **Site Name** | The HCE site code. |
| **Status** | The status of the HCE user account. |
| **User Type** | The type of account the HCE user has. This is typically displayed as *SUB\_ADMIN*. |

A State PDMP Administrator is allowed to add a new administrative user for a HCE following the steps below.

1. Click the *Add User* button to open a popup window.

2. In the popup window, enter the requested information into the appropriate data field.

A description of each field is available in the following table.


<div class="step-image-layout" markdown="1">
<div class="steps-col" markdown="1">

1. Click the *Save* button to save the information populated in the fields.

</div>
<div class="images-col">

![image-20260108-174754.png](attachments/195592193/195002372.png?width=72)
![image-20260108-174831.png](attachments/195592193/194838538.png?width=204)
![image-20260108-174838.png](attachments/195592193/196706305.png?width=52)

</div>
</div>

| **Heading** | **Description** |
| --- | --- |
| **Email** | The contact email for the HCE user and username for RxConsole. |
| **Password** | The password for the HCE user to access the RxConsole application. |
| **Site Code** | The site code for the HCE user. This field will be auto-populated. |
| **First Name** | The HCE user’s first name. |
| **Middle Name** | The HCE user’s middle name. |
| **Last Name** | The HCE user’s last name. |
| **Status** | The status of this HCE user’s account. Can be set to either *Active* or *Inactive*. |
| **Phone Number** | The HCE user’s phone number. |

---

## Opening a Health Entity Record

1. Click on the *Healthcare Entities* button, located on the left-hand side of the screen.

2. Find the healthcare entity using one of two methods:

* Scroll through the list on the screen (may need to navigate to the next screen by using the navigation arrows at the bottom of the list)
* Type the name of the HCE into the search bar labeled *Global Filter* in the top right.

![image-20260108-175045.png](attachments/195592193/196149251.png?width=197)![image-20260108-175123.png](attachments/195592193/196575234.png?width=145)![image-20260108-175128.png](attachments/195592193/196313096.png?width=195)

![image-20260108-175205.png](attachments/195592193/196771842.png?width=423)

1. Select the desired healthcare entity to view further details about that facility.


<div class="step-image-layout" markdown="1">
<div class="steps-col" markdown="1">

2. To edit a record, make your changes and click the *Save* button to ensure any new information is recorded.
   To exit without saving, click on the *Cancel* button.

</div>
<div class="images-col">

![image-20260108-175220.png](attachments/195592193/194674696.png?width=132)
![image-20260108-175241.png](attachments/195592193/195559446.png?width=52)
![image-20260108-175246.png](attachments/195592193/196837377.png?width=63)

</div>
</div>

---

## Export a list of your HCE’s and Facilities

1. Click on the *Healthcare Entities* button, located on the left-hand side of the screen.

2. In the top-right corner, there are two buttons to extract either:

* Export HCE’S—Downloads a list of healthcare entities, their HCE code, and their status.
* Export Facilities—Downloads a list of Facilities, their site code, and their status.

The HCE and facility lists are downloaded in a zipped folder. Please see the tables in previous sections for a description of the columns in these files.

1. Right-click on the zipped folder to view options


<div class="step-image-layout" markdown="1">
<div class="steps-col" markdown="1">

2. Select the “Extract All…” option.

</div>
<div class="images-col">

![image-20260108-175404.png](attachments/195592193/195133442.png?width=220)
![image-20260108-175436.png](attachments/195592193/196018187.png?width=198)
![image-20260108-175443.png](attachments/195592193/194674703.png?width=92)
![image-20260108-175551.png](attachments/195592193/196902913.png?width=126)

</div>
</div>

**HCE Export Columns**

| **Heading** | **Description** |
| --- | --- |
| **Code** | A six-character code that follows the following format:   * Two letters to represent the state code. * An underscore (\_). * Three letters to represent a HCE site. |
| **Name** | The name of the Healthcare Entity. |
| **Status** | Status that indicates if a site is *Active* or *Inactive*. |

**Facility Export Columns**

| **Heading** | **Description** |
| --- | --- |
| **Code** | A facility code specific to that individual healthcare facility. |
| **Name** | The name of the facility. |
| **Status** | Status that indicates if the facility is *Active* or *Inactive*. |