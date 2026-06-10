# CCNA Lab Notes — Cisco Packet Tracer

Hands-on study repository documenting Cisco Packet Tracer labs completed as part of CCNA (200-301) exam preparation. Each lab is saved as a `.pkt` file and corresponds to a topic from the CCNA syllabus.

## Progress

| Status | Count |
|--------|-------|
| Labs completed | 49 |
| Labs remaining | ~25 |
| Labs to redo | Lab 42 (IPv6), Lab 48 (STP) |

---

## Lab Index

| # | File | Topic |
|---|------|-------|
| 01 | `001-router-security.pkt` | Router Security — passwords, encryption |
| 02 | `002-router-security.pkt` | Router Security — enable secret |
| 03 | `003-router-security.pkt` | Router Security — review |
| 04 | `004-serial-connection.pkt` | Serial Connections — DCE/DTE, clock rate |
| 05 | `005-vlans-switches.pkt` | VLANs on Switches |
| 06 | `006-vlans-multilayer-swtiches.pkt` | VLANs on Multilayer Switches |
| 07 | `007-inter-vlan-routing.pkt` | Inter-VLAN Routing |
| 08 | `008-troubleshooting-inter-vlaning.pkt` | Troubleshooting Inter-VLAN Routing |
| 09 | `009-troubleshooting-inter-vlaning.pkt` | Troubleshooting Inter-VLAN Routing |
| 10 | `010-local-username-database.pkt` | Local Username Database |
| 11 | `011-motd-and-login-banners.pkt` | MOTD and Login Banners |
| 12 | `012-vlan-naming.pkt` | VLAN Naming |
| 13 | `013-cisco-discovery-protocol.pkt` | Cisco Discovery Protocol (CDP) |
| 14 | `014-cisco-discovery-protocol.pkt` | CDP — disable/enable |
| 15 | `015-system-configuration-dialog.pkt` | System Configuration Dialog |
| 16 | `016-loopback-interface.pkt` | Loopback Interfaces |
| 17 | `017-port-security.pkt` | Port Security |
| 18 | `018-port-security.pkt` | Port Security — sticky MAC |
| 19 | `019-port-security.pkt` | Port Security — violation actions |
| 20 | `020-configuration-review.pkt` | Configuration Review |
| 21 | `021-troubleshooting-review.pkt` | Troubleshooting Review |
| 22 | `022-telnet.pkt` | Remote Access — Telnet |
| 23 | `023-ssh.pkt` | Remote Access — SSH |
| 24 | `024-static-routing.pkt` | Static Routing |
| 25 | `025-static-routing.pkt` | Static Routing — multi-router |
| 26 | `026-static-routing-backup.pkt` | Static Routing — backup/floating routes |
| 27 | `027-dynamic-routing-rip.pkt` | Dynamic Routing — RIP |
| 28 | `028-dynamic-routing-rip.pkt` | Dynamic Routing — RIP passive interface |
| 29 | `029-standard-acls.pkt` | Standard ACLs (numbered) |
| 30 | `030-extended-acls.pkt` | Extended ACLs (numbered) |
| 31 | `031-named-acls.pkt` | Named ACLs |
| 32 | `032-ntp.pkt` | Network Time Protocol (NTP) |
| 33 | `033-ntp.pkt` | NTP — authentication |
| 34 | `034-lldp.pkt` | Link Layer Discovery Protocol (LLDP) |
| 35 | `035-dhcp.pkt` | DHCP — server configuration |
| 36 | `036-dns.pkt` | DNS |
| 37 | `037-static-nat.pkt` | NAT — Static |
| 38 | `038-dynamic-nat.pkt` | NAT — Dynamic |
| 39 | `039-pat.pkt` | NAT — PAT (overload) |
| 40 | `040-syslog.pkt` | Syslog |
| 41 | `041-pass-recovery-config-backup-os-upgrading.pkt` | Password Recovery, Config Backup, IOS Upgrade |
| 42 | `042-ipv6.pkt` | IPv6 — addressing and routing *(redo)* |
| 43 | `043-review-configuration.pkt` | Configuration Review |
| 44 | `044-review-troubleshooting.pkt` | Troubleshooting Review |
| 45 | `045-dtp.pkt` | Dynamic Trunking Protocol (DTP) |
| 46 | `046-vtp.pkt` | VLAN Trunking Protocol (VTP) |
| 47 | `047-troubleshooting-vtp.pkt` | Troubleshooting VTP |
| 48 | `048-stp.pkt` | Spanning Tree Protocol (STP) *(redo)* |
| 49 | `049-stp-election.pkt` | STP — root bridge election |

