---
title: "RxCheck : Modifying an Existing Provider Validation"
parent: "RxConsole User Guide"
nav_order: 45
---
1. Click on the *Provider Management* button, followed by the *Provider Validation* option, located on the left-hand side of the screen.

2. The Provider Validation screen allows you to view a list of existing validations that have been added and includes a button to add a new provider validation.

The names of the headers are described in the table following these steps.

1. To view and/or modify an existing validation, click on the name of a validation.

2. The following screen allows you to change settings related to the existing validation.

   1. Name – change the name of the validation settings.
   2. Select Roles – change the roles that are subject to validation.
   3. Validation Type – if *Mandatory* is chosen, a query will fail if the fields are not present, while Validate will stop a query if the validation check fails.
   4. Datasource – allows you to select a datasource to reference for the validation check. (Only present if validate is chosen for the *Validation Type*.)
   5. Selection – if *All* is chosen, all boxes checked in the *Validation Field(s)* selection will be checked for validation. If *Any* is chosen, only one of the numbers must pass for the validation to be successful.
   6. Validation Field(s) – allows you to check which ID numbers are subject to validation.

3. Press the *Save* button on the right corner of the screen to record your changes to provider validation to the RxConsole for your state.

4. Alternatively, if you do not wish to proceed with your changes, you can press the *Cancel* button to discard changes and return to the previous screen.

5. Verify the Provider Validation was successfully updated by looking for the Alert that states, “Provider Validation Updated”.

   You will also return to the Provider Validation screen and should see your changes in the *List of Provider Validations*.

![image-20260113-210742.png](attachments/200572941/202080262.png?width=225)![image-20260113-210814.png](attachments/200572941/201588738.png?width=118)![image-20260113-210819.png](attachments/200572941/200605727.png?width=135)![image-20260113-210825.png](attachments/200572941/200966157.png?width=132)![image-20260113-210924.png](attachments/200572941/202964993.png?width=165)![image-20260113-210959.png](attachments/200572941/202342413.png?width=206)![image-20260113-211024.png](attachments/200572941/202571780.png?width=153)![image-20260113-211028.png](attachments/200572941/202899464.png?width=119)![image-20260113-211033.png](attachments/200572941/202047515.png?width=109)![image-20260113-211038.png](attachments/200572941/202997761.png?width=206)![image-20260113-211143.png](attachments/200572941/201785346.png?width=49)![image-20260113-211148.png](attachments/200572941/202375175.png?width=59)![image-20260113-211153.png](attachments/200572941/203030529.png?width=198)

| **Header** | **Description** |
| --- | --- |
| **Name** | The name given to this specific set of validation rules. |
| **Datasource Name** | The name of the datasource that is referenced for validation. |
| **Validation Fields** | The identification numbers that are subject to validation. |
| **Validate Type** | The type of validation occurring, Mandatory will stop a query if the fields are not present, while Validate will stop a query if the validation check fails. |
| **Created Date** | The date and time the validation rules were created. |