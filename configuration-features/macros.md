---
title: Macros
slug: tiJ--macros
createdAt: Tue Mar 07 2023 22:17:21 GMT+0000 (Coordinated Universal Time)
updatedAt: Tue Mar 07 2023 22:26:48 GMT+0000 (Coordinated Universal Time)
description: >-
  A list of predefined Macros variables that can be used as templates for
  substituting attributes in the Preset configuration.
---

# Macros

While creating or editing Preset, it is possible to click on a macros field with the left mouse button to add it to the Code field while editing preset in the Preset form.

![Macros list](../.gitbook/assets/hlF6DGDCJgwJSWglb7QNG\_image.png)

<details>

<summary>What do each macros represent?</summary>

* onu.serial\_number - serial number of the ONU
* onu.port\_interface - ONU port interface
* onu.qinq\_free\_vlan - free qinq vlan ONU port
* onu.onu\_interface - ONU interface
* onu\_number - ONU number
* onu.name - ONU name
* onu\_type.value - ONU type value
* onu.mac\_address - ONU mac address
* onu.mac\_address | split "." - mac address of the current ONU, separated by the dot character
* onu.mac\_address | split "-" - mac address of the current ONU, separated by the dash character
* input\_params.field\_name - field name input\_params

You can view examples of their samples [here](https://app.gitbook.com/o/FLfeqEYvh9QVB713VXQE/s/MviMfLPCHms6Yo2oirJF/\~/changes/5/macros/macros-descriptions).

</details>

### View macros info

Clicking on the view icon opposite a specific Macros opens a modal window with Macros details. The following fields are available:

* Name - Macros title
* Example - an example value
* Description en - description of Macros in English

From this modal window, it is also possible to **edit Macros** by pressing edit or close it by pressing the Close button. After editing, you can save changes by using the Save button or cancel the action by using the Cancel button.
