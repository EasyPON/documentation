---
title: Macros
slug: tiJ--macros
createdAt: Tue Mar 07 2023 22:17:21 GMT+0000 (Coordinated Universal Time)
updatedAt: Tue Mar 07 2023 22:26:48 GMT+0000 (Coordinated Universal Time)
description: >-
  A list of predefined Macros variables that can be used as templates for
  substituting attributes in the Preset configuration.
---

# Macros list

While creating or editing Preset or Action, it is possible to click on a macros field with the left mouse button to add it to the Code field while editing Preset in the Preset or Action form.

Below is a macro[ variables description](macros.md#macros-variables-description) along with examples to help you understand how it works.

![Macros list on the Action edit form](<../.gitbook/assets/Screenshot 2024-02-12 at 16.49.33.png>)

<details>

<summary>What do each macros represent?</summary>

* `onu.serial_number` - serial number of the ONU
* `onu.port_interface` - ONU port interface
* `onu.qinq_free_vlan` - free qinq vlan ONU port
* `onu.onu_interface` - ONU interface
* `onu_number` - ONU number
* `onu.name` - ONU name
* `onu_type.value` - ONU type value
* `onu.mac_address` - ONU Mac address
* `onu.mac_address | split "."` - mac address of the current ONU, separated by the dot character
* `onu.mac_address | split "-"` - mac address of the current ONU, separated by the dash character
* `input_params.field_name` - field name input\_params

You can view examples of their samples in the [Macros variables description](macros.md#macros-variables-description).

</details>

### View macros info

Clicking on the view icon opposite a specific Macros opens a modal window with Macros details. The following fields are available:

* Name - Macros title
* Example - an example value
* Description - Description of Macros.

<figure><img src="../.gitbook/assets/Screenshot 2024-02-12 at 17.04.40.png" alt=""><figcaption><p>Specific macros view</p></figcaption></figure>

You can **Close** the Macros view modal window after review.

## Macros variables description

#### onu.serial\_number

The macros substitute the ONU serial number. Example:

```clike
ZTEGC1282BD3
```

#### onu.port\_interface

The number of the port on which the ONU is located is substituted. Example:

```clike
gpon-olt_1/2/16
```

#### onu.qinq\_free\_vlan

Finds a free q-in-q vlan and substitutes its number.

```clike
vlan-smart-qinq ingress-port gpon-olt_1/12/5 cvlan 1074 to 1314 svlan 150
```

Example for the rule above:

```clike
1075
```

#### onu.onu\_interface

Substitutes the name of the ONU interface. Example:

```clike
gpon-onu_1/2/16:2
```

#### onu\_number

Finds a free ONU number on the port and substitute it. For example, there is a configured port

```csharp
interface gpon-olt_1/5/3
  no shutdown
  linktrap disable
  onu 1 type universal sn ZTEGC041AF2B
  onu 1 profile line 1000mb remote standart 
  onu 3 type universal sn ZTEGC6961A2E
  onu 3 profile line 1000mb remote standart 
  onu 4 type universal sn ZTEGC0F4D2C9
  onu 4 profile line 1000mb remote standart 
```

There is no ONU with the number 2. EasyPON will determine that the number 2 is free and substitutes it in the configuration.

```clike
2 
```

#### onu\_type.value

Substitutes the type selected by the user during registration. Example:

```clike
ZTE-F660-WIFI
```

#### onu.mac\_address

Substitutes the Mac address of the ONU. Example:

```kotlin
00005e0053af
onu.mac_address | split:"."
0000.5e00.53af
onu.mac_address | split:":"
00:00:5e:00:53:af
onu.mac_address | split:"-"
00-00-5e-00-53-af
```

#### input\_params.field\_name

Request the user to input a value that will be inserted into the ONU configuration code before its registration. For example:

```clike
property description {{input_params.name}}
```

During registration, the user will be requested for the name, which will be placed while applying the `onu.name` configuration.
