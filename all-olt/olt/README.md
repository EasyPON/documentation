---
description: >-
  On the OLT page, you can find all the information about the device, Its main
  info, and event logs. Also, there are actions available: OLT editing, OLT and
  ONU synchronization, and deleting OLT.
---

# OLT information

## OLT detailed information

The detailed OLT information page contains:

* [Main info](./#main-info)
* [Quick actions bar ](./#quick-actions-bar)
* [Slots & Ports panel](./#slots-and-ports)
* [Graph all ONU / Online ONU](./#graph-all-onu-online-onu)
* [Graph of the amount of errors by OLT in the time](./#amount-of-errors-by-olt-in-the-time-graph)

<figure><img src="../../.gitbook/assets/Screenshot 2023-11-22 at 22.16.33.png" alt=""><figcaption><p>OLT page</p></figcaption></figure>

## Main info&#x20;

The following main information about OLT is available:

* **Hostname -** This refers to the unique identifier assigned to the OLT device within a network. It helps in distinguishing this device from others, especially when managing or addressing networked devices.
* **OLT Type -** This specifies the model or category of the OLT. [OLT types](../../easypon-information/supported-olts.md) vary based on their capabilities, such as the number of supported connections, power levels, and compatibility with different optical network standards.
* **Name SNMP (Simple Network Management Protocol) -** This is the identifier used within SNMP to manage and monitor the OLT. It facilitates the communication of management data between network devices and the management systems.
* **Online Status -** Indicates whether the OLT is currently active and connected to the network. An online status means the device is operational and can manage the fiber optic lines connected to it.
* **Status -** This broader term refers to its operational state, ad Active or Not Active. This option can be changed on the OLT edit form.
* **SNMP Port -** The network port used by SNMP to communicate with the OLT. This port allows for the remote configuration, monitoring, and management of the device.
* **Telnet Port -** This is the port used for Telnet access to the OLT. Telnet provides a user interface for configuring and managing the device via a command-line interface over the network.
* **Port SSH (Secure Shell)**: Similar to the Telnet port but offers a secure channel for network communication. SSH is used for securely logging into the OLT, executing commands, and transferring files.
* **Software Version -** Refers to the specific version of the firmware or software that is currently running on the OLT. This information is crucial for understanding the device's capabilities, compatibility, and any known issues or vulnerabilities.

## Quick Actions Bar

**Back** – return to the [OLT list](../)

**Edit** - open the [OLT editing](../add-olt.md#edit-olt) form.

**Periodic tasks** - view [periodic tasks](../../access-and-management/periodic-tasks.md) for the OLT.

**Event logs -** OLT event logs are records of activities and incidents that occur on an Optical Line Terminal (OLT) within a Passive Optical Network (PON) or similar network infrastructure. These logs are essential for network administrators and technicians to monitor, troubleshoot, and maintain the OLT and the PON network effectively. All events are logged with time stamps and information about the author of the event. Here are some common types of events that may be logged on an OLT:

* **Check connection** - when checking the connection with OLT
* **Sync all onus** - synchronizing ONU events by the Get ONU option
* **Synchronize** - OLT data synchronization
* **Create object** -creating OLT object event in the EasyPON application

**Synchronize** – OLT main data synchronization. After successful synchronization, all OLT data should be up to date.

**Get ONU** – synchronize all ONUs on the current OLT. With the help of Get ONU, it is possible to perform the synchronization process of all ONUs on the OLT Slots & Ports section. This option is available both from the Quick Actions Bar on the OLT page, in separate slots, and on individual OLT ports with an 'Up' Link Status.

**Delete OLT** - delete the OLT from the EasyPON system. OLT can be deleted by pressing the Delete button in the Quick Actions Bar section on the OLT page. To delete the OLT from the EasyPON system user confirmation is required.

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

By clicking the **Registered ONU** field it is possible to view the full list of ONU filtered by OLT slot and port.

## Graph all ONU / Online ONU

The graph displays the number of all ONUs on the OLT relative to the ONUs that had Online status on the OLT within a time scale. It is possible to view statistics for the last 24 hours, for yesterday, for 7, 30, and 90 days ago.

Press the indicator in the legend to isolate its view on the graph or press back to select and view all data again. You can also press the Command key on Mac or Windows key on PC for multiple indicators selection and viewing them on the graph.

![Graph all ONU / Online ONU](../../.gitbook/assets/JF2kp0HIq3RrcF0bmQKoI\_image.png)

## Amount of errors by OLT in the time graph

The graph displays the number of errors on the OLT within a time scale. It is possible to view statistics for the last 24 hours, for yesterday, for 7, 30, and 90 days ago.

Press the indicator in the legend to isolate its view on the graph or press back to select and view all data again. You can also press the Command key on Mac or Windows key on PC for multiple indicators selection and viewing them on the graph.

![Amount of errors by OLT in time graph](../../.gitbook/assets/7oE5NXNEdAUS-J0VDtLmt\_image.png)
