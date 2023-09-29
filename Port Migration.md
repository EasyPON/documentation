---
description: >-
  OLT port migration, refers to the process of moving subscribers or Optical
  Network Units (ONUs) from one port on an Optical Line Terminal (OLT) to
  another.
---

# Port Migrations

This migration can be necessary for various reasons, such as network optimization, hardware upgrades, or addressing congestion issues.

OLT port migration requires careful planning and execution to minimize service disruptions and ensure a smooth transition for subscribers. It's crucial to follow best practices and maintain clear communication with both subscribers and network operators throughout the process. EasyPON offers a user-friendly interface for such migration planning and executing at the moment you need it.

It is possible to migrate a separate port with all registered ONU cards on OLT to a different OLT port with just a few actions:

1. Choose a port for migration in the Ports section on a specific OLT page and click action Migration. A migration process will be planned for the port.
2. You will be redirected to the Migration page.
3. Reconnect the chosen OLT port to the incoming migration port and press "Finish Migration" to finish the migration process. All migrated ONU cards will be shown in the History list.

If the migration process has been planned earlier on the specific port, the action Migration icon will be changed to the link for locating planned migration.

![Migration from OLT Ports list](<.gitbook/assets/Screenshot 2023-09-28 at 23.43.27.png>)

The Migrations button can be also accessed from the [OLT workspace](all-olt/) quick action bar. All 'Planned', 'In the process', and 'Finished' port migrations can be found here.

<figure><img src=".gitbook/assets/Screenshot 2023-09-28 at 23.40.50.png" alt=""><figcaption></figcaption></figure>

## Specific migration page

The main information about this action is located on the migration page, while its history is only available after completion. You can always back to the Migrations page when required.

![Planned migration](<.gitbook/assets/Screenshot 2023-09-28 at 23.41.07.png>)
