---
description: >-
  On the OLT page, you can find all the information about the device, Its main
  info, and event logs. Also, there are actions available: OLT editing, OLT and
  ONU synchronization, and deleting OLT.
---

# OLT detailed information

## Main info&#x20;

The following main information about OLT is available:

* Hostname&#x20;
* Type - [OLT type](../../easypon-information/supported-olts.md)
* Name SNMP
* SNMP port
* Telnet port
* Port ssh

## Quick Actions Panel

**Back** – back to the [OLT list](../)

**Edit** - [OLT editing](../add-olt.md#edit-olt)

**Event logs -** OLT event logs are records of activities and incidents that occur on an Optical Line Terminal (OLT) within a Passive Optical Network (PON) or similar network infrastructure. These logs are essential for network administrators and technicians to monitor, troubleshoot, and maintain the OLT and the PON network effectively. All events are logged with time stamps and information about the author of the event. Here are some common types of events that may be logged on an OLT:

* **Check connection** - when checking the connection with OLT
* **Sync all onus** - synchronizing ONU events by the Get ONU option
* **Synchronize** - OLT data synchronization
* **Create object** -creating OLT object event in the EasyPON application

**Synchronize** – OLT main data synchronization. After successful synchronization, all OLT data should be up to date.

**Get ONU** – synchronize all ONUs on the current OLT. With the help of Get ONU, it is possible to perform the synchronization process of all ONUs on the OLT Slots & Ports section. This option is available both from the Quick Actions Bar on the OLT page, in separate slots, and on individual OLT ports with an 'Up' Link Status.

**Delete OLT** - delete the OLT from the EasyPON system. OLT can be deleted by pressing the Delete button in the Quick Actions Bar section on the OLT page. To delete the OLT from the EasyPON system user confirmation is required.

<figure><img src="../../.gitbook/assets/Screenshot 2023-10-02 at 18.24.26.png" alt=""><figcaption><p>OLT page</p></figcaption></figure>

## Slots & Ports

In this panel, you can access the information about slots and ports you have on your OLT.

<figure><img src="../../.gitbook/assets/Screenshot 2023-09-28 at 22.11.08.png" alt=""><figcaption><p>Slots panel</p></figcaption></figure>

Ports are displayed in the summary table under the corresponding slot. Selecting a slot in the "Slots" section will display its ports in this section.

<details>

<summary>Port section fields:</summary>

**№** - serial number of the port&#x20;

**Registered ONU** – the number of registered ONUs on the port&#x20;

**Admin Status (On/Off)** - administrative status of the port, which can be interactively changed by a left button click.

**Link status (Up/Down)** – port connection status&#x20;

**QinQ status** - the list of QinQ ports.

**Port load** - the load on the port in the following format: registered ONUs / total port capacity - port load in percentages.&#x20;

**Get ONU button** – synchronization of all ONUs on the OLT slot and separate port.

**Migration** - plan ONU [migration](<../../Port Migration.md>) on a separate OLT port.

</details>

## Graph all ONU / Online ONU

The graph displays the number of all ONUs on the OLT relative to the ONUs that had Online status on the OLT within a time scale. It is possible to view statistics for the last 24 hours, for yesterday, for 7, 30, and 90 days ago.

Press the indicator in the legend to isolate its view on the graph or press back to select and view all data again. You can also press the Command key on Mac or Windows key on PC for multiple indicators selection and viewing them on the graph.

![Graph all ONU / Online ONU](../../.gitbook/assets/JF2kp0HIq3RrcF0bmQKoI\_image.png)

## Amount of errors by OLT in the time graph

The graph displays the number of errors on the OLT within a time scale. It is possible to view statistics for the last 24 hours, for yesterday, for 7, 30, and 90 days ago.

Press the indicator in the legend to isolate its view on the graph or press back to select and view all data again. You can also press the Command key on Mac or Windows key on PC for multiple indicators selection and viewing them on the graph.

![Amount of errors by OLT in time graph](../../.gitbook/assets/7oE5NXNEdAUS-J0VDtLmt\_image.png)