---

## Notes

### Helpers and General Tips

- Use `?` to view available options at any point in the CLI. Example: `Router(config-if)# clock rate ?`

### Cables

| Cable Type | Use Case |
|------------|----------|
| Copper Straight-Through | Connect **different** device types (e.g. PC to Switch) |
| Copper Cross-Over | Connect **same** device types (e.g. Switch to Switch) |

---

### CLI Modes

| Prompt | Mode | Capability |
|--------|------|------------|
| `Router>` | User EXEC | Monitoring commands only, no config changes |
| `Router#` | Privileged EXEC | Can run all show and config commands |
| `Router(config)#` | Global Configuration | Change device configuration |

```
Router> enable                   ! enter privileged EXEC
Router# configure terminal       ! enter global config
```

---

### View Configuration and Device Info

```
Router# show running-config
Router# show startup-config
Router(config)# do show running-config    ! run show commands from config mode
Router# show version
```

---

### Router Security

#### Passwords and Encryption

```
Router(config)# enable password <password>          ! set privileged EXEC password
Router(config)# service password-encryption         ! encrypt all plaintext passwords (type 7)
Router(config)# no enable password                  ! remove password
Router(config)# no service password-encryption      ! disable encryption for new passwords (old remain encrypted)
```

#### Enable Secret (recommended over password)

```
Router(config)# enable secret <secret>              ! encrypted password (type 5 / MD5)
```

> If both `enable password` and `enable secret` are configured, the secret takes precedence.
> Secret uses encryption type 5; password uses type 7. Secret is more secure.

#### Save Configuration

```
Router# copy running-config startup-config
Router# write
```

> Configuration is stored in RAM. You must save it to NVRAM (startup-config) to survive a reload.

---

### Console Line Configuration

```
Router(config)# line console 0
Router(config-line)# password <password>
Router(config-line)# login                          ! require authentication on console connect
```

---

### Remote Access — Telnet and SSH

#### VTY Lines (both Telnet and SSH)

```
Router(config)# line vty 0 4                        ! configure 5 simultaneous virtual connections
Router(config-line)# transport input telnet         ! allow Telnet only
Router(config-line)# transport input ssh            ! allow SSH only
Router(config-line)# exec-timeout <minutes>         ! auto-disconnect after X minutes of inactivity
```

> Switches are Layer 2 devices. To reach a switch via Telnet/SSH, you must configure a VLAN interface with an IP address:
> ```
> Switch(config)# interface vlan 1
> Switch(config-if)# ip address 192.168.1.1 255.255.255.0
> Switch(config-if)# no shutdown
> ```

#### SSH Setup

SSH requires a hostname, domain name, and RSA keys before it can be used.

```
Router(config)# hostname <name>
Router(config)# ip domain name cisco.com
Router(config)# crypto key generate rsa general-keys modulus 1024
Router(config)# ip ssh version 2
Router(config)# username <user> privilege 15 secret <password>
Router(config-line)# login local
```

```
C:\> ssh -l <username> <ip_address>                 ! connect from a PC
```

---

### Local Username Database

```
Router# username <user> password <password>         ! add user to local database
Router(config-line)# login local                    ! require local authentication
```

> Passwords are case-sensitive. Usernames are NOT case-sensitive.
> If both `ccna` and `CCNA` exist, the last one created overrides the first.

---

### Banners

```
Router(config)# banner motd '<message>'             ! displayed to all users connecting
Router(config)# banner login '<message>'            ! displayed before login prompt
```

> The character wrapping the message (e.g. `'`) is the delimiter — it marks the start and end of the message.

---

### Interface Configuration

```
Router(config)# interface <interface>                         ! single interface
Router(config)# interface range fa0/1 - 4                    ! range of interfaces
Router(config-if)# ip address <ip_address> <subnet_mask>
Router(config-if)# no shutdown                               ! enable interface
```

#### View Interface Status

```
Router# show ip interface brief
Router# show ip interface
Router# show interface <interface>
```

---

### Serial Connections

| Term | Meaning |
|------|---------|
| DCE | Data Communications Equipment — supplies the clock signal |
| DTE | Data Terminal Equipment — receives the clock signal |

```
Router# show controllers <interface>               ! identify DCE or DTE side
Router(config-if)# clock rate <bits_per_second>   ! set on DCE side only
```

---

### VLANs on Switches

```
Switch# show vlan
Switch(config)# vlan <number>
Switch(config-vlan)# name <name>
```

#### Access Ports (one VLAN per port)

```
Switch(config-if)# switchport mode access
Switch(config-if)# switchport access vlan <number>
```

