---
id: manageSections
title: Manage Sections
sidebar_label: Manage Sections
# slug: /
---

These are the sections which will be displayed in the side bar of different screens based on the roles and permissions.

## Listing Sections

Manage section contains a table with each row having:

- `Section Name` : It is the name of the section which will appear in the user screen.
- `Manage Forms` : It is a button used to navigate to the respective subsections.

![section ](assets/manageSection/manageSectionScreen.png)

#### Change The Section Order

- Click on the `Change Order` button.
- Change the order as per the requirement by dragging.
- Click on `Save Order`.

## Create New Section

On clicking the `New Section` button, a modal will be opened which contains:

- `Name` : It is the name of the new section.
- `Choose Icon` : It is the icon for the new section which will appear at the left side of the section name in the user screen.
- `Status` : It is the status of the section to determine whether to display this section in the user screen or not.

## Listing Subsections

These are the list of sub sections in the selected section. It Contains:

- `Name` : It is the name of the subsection which will appear inside the section in user screen.
- `Manage Fields` : It is a button used to navigate to the respective fields.

![section ](assets/manageSection/manageFormScreen.png)

#### Change The Sub Section Order

- Click on the `Change Order` button.
- Change the order as per the requirement by dragging.
- Click on `Save Order`.

## Create New Sub Section

On clicking the `Create New Form` button a modal will be opened which contains:

- `Name` : It is the name of the new subsection of the selected section.

## Listing Fields

These are the list of subsections available for the selected section. It Contains:

- `Fields` : It is the name of the subsection which will appear inside that section in the user screen.
- `Type` : It is the type of the field like `Input Text`, `Input Number`, `Dropdown`, `Radio Button`, `Text Area`
- `Mandatory` : It is a checkbox to record whether the field is mandatory or not.
- `Input Box Size` : It allows the user to choose the size of the input box from the options.
  - `Full Width` : On selecting full width, the field occupies the full width of the form container.
  - `Half width` : On selecting half width, the field occupies the half width of the form container.
- `Actions` : Each field has two actions:

  - #### Edit:

    - On clicking the edit icon the edit modal will be opened.
    - The admin can edit the field details .
    - The edit modal contains the same [fields](#listing-fields) displayed in the table.

  - #### Delete:

    - On clicking the delete icon, a confirmation modal will be displayed before deleting the field permanently.
    - After confirming the delete action, the deleted field will no longer be displayed in the section.

![field ](assets/manageSection/manageFieldScreen.png)

#### Change the Field Order

- Click on the `Change Order` button.
- Change the order as per the requirement by dragging.
- Click on `Save Order`.

#### Preview of the Fields

- On clicking the `Preview` button in the `Sections` <- `Forms` <- `Manage Fields` page, the preview modal will be diplayed.
- The modal contains the all the fields of the selected sub section.

![section ](assets/manageSection/FormUIScreen.png)

## Create New Field

On clicking the `Create New Field` button, a modal will be opened which contains the [field](#listing-fields) details.

### Example

The sections added will be displayed in the respective user screen. For example,

1. Add a new section by clicking on the `New Section` Button.

![uiScreen ](assets/manageSection/newSection.png)

2. Go to `User Roles` section in the side bar.

![uiScreen ](assets/manageSection/userRoles.png)

3. Select a user role. For example, select `Doctor`.

![uiScreen ](assets/manageSection/doctor.png)

4. The newly added `Surgery Section` will be displayed in the permissions list.

5. Enable the permission for the new section in the doctor screen.

![uiScreen ](assets/manageSection/enableSurgery.png)

6. On saving the permission for the new section, a success modal will be displayed.

![uiScreen ](assets/manageSection/successModal.png)

7. Go to Doctor Screen inorder to view the new section in the side bar and click on the `Surgery` section.

![uiScreen ](assets/manageSection/drSideBar.png)

The surgery screen will be empty until it is been configured by the admin.

8. Go to admin screen and click on `Manage Sections` to configure the new section.

![uiScreen ](assets/manageSection/surgerySection.png)

9. Click on the `Manage Forms` at the right end of the surgery section in the list.

![uiScreen ](assets/manageSection/surgerySectionManageForm.png)

10. Click on the `Create New form` in the `Sections` <- `Manage Forms` and add a form `Form1`.

![uiScreen ](assets/manageSection/surgeryForm.png)

11. The newly added form name will be displayed inside the `Sections` <- `Manage Forms` page.

![uiScreen ](assets/manageSection/formList.png)

12. Click on the `Manage Fields` button in the `Sections` <- `Manage Forms` page against the newly added form `Form1`.

![uiScreen ](assets/manageSection/manageForm1.png)

13. In `Sections` <- `Manage Forms` <- `Manage Fields` click on the `Create New Field` button.

![uiScreen ](assets/manageSection/field.png)

14. The newly added fields inside the `Form1` will be listed in the `Sections` <- `Manage Forms` <- `Manage Fields` page.

![uiScreen ](assets/manageSection/formList1.png)

15.Click on the `Preview` button to see the preview of the form `Form1`.

![uiScreen ](assets/manageSection/fieldPreview.png)

16. The Final Doctor screen will be like:

![uiScreen ](assets/manageSection/finalDrScreen.png)
