---
description: Monitor and manage OLT
---

# Actions on the OLT

## Add OLT

The Add OLT button opens the form for creating a new OLT Create OLT. On this page, it is possible to add a new OLT to the system and check the connection with the OLT before adding it using the Test Connection button.

![Add OLT form](<../.gitbook/assets/Screenshot 2023-09-28 at 23.30.37.png>)

<details>

<summary>The Add OLT form consists of the following fields:</summary>

**OLT Name** - OLT title to identify it in the EasyPON system.

**Type OLT** - the [type](../easypon-information/supported-olts.md) of current OLT.

**IP address** - the IP address of the OLT.

**Shel** - the shelf number on the OLT.

**SNMP read community** - SNMP sequence for reading OLT statistics.

**SNMP write community** - SNMP sequence for recording OLT statistics data.

**SNMP port -** :Simple Network Management Protocol port.

**Telnet login -** username that is used to access a device via Telnet, which is a network protocol used for accessing and administering a device remotely.

**Telnet password -** along with the Telnet login, the password is the credential required to authenticate to a device when using the Telnet protocol.&#x20;

**Telnet port -** the network port that the Telnet service listens on for incoming connections. When you connect to a device using Telnet, you are essentially establishing a TCP connection to this port.

**Autosave** (On or Off) - automatic saving of the current configuration to non-volatile memory, ensuring that settings are retained after a reboot or power loss.

**Activate SSH** - activate SSH status on the OLT. It can be done only once when adding the OLT or editing it later.

**Status** - synchronization status of the OLT. If disabled all OLT periodic tasks will be postponed to the moment you enable OLT status again.

</details>

## Edit OLT

OLT data can be edited by pressing the **Edit** button in the Quick Actions Bar section on the OLT page. To edit the OLT you need to modify data fields and then **Save** the form.

## Test connection

You can also Check the connection with the existing OLT on the OLT page or before saving the OLT add/edit form results by pressing the "Test Connection" button.

<figure><img src="../.gitbook/assets/test connection.png" alt=""><figcaption><p>Test connection in complete</p></figcaption></figure>

## Migrations

{% content-ref url="../Port Migration.md" %}
[Port Migration.md](<../Port Migration.md>)
{% endcontent-ref %}