#### Trunk Ports (carry traffic from multiple VLANs)

```
Switch(config-if)# switchport mode trunk
Switch(config-if)# switchport trunk allowed vlan <number,number,...>
Switch(config-if)# switchport trunk allowed vlan add <number>
Switch(config-if)# switchport trunk allowed vlan remove <number>
Switch(config-if)# switchport trunk allowed vlan all
Switch(config-if)# switchport trunk allowed vlan none
Switch(config-if)# switchport trunk allowed vlan except <number>
```

---

### VLANs on Multilayer Switches

Multilayer switches support two trunk encapsulation types: `dot1q` (industry standard) and `isl` (Cisco proprietary). You must set encapsulation before setting trunk mode.

```
Switch(config-if)# switchport trunk encapsulation dot1q
Switch(config-if)# switchport mode trunk
```

---

### Inter-VLAN Routing

Uses subinterfaces on a router (Router-on-a-Stick).

```
Router(config)# interface <interface>.<vlan_number>       ! create subinterface
Router(config-subif)# encapsulation dot1q <vlan_number>   ! tag subinterface with VLAN
Router(config-subif)# ip address <address> <subnet_mask>  ! set gateway for that VLAN
```

#### Troubleshooting

```
Router# show interfaces trunk
Router# show interface <interface>
Router(config)# no vlan <vlan_number>              ! delete a VLAN
C:\> ipconfig /all                                 ! check host config
```

---

### Dynamic Trunking Protocol (DTP)

DTP can automatically negotiate trunk or access mode between switches. Disable it for security.

```
Switch(config-if)# switchport mode trunk           ! set mode manually first
Switch(config-if)# switchport nonegotiate          ! disable DTP on this port
```

---

### VLAN Trunking Protocol (VTP)

Propagates VLAN configuration across switches in the same VTP domain.

| Mode | Behaviour |
|------|-----------|
| Server (default) | Creates, deletes, and advertises VLANs |
| Client | Syncs from server, cannot create/delete VLANs |
| Transparent | Does not sync, but forwards VTP messages |

```
Switch(config)# vtp mode <server|client|transparent>
Switch(config)# vtp domain <domain_name>
Switch(config)# vtp version <version>
```

> A switch with a null (default) VTP domain will automatically join the domain of any VTP message it receives — be careful.

---

### Spanning Tree Protocol (STP)

Prevents Layer 2 loops by blocking redundant paths.

#### Key Concepts

- **Bridge ID** = Priority (default 32768) + MAC address. Lowest Bridge ID becomes the **Root Bridge**.
- All ports on the root bridge are **designated**.
- Non-root switches select the port with the **lowest cost** to the root as their **root port**.
- Remaining ports become **designated** or **blocked**.

| Interface Type | Default STP Cost |
|----------------|-----------------|
| GigabitEthernet | 4 |
| FastEthernet | 19 |

```
Switch# show spanning-tree
Switch# show spanning-tree summary
Switch(config)# spanning-tree mode rapid-pvst
```

#### Influence Root Bridge Election

```
SW2(config)# spanning-tree vlan 20 root primary     ! force this switch to be root for VLAN 20
SW2(config)# spanning-tree vlan 10 root secondary   ! make this switch secondary root for VLAN 10
```

#### PortFast and BPDU Guard

```
SW2(config)# spanning-tree portfast bpduguard default     ! enable on all access ports globally
SW2(config-if)# spanning-tree portfast                    ! enable on specific interface
SW2(config-if)# spanning-tree bpduguard enable            ! enable bpduguard on specific interface
```

---

### Port Security

Port security restricts which MAC addresses can communicate on a switch port. Only available on non-dynamic (statically assigned) ports.

```
Switch# show mac address-table
Switch# show interfaces <interface> switchport
Switch(config-if)# switchport mode access
Switch(config-if)# switchport port-security                        ! enable port security (default max: 1 MAC)
Switch(config-if)# switchport port-security maximum <number>       ! set max allowed MACs
Switch(config-if)# switchport port-security mac-address <mac>      ! manually allow a MAC
Switch(config-if)# switchport port-security mac-address sticky     ! dynamically learn and save MACs
Switch(config-if)# switchport port-security violation <action>     ! protect | restrict | shutdown
Switch# show port-security
Switch# show port-security address
```

#### Violation Actions

| Action | Drops Traffic | Shuts Port | Message | Counter |
|--------|--------------|------------|---------|---------|
| Protect | Yes | No | No | No |
| Restrict | Yes | No | Yes | Yes |
| Shutdown (default) | Yes | Yes | — | Yes |

