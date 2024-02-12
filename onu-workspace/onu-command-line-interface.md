---
description: >-
  Configuring an ONU is an essential task for network administrators to ensure
  proper communication between the end-users devices and the broader network
  infrastructure. The process usually involves acc
---

# ONU command line interface

**Accessing the ONU CLI** To view configuration, you need to access the ONU's CLI, which can be done by the **Configs** button in the quick access bar. After opening the output of the current ONU configuration will be shown.

**Basic Commands** The screenshot you've shared shows a set of commands available in the CLI. Here's a rundown of some common ones:

* `show_config` – This command displays the current configuration of the ONU. It’s useful for verifying changes or troubleshooting.
* `show_info -` displays detailed information about the ONU. This can include hardware specs, software version, system uptime, network interfaces, and other crucial system-related information.
* `run <last_applied_action>` - re-apply [action](../configuration-features/custom-action.md).
* `help` - view all available commands.
* `exit` – This will close the current CLI session.

<figure><img src="../.gitbook/assets/Screenshot 2024-02-12 at 17.13.11 (2).png" alt=""><figcaption><p>ONU configuration CLI</p></figcaption></figure>
