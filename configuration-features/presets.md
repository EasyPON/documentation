---
description: >-
  The Presets section displays a list of available script templates, which can
  be used for registering ONU on the OLTs of different types.
---

# Presets for ONU

In this section the presets can be added, edited, and deleted. Also empty presets can be kept for adding different OLTs and ONU types to them later and archiving.

For your convenience, we prepared standard drafts of presets so you can use them from the beginning of your interaction with EasyPON:

* [ZTE c220 v1 GPON preset](presets/zte-s220-v1-gpon.md)
* [ZTE c320/300 v1 GPON preset](presets/zte-s320-300-v1-gpon.md)
* [ZTE c320/300 v2 GPON preset](presets/zte-s320-300-v2-gpon.md)

By default, a few distributed presets are also available in the EasyPON system as well. To use them it is required to assign OLT, ONU technology, and ONU type in the [edit Preset](presets.md#edit-preset-for-onu) form. Then you can select the assigned preset during [ONU registration](../onu-workspace/onu-registration.md).

## Preset list

Displaying added Presets at the Presets list in the Preset for ONU section.&#x20;

You can select items in the list to open a preset for the ONU on the specific page for viewing the selected Preset detailed information.

![Preset for ONU section list](<../.gitbook/assets/Screenshot 2024-02-16 at 10.13.00.png>)

Also, the **Add Preset** button is available in the section, which allows you to add new Presets. You can also find the Docs button to get to this manual section.

## Preset for ONU page

By clicking the view button on the specific preset item in the Preset list you can view specific Preset for the ONU page.

It is also possible to view the event logs of selected presets by pressing the Event Logs quick actions menu button. You will be redirected to [Event Logs](../event-log.md) filtered by specific preset

<details>

<summary>The values are displayed in the page of the selected Preset</summary>

**Preset title** - the title of the preset

**ONU Type** - selected ONU types to which the Preset corresponds&#x20;

**Code** - Preset configuration script

**Description** - a detailed description of the Preset

**Macros used** - Macros which are used in the Preset

</details>

<figure><img src="../.gitbook/assets/Screenshot 2024-02-06 at 17.24.39.png" alt=""><figcaption><p>Preset for ONU page</p></figcaption></figure>

## Add Preset for ONU

On the Add Preset for ONU form, you can add the following preset information:&#x20;

* **Preset title** - the title of the preset
* **Code** - Preset configuration script with Macros
* **ONU Type** - selected ONU types to which the preset corresponds&#x20;
* **Description** - a detailed description of the preset
* **Macros list** - select macros which will be used in the preset

While adding or editing Preset you can choose **Preset for auto-registration** option. When marked the preset will be managed for autoregistration through the external API. You can fill default inputs params below this option.

<figure><img src="../.gitbook/assets/Screenshot 2024-02-06 at 17.30.37.png" alt=""><figcaption><p>Add Preest for ONU form</p></figcaption></figure>

## Edit Preset for ONU

You can change the preset data by pressing the **Edit** button modifying the Preset Name, Description, and Code with selected Macroses, and assigning ONU types.

<figure><img src="../.gitbook/assets/Screenshot 2024-02-06 at 17.27.32.png" alt=""><figcaption><p>Edit preset for ONU form</p></figcaption></figure>

## Re-configure ONU with Preset

Preset can be chosen and used while [registering the new ONU](../onu-workspace/onu-registration.md) or re-applied on the specific ONU page later after registration has been finished.

<figure><img src="../.gitbook/assets/Screenshot 2024-02-06 at 17.29.03.png" alt=""><figcaption><p>Re-configure ONU with the different Preset</p></figcaption></figure>

## Macros list

There is a [Macros list](macros.md) available on the right side. Macro variables can be used as the template for substituting standard parameters into a Preset configuration in the Code input field while adding or editing the preset.

<figure><img src="../.gitbook/assets/Screenshot 2024-02-06 at 17.20.11.png" alt="" width="375"><figcaption><p>Macros list</p></figcaption></figure>

