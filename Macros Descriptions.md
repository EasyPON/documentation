---
title: Macros Descriptions
slug: Eyru-macros-descriptions
createdAt: Tue Mar 07 2023 22:17:54 GMT+0000 (Coordinated Universal Time)
updatedAt: Tue Mar 07 2023 23:06:18 GMT+0000 (Coordinated Universal Time)
---

### onu.serial\_number

The macro substitutes the ONU serial number. Example:

```clike
ZTEGC1282BD3
```

### onu.port\_interface

The number of the port on which the ONU is located is substituted. Example:

```clike
gpon-olt_1/2/16
```

### onu.qinq\_free\_vlan

Finds a free q-in-q vlan and substitutes its number.

```clike
vlan-smart-qinq ingress-port gpon-olt_1/12/5 cvlan 1074 to 1314 svlan 150
```

Example for the rule above:

```clike
1075
```

### onu.onu\_interface

Substitutes the name of the ONU interface. Example:

```clike
gpon-onu_1/2/16:2
```

### onu\_number

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

### onu\_type.value

Substitutes the type selected by the user during registration. Example:

```clike
ZTE-F660-WIFI
```

### onu.mac\_address

Substitutes the mac address of the ONU. Example:

```kotlin
00005e0053af
onu.mac_address | split:"."
0000.5e00.53af
onu.mac_address | split:":"
00:00:5e:00:53:af
onu.mac_address | split:"-"
00-00-5e-00-53-af
```

### input\_params.field\_name

Request the user to input a value that will be inserted into the ONU configuration code before its registration. For example:

```clike
property description {{input_params.name}}
```

During registration, the user will be requested for the name, which will be placed while applying the onu.name configuration.

##

