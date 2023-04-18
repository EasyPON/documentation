---
title: OLT
slug: b1sETT8BP8N5wcSDDSTnT
createdAt: Mon Nov 14 2022 15:29:11 GMT+0000 (Coordinated Universal Time)
updatedAt: Tue Mar 07 2023 22:53:32 GMT+0000 (Coordinated Universal Time)
---

The OLT page displays information on the selected OLT and consists of several sections:

*   Quick actions panel - the quick actions panel contains quick commands that can be executed on the page or from the OLT

*   Main Info - view detailed information about the OLT

*   Slots - available slots on the OLT

*   Ports - the ports on the slot that are displayed in the summary table

*   Tasks - table showing periodic OLT tasks and their status

![OLT page](../../assets/UVSiAKo32h60hogplfM0X_image.png)

# Quick Actions Bar

*   Back – back to the OLT list

*   Edit - OLT editing

*   Synchronise – OLT main data synchronization

*   Get ONU – synchronize all ONUs on the OLT

*   Delete - delete the OLT from EasyPON system

# Main Info

*   Hostname – how the host is called

*   Type – OLT type

*   Name SNMP - the name of SNMP

*   Port SNMP - SNMP port number

*   Telnet port - Telnet port number

*   Port ssh - ssh port number

*   Button Test Connection – checking the connection to the OLT

# Slots

Available slots on OLT. Available information for each OLT slot:

*   Slot number and title

*   ONU count - the number of ONUs on the slot

*   Software - software version

*   Hardware - firmware version of the hardware

*   RAM – RAM usage percentage

*   CPU – CPU temperature

# Ports

Ports - ports on the slot, which are displayed in the summary table. When you select a slot in the Slots section, this section displays the ports for that slot.

*   № - serial number of the port

*   Registered ONU – the number of registered ONUs on the port

*   Admin Status (On/Off) - administrative status of the port

*   Link status (Up/Down) – port connection status

*   QinQ status - the list of QinQ ports

*   Port load - the load on the port in the following format "registered ONUs/total port capacity - port load in percents".

*   Get ONU button – synchronization of all ONUs on the OLT slot

# Graph all ONU / Online ONU

The graph displays the number of all ONUs on the OLT relative to the ONUs that had Online status on the OLT within a time scale. It is possible to view statistics for the last 24 hours, for yesterday, for 7, 30, and 90 days ago.

Press the indicator in the legend to isolate its view on the graph or press back to select and view all data again. You can also press the Command key on Mac or Windows key on PC for multiple indicators selection and viewing them on the graph.

![Graph all ONU / Online ONU](../../assets/JF2kp0HIq3RrcF0bmQKoI_image.png)

# Amount of errors by OLT in the time graph

The graph displays the number of errors on the OLT within a time scale. It is possible to view statistics for the last 24 hours, for yesterday, for 7, 30, and 90 days ago.

Press the indicator in the legend to isolate its view on the graph or press back to select and view all data again. You can also press the Command key on Mac or Windows key on PC for multiple indicators selection and viewing them on the graph.

![Amount of errors by OLT in time graph](../../assets/7oE5NXNEdAUS-J0VDtLmt_image.png)

