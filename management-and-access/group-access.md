---
title: Group access
slug: Im7v-group-access
createdAt: Wed Nov 23 2022 22:25:03 GMT+0000 (Coordinated Universal Time)
updatedAt: Fri Mar 24 2023 19:56:16 GMT+0000 (Coordinated Universal Time)
---

# Group access

## Standard permission groups

We added for you two standard groups with permissions, that are, for our opinion, suitable for admins and support managers. By the way, you can easily configure

> The Group access section may not be displayed due to the limited access permissions of your account.

The Group access section displays information about already existing permission groups and allows their creation, editing, and deletion in the EasyPON system.

Permission groups can be assigned while creating or editing users on the user account creation or editing form.

Individual user permissions have higher priority status over permission groups. If individual user permissions are different from the group permissions, the group, and its permissions will be no longer active for the user.

The permission group can not be deleted if it is assigned at least to one user account. All the permission group changes when edited are automatically applied to the users with this group chosen. If the group is not chosen for the user, only his individual permissions will be active and need to be configured separately for each such user.

All available permission groups are displayed on the All-access page in a list with fields:

* № - the serial number in the table
* Name - the name of the access rights group
* View - displaying information about a specific group of permissions

![The All Access page, which displays all available groups of access rights in the EasyPON system](../.gitbook/assets/9rUwVPK3SeRQFvXF7toBa\_image.png)

## Access group view

After clicking the View button, a page with information about the selected group of access rights is displayed in the Group list table. On this page, you can edit the group name and access rights or delete the selected group.

![Group info page](../.gitbook/assets/dPhqcvrTTr5\_B8I9f2X2A\_image.png)

### Quick Actions Bar

The following commands are displayed on the Quick Actions panel

* Back - return to the main page of the All Access section
* Edit - editing access rights group
* Delete - delete the access rights group after confirming the action

### All permissions

Displaying sections of access rights that are active in the group. With full access to the section, the Full Access switch will be active, if the rights are limited, then the group will have the inscription Partial Access.

If no item is checked in the section it will be marked as No Access.

The display of individual elements in the rights section has the value Yes and No.

## Adding an access permission group

![Add group page](../.gitbook/assets/kgXuvLrTN7mkh-D0WwZ1y\_image.png)

To add a group, you need to specify the name in the Name group input and the sections of access rights that will be activated in the group. If you need to set full access to the section, you need to activate the Full Access switch. If the rights are limited, then the group will have Partial Access and the necessary accesses must be set separately.

If no item is checked in the section, it will be marked No Access.

After adding data and accesses, use the Cancel button to cancel the creation of a group of accesses and Save to save the result. After saving the result of creating an access rights group, a redirect will be made to the All Access page with a list of all access rights groups, where the newly created one will also be displayed.