To recover from err-disabled state:
```
Switch(config-if)# shutdown
Switch(config-if)# no shutdown
```

---

### CDP — Cisco Discovery Protocol

CDP is a Cisco-proprietary Layer 2 protocol that discovers directly connected Cisco devices.

```
Router# show cdp
Router# show cdp neighbors
Router# show cdp neighbors detail
Router# show cdp entry <hostname>
Router(config)# no cdp run                    ! disable globally
Router(config)# cdp run                       ! enable globally
Router(config-if)# no cdp enable              ! disable on interface
Router(config-if)# cdp enable                 ! enable on interface
```

---

### LLDP — Link Layer Discovery Protocol

Vendor-neutral alternative to CDP (IEEE 802.1AB).

```
Device(config)# no cdp run
Device(config)# lldp run
Device# show lldp
Device# show lldp neighbors
Device# show lldp neighbors detail
Device(config-if)# no lldp transmit           ! disable sending on interface (e.g. toward endpoints)
Device(config-if)# no lldp receive            ! disable receiving on interface
```

> Default: advertisements every 30s, hold time 120s, reinitialisation delay 2s.

---

### Loopback Interfaces

Virtual interfaces that are always up. Best practice: use a /32 host mask.

```
Router(config)# interface loopback <id>
Router(config-if)# ip address <ip> 255.255.255.255
Router(config)# no interface loopback <id>    ! remove loopback
```

---

### Static Routing

```
Router(config)# ip route <dest_network> <dest_mask> <next_hop_ip>
Router(config)# ip route <dest_network> <dest_mask> <exit_interface>
```

#### Administrative Distance (AD)

| Route Type | AD |
|------------|----|
| Connected interface | 0 |
| Static route | 1 |
| RIP | 120 |

When multiple paths exist, the router prefers the **lowest AD**. Equal AD → compare **metric** (e.g. hop count for RIP).

#### Floating Static Route (Backup)

Set the static route's AD one higher than the primary path's AD so it is only used when the primary fails.

```
Router(config)# ip route <dest> <mask> <next_hop> <administrative_distance>
```

---

### Dynamic Routing — RIP

```
Router(config)# router rip
Router(config-router)# version 2
Router(config-router)# no auto-summary              ! advertise subnets, not classful networks
Router(config-router)# network <network_address>    ! enable RIP on interfaces in this network
Router(config-router)# passive-interface <iface>    ! listen only, do not send updates (e.g. toward hosts)
Router# show ip protocols
```

> RIPv1 always has auto-summary enabled and cannot disable it. RIPv2 can disable it.
> A **passive interface** receives route advertisements but does not send them.

---

### Access Control Lists (ACLs)

#### Types

| Type | Number Range | Filters On | Best Placed |
|------|-------------|------------|-------------|
| Standard | 1–99 | Source IP only | Close to **destination** |
| Extended | 100–199 | Source + Destination IP, protocol, port | Close to **source** |

> ACLs have an **implicit deny all** at the bottom. Always add a `permit any` if you only want to deny specific traffic.

#### Standard Numbered ACL

```
Router(config)# access-list <1-99> <permit|deny|remark> <ip|host|any> <wildcard_mask>
Router(config-if)# ip access-group <acl_number> <in|out>
```

#### Extended Numbered ACL

```
Router(config)# access-list 100 permit ip host 192.168.1.11 host 192.168.3.100
Router(config-if)# ip access-group 100 in
```

#### Named ACL

```
Router(config)# ip access-list <standard|extended> <name>
Router(config-std-nacl)# deny <ip> <wildcard_mask>
Router(config-std-nacl)# permit any
```

---

### NTP — Network Time Protocol

```
Router# show clock
Router# show clock detail
Router(config)# clock timezone <timezone> <hour_offset> <minute_offset>
Router# clock set <hh:mm:ss> <month> <day> <year>
```

#### NTP Server

```
Router(config)# ntp master <stratum>              ! lower stratum = more authoritative
```

#### NTP Client

```
Router(config)# ntp server <server_ip>
Router# show ntp associations
```

#### NTP Authentication

```
Router(config)# ntp authenticate
Router(config)# ntp authentication-key <key_number> md5 <key>
Router(config)# ntp trusted-key <key_number>
Router(config)# ntp server <server_ip> key <key_number>
```

> All devices must have: timezone set, authentication enabled, same key created and trusted. NTP only syncs the clock.

---

### DHCP

