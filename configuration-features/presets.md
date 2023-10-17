---
description: >-
  The Presets section displays a list of available Presets, which can be used to
  register ONU on the OLT of different types.
---

# Presets for ONU

In this section the presets can be added, edited, and deleted. Also empty presets can be kept for adding different OLTs and ONU types to them and experimenting.

For your convenience, we prepared standard drafts of presets so you can use them from the beginning of your interaction with EasyPON:

* [ZTE c220 v1 GPON preset](presets/zte-s220-v1-gpon.md)
* [ZTE c320/300 v1 GPON preset](presets/zte-s320-300-v1-gpon.md)
* [ZTE c320/300 v2 GPON preset](presets/zte-s320-300-v2-gpon.md)

## Macros list

There is a [Macros list](macros.md) available on the right side. Macros variables can be used as the template for substituting standard parameters into a Preset configuration in the Code input field while adding or editing the preset.

![Preset for ONU section](<../.gitbook/assets/Screenshot 2023-10-08 at 23.11.27.png>)

<details>

<summary>The values are displayed in the block of the selected Preset</summary>

**Preset title**&#x20;

**ONU Type** - selected ONU types to which the Preset corresponds&#x20;

**Description EN** - a detailed description of the Preset in English&#x20;

**Code** - Preset configuration script

</details>

## Preset list

Displaying added Presets at the Presets list in the Preset for ONU section. You can select items in the table to open a preset preview card for viewing the selected Preset. You can also make changes to the preset by pressing the **Edit** button and modifying the Preset Name, Description, Code, and ONU types.

![Preset form](<../.gitbook/assets/Screenshot 2023-10-08 at 23.32.05.png>)

Also, the **Add** and **Delete** buttons are available in the block, which allows you to add or delete Presets respectively. It is also to press the Docs button to get to this manual section.

While adding or editing Preset you can choose **Preset for autoregistration** option. When marked the preset will be managed for autoregistration through the external API.. You can fill default inputs params below this option.

Preset can be chosen and used while [registering the new ONU](../onu-workspace/onu-registration.md) or re-applied on the specific ONU page later after registration has been finished.

<figure><img src="../.gitbook/assets/Screenshot 2023-10-08 at 23.57.09.png" alt=""><figcaption><p>Re-configure ONU with the different Preset</p></figcaption></figure>
