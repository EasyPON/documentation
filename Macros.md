---
title: Macros
slug: tiJ--macros
createdAt: Tue Mar 07 2023 22:17:21 GMT+0000 (Coordinated Universal Time)
updatedAt: Tue Mar 07 2023 22:26:48 GMT+0000 (Coordinated Universal Time)
---

A list of predefined Macros variables that can be used as templates for substituting attributes in the Preset configuration.

*   onu.serial\_number - serial number of the ONU

*   onu.port\_interface - ONU port interface

*   onu.qinq\_free\_vlan - free qinq vlan ONU port

*   onu.onu\_interface - ONU interface

*   onu\_number - ONU number

*   onu.name - ONU name

*   onu\_type.value - ONU type value

*   onu.mac\_address - ONU mac address

*   onu.mac\_address | split ":" - mac address of the ONU separated by the specified character

*   onu.mac\_address | split "." - mac address of the ONU separated by the specified character

*   onu.mac\_address | split "-" - mac address of the ONU separated by the specified character

*   input\_params.field\_name - field name input\_params

While creating or editing Preset, it is possible to click on a macro field with the left mouse button to add it to the Code field while editing preset in the Preset form.

![Macros list](../../assets/hlF6DGDCJgwJSWglb7QNG_image.png)