```
Router(config)# ip dhcp pool <pool_name>
Router(dhcp-config)# network <network_address> <mask>
Router(dhcp-config)# default-router <gateway_ip>
Router(dhcp-config)# dns-server <dns_ip>
Router(config)# ip dhcp excluded-address <first_ip> <last_ip>
Router(config-if)# ip address dhcp                    ! configure interface as DHCP client
```

#### DHCP Relay Agent

Used when hosts and the DHCP server are on different networks. Configure on the Layer 3 interface closest to the hosts.

```
Router(config-if)# ip helper-address <dhcp_server_ip>
```

> Hosts send DHCP broadcasts. The relay agent forwards them as unicast to the DHCP server.
> If DHCP fails, the host falls back to an APIPA address (169.254.0.0/16).

```
C:\> ipconfig /release
C:\> ipconfig /renew
```

---

### DNS

```
Switch(config)# ip default-gateway <gateway_ip>
Switch(config)# ip name-server <dns_server_ip>
```

---

### NAT — Network Address Translation

#### Static NAT (1:1 mapping)

```
Router(config-if)# ip nat inside
Router(config-if)# ip nat outside
Router(config)# ip nat inside source static <inside_local_ip> <inside_global_ip>
```

#### Dynamic NAT (pool of public IPs)

```
Router(config-if)# ip nat inside
Router(config-if)# ip nat outside
Router(config)# access-list 1 permit 192.168.1.0 0.0.0.255
Router(config)# ip nat pool pool1 1.2.3.10 1.2.3.20 netmask 255.255.255.0
Router(config)# ip nat inside source list 1 pool pool1
Router# show ip nat translations
Router# clear ip nat translation *
```

#### PAT — Port Address Translation (many-to-one)

```
Router(config)# access-list 1 permit 192.168.1.0 0.0.0.255
Router(config)# ip nat inside source list 1 interface <exit_interface> overload
```

---

### Syslog

```
Router(config)# service timestamps log datetime msec     ! add timestamps to messages
Router# terminal monitor                                  ! show syslog over vty lines
Router(config-line)# logging synchronous                 ! reprint command after syslog interrupts
Router(config)# logging buffered                         ! log to buffer (RAM)
Router(config)# logging buffered <size>                  ! set buffer size (default 4096)
Router# show logging
Router(config)# logging <server_ip>                      ! send logs to syslog server
Router(config)# logging host <server_ip>
```

> Syslog has 8 severity levels (0–7). Logs in RAM are lost on reload.

---

### Password Recovery, Config Backup, IOS Upgrade

#### Password Recovery

```
! 1. Power cycle the device, press Ctrl+C (or Cmd+C) to enter ROMMON
rommon 1> confreg 0x2142        ! skip startup-config on boot
rommon 1> reset
! 2. After reload, copy startup to running
Router# copy startup-config running-config
! 3. Change the password
Router(config)# enable secret <new_secret>
! 4. Restore normal boot behaviour
Router(config)# config-register 0x2102
! 5. Save
Router# write
```

#### Config Backup and IOS Upgrade

```
Router# copy startup-config tftp                ! backup config to TFTP
Router# copy tftp flash                         ! download new IOS image from TFTP
Router# show flash                              ! view flash contents
Router# delete flash:<filename>                 ! delete old IOS image
```

---

### IPv6

```
Router(config)# ipv6 unicast-routing
Router(config-if)# ipv6 address <ipv6_address>/<prefix_length>
Router(config-if)# ipv6 address autoconfig     ! enable SLAAC on the interface
Router# show ipv6 interface brief
Router(config)# ipv6 route <network_prefix> <gateway_address>
```

> Every IPv6-enabled interface automatically gets a **link-local address** (FE80::/10). These are non-routable.
> **SLAAC** generates a global IPv6 address by combining the network prefix with the device's MAC address, using the Neighbor Discovery Protocol.

---

### Troubleshooting Methodology

1. **Confirm** the problem
2. **Identify** and fix the misconfiguration
3. **Test** the new configuration
4. **Save** the configuration

---

## Topics Remaining (~25 labs)

Based on the CCNA 200-301 exam syllabus, the likely remaining topics include:

- OSPF (single-area and multi-area)
- EtherChannel (LACP / PAgP)
- FHRP — HSRP / VRRP
- Wireless LAN configuration
- IPv6 routing
- Network automation and programmability (REST APIs, JSON, Python basics)
- QoS fundamentals
- SD-WAN / SD-Access concepts

---

## Tools Used

- [Cisco Packet Tracer 9.0.0](https://www.netacad.com/courses/packet-tracer)
- Course: Jeremy's IT Lab — CCNA 200-301 Full Course (YouTube / Udemy)

---

*CCNA 200-301 certification exam in progress.*
