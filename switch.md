---
description: >-
  The 'All Switches' section is a central feature of the EasyPON management
  interface, designed to facilitate the monitoring and management of network
  switches.
---

# Switch

## Add Switch

The 'Add Switch' form in EasyPON is designed to facilitate the addition of new switches to your network. This manual section will guide you through each step of the process.

### Accessing the 'Add Switch' Form

To access the 'Add Switch' form:

1. Navigate to the 'All Switches' section of EasyPON.
2. Click on the 'Add Switch' button located in the Quick Access Bar at the top right of the page.

<figure><img src=".gitbook/assets/Screenshot 2023-05-04 at 15.53.18 (1).png" alt=""><figcaption><p>Add Switch form</p></figcaption></figure>

### Completing the 'Add Switch' Form

The form requires you to input detailed information for the new switch:

* **Name** - Enter a unique name for the switch to identify it within the network.
* **IP Address** - Provide the IP address assigned to the switch.
* **SNMP Read Community** - Input the community string for SNMP read access.
* **SNMP Write Community** - Input the community string for SNMP write access.
* **Port SSH** - Set the SSH port, the default is usually 22.
* **SNMP Port -** Set the SNMP port, the default is usually 161.
* **Telnet Login -** Provide the login credentials for Telnet access.
* **Telnet Password -** Enter the password for Telnet access.
* **Telnet Port -** Set the Telnet port, often set to 23.

Fields marked with an asterisk (\*) are mandatory and must be filled out to proceed.

### Testing the Connection

Before saving the new switch details, you can test the connection to ensure that all credentials and addresses are correct. Look for a test button or link, often indicated by a looped arrow icon, to verify connectivity.

### Saving the Switch

After entering all the necessary details and testing the connection:

1. Review the information for accuracy.
2. Click the 'Save' button to add the switch to your network.

### Canceling the Process

If you need to exit the form without adding the switch:

1. Click the 'Cancel' button to discard any information entered.
2. You will return to the 'All Switches' list without adding a new switch.

The 'Add Switch' form is a straightforward tool for expanding your network's capabilities within the EasyPON interface. By following the above steps, you can ensure that each new switch is correctly added and configured for remote management.

The list of connected switches in the EasyPON system is presented in the form of a Switch List table. You can connect it easily by filling in the required fields:

## All Switches

![All Switches section](<.gitbook/assets/Screenshot 2024-02-15 at 14.01.23 (1).png>)

### Quick Access Bar

Positioned on the top right of the 'All Switches' section, the Quick Access Bar offers tools for additional actions and settings. Key features include:

* **Docs -** A **l**ink to this manual article.
* **Show downloads -** A shortcut to view all the downloaded files from the system.
* **Event logs -** Provides immediate access to the log records of events on the switches.
* **Add Switch -** This button allows you to seamlessly add new switches to your network.

<figure><img src=".gitbook/assets/Screenshot 2024-02-15 at 14.01.48.png" alt=""><figcaption></figcaption></figure>

These tools are designed to enhance user experience by providing quick access to frequently used features within the EasyPON interface.

### Filter Switches

To refine the switches displayed in the switch list, use the 'Filter Switches' panel at the top of the 'All Switches' section. You can filter switches by:

* **Name -** Enter the name of the switch to find specific devices quickly.
* **IP Switch -** Input the IP address to locate switches by their network address.
* **Switch Type -** Select from a dropdown menu to filter switches based on their type or model.

Once the filters are set, you can close the filter panel to maximize screen real estate for the switch list view.

### Switch List

The 'Switch List' displays all the switches within the network in a tabular format. Essential details like the switch number, name, and IP address are listed for easy identification. Each entry has a 'View' button, enabling detailed inspection of a particular switch.  For enhanced navigability, the switch list supports pagination.&#x20;

The 'Amount' option shows the number of switches you wish to view per page. Furthermore, there's an option to export the list to an XLSX file, offering a convenient way to handle data offline or for reporting purposes. You can download all generated reports in the [Reports](Reports.md) section.

