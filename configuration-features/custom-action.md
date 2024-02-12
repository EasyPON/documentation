---
description: >-
  In the EasyPON web application, an Action for an ONU (Optical Network Unit)
  could be a specific operation or function that you want to perform on an ONU
  device.
---

# Actions for ONU

Action is a feature, that helps you to apply custom code to the ONU, that otherwise you have to perform manually step by step. This simplifies any interaction with ONU and helps you automate your daily routine. This could include tasks like provisioning, configuring, or troubleshooting the ONU.

The main difference between Preset and Action is that Ppreset is used for registering new ONUs instead of creating custom actions with registered ONUs in the EasyPON web application.\
\
You may access the Action submenu by clicking on **Settings -> Action** in the Main Menu.

## Action list

Displaying added Actions at the Action for ONU list in the Action for ONU section.&#x20;

You can select items in the list to open an action on the specific page for viewing the selected Action detailed information.

<figure><img src="../.gitbook/assets/Screenshot 2024-02-06 at 17.50.47 (1).png" alt=""><figcaption><p>Action for ONU</p></figcaption></figure>

Also, the **Add Action** button is available in the section, which allows you to add new Actions. You can also find the Docs button to get to this manual section.

## Action for ONU page

You can also **Edit**, **Delete**, and view event logs of documentation by clicking the Docs icon.

It is also possible to view the event logs of selected actions by pressing the Event Logs quick actions menu button. You will be redirected to [Event Logs](../event-log.md) filtered by specific action

<figure><img src="../.gitbook/assets/Screenshot 2024-02-06 at 18.05.06 (1).png" alt=""><figcaption><p>Action for ONU page</p></figcaption></figure>

## Add Action for ONU

To add a new Action click on the button **Add Action**. After that, you can set the Action Name, Code, Description, and ONU types on the Action form. You can use the [Macros list](macros.md) for your convenience to fill the required ONU parameters in the code field by clicking on the macros.

On the Add Action for ONU form, you can add the following preset information:&#x20;

* **Action title** - the title of the action
* **Code** - Action configuration script with Macros
* **ONU Type** - selected ONU types to which the action corresponds&#x20;
* **Description** - a detailed description of the action
* **Macros list** - select macros which will be used in the action

<figure><img src="../.gitbook/assets/Screenshot 2024-02-12 at 16.49.48.png" alt=""><figcaption><p>Create Action for ONU form</p></figcaption></figure>

## Edit Action for ONU

You can change the preset data by pressing the **Edit** button modifying the Action Name, Description, and Code with selected Macroses, and assigning ONU types.

<figure><img src="../.gitbook/assets/Screenshot 2024-02-12 at 16.49.33.png" alt=""><figcaption><p>Edit Action for ONU form</p></figcaption></figure>

## Run Actions

Actions can be run from a specific ONU page by clicking Action on the Quick Actions Bar. On the modal window, you can Apply or Cancel the action.

<figure><img src="../.gitbook/assets/Screenshot 2023-10-08 at 23.53.56.png" alt=""><figcaption><p>Custom action for ONU</p></figcaption></figure>

After the run, the action will be executed in the configuration console with the execution output. Action can be re-run by using the up key on the keyboard

<figure><img src="../.gitbook/assets/Screenshot 2024-02-12 at 16.59.41.png" alt=""><figcaption><p>Action execution information</p></figcaption></figure>

## Macros list

There is a [Macros list](macros.md) available on the right side. Macro variables can be used as the template for substituting standard parameters into a Preset configuration in the Code input field while adding or editing the preset.

<figure><img src="../.gitbook/assets/Screenshot 2024-02-06 at 17.20.11.png" alt="" width="375"><figcaption><p>Macros list</p></figcaption></figure>