The 'All Switches' section of EasyPON provides a comprehensive overview of the network's switches. With the Quick Access Bar, filtering options, and a paginated switch list, network administrators can effectively monitor and manage their network infrastructure.

## Switch page

The 'Switch' page in the EasyPON interface allows you to manage individual switches within your network. This section of the manual covers the use of the Quick Access Bar and the Information section on the Switch page.

### Quick Access Bar

The Quick Access Bar on the 'Switch' page includes several functional icons that allow you to perform various tasks:

* **Back Arrow -** Returns you to the previous page, usually the 'All Switches' list.
* **Event Logs -** This directs you to a log of all events related to this particular switch, which is crucial for troubleshooting and monitoring purposes.
* **Synchronize -** The synchronize function enables you to update the switch's configuration and status in real-time to ensure that the data displayed is current.
* **Delete -** Delete OLT from the EasyPON system,

<figure><img src=".gitbook/assets/Screenshot 2024-02-15 at 13.20.21.png" alt=""><figcaption><p>Quick access bar of the Switch page</p></figcaption></figure>

These icons are designed to provide quick access to frequently used functions, enhancing the efficiency of switch management.

### Information

Below the Quick Access Bar, the Information section provides detailed data regarding the switch:

* **Hostname -** Shows the name assigned to the switch within the network.
* **Username -** The username used for accessing the switch, often for secure shell or web access.
* **Name SNMP -** Displays the SNMP (Simple Network Management Protocol) name for the switch, used for monitoring and management.
* **SNMP port -** The network port number assigned to SNMP traffic, typically 161.
* **Telnet port -** Reveals the port number used for Telnet access, generally set to 23.
* **Port SSH -** Indicates the port used for SSH (Secure Shell) access, commonly 22.

This section is essential for network administrators to view and manage the network settings associated with the switch.

### Ports

<details>

<summary>The block displays the list of ports on the switch in tabular form. The following information is available in the table:</summary>

* **Port -** The physical port number on the switch.
* **Name -** An assigned name or identifier for the port.
* **Admin Status -** Displays whether the port is administratively up or down.
* **Oper. Status -** Shows the current operational status of the port (whether it's actively up and transmitting data).
* **Vlans -** Lists the VLAN IDs associated with the port.
* **Type -** Indicates the port type, such as access or trunk.
* **Client MAC address -** Displays the MAC addresses of clients connected to that port.

</details>

<figure><img src=".gitbook/assets/Screenshot 2024-02-15 at 14.20.24.png" alt=""><figcaption><p>Specific Switch page</p></figcaption></figure>

This comprehensive overview allows for effective monitoring and management of individual port statuses and configurations.

You can also change the Admin Status on the switch port. Also, each port displays the client MAC addresses on which the [global search](onu-workspace/onu-search.md) works.

### Admin Status change

By clicking on the port Admin Status icon in the table, you can change the administrative status on the Switch port. Also, each port displays the client MAC addresses on which the [global search](onu-workspace/onu-search.md) works.

<figure><img src=".gitbook/assets/Screenshot 2023-05-04 at 16.04.03.png" alt="" width="375"><figcaption><p>Admin status change action on Switch port dialog</p></figcaption></figure>



### Event logs

We added an Event log button to the Switch detailed info page for your convenience. It will navigate you to the filtered [Event log page](switch.md#event-logs) by specific Switch, you would like to see changes with.

### Synchronize

By clicking the Synchronize button located in the Quick Actions Bar section on the Switch page, it is feasible to synchronize the connection and data with the existing Switch. Once the synchronization process is successful, all data related to the Switch should be current and up-to-date.

### Delete Switch

The Switch can be deleted by pressing the Delete button in the Quick Actions Bar section on the Switch page. To delete Switch from the EasyPON system user confirmation is required.

<figure><img src=".gitbook/assets/Screenshot 2023-12-19 at 09.19.19.png" alt="" width="375"><figcaption><p>Delite Switch confirmation dialog</p></figcaption></figure>

The 'Switch' page in EasyPON is a powerful interface for detailed management of each switch in your network. By utilizing the Quick Access Bar and comprehending the Information section, network administrators can efficiently oversee the functionality and performance of their network switches.
