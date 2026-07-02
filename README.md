# CCNA Lab Notes — Cisco Packet Tracer

Hands-on study repository documenting Cisco Packet Tracer labs completed as part of CCNA (200-301) exam preparation. Each lab is saved as a `.pkt` file and corresponds to a topic from the CCNA syllabus.

## Progress

| Status         | Count                       |
| -------------- | --------------------------- |
| Labs completed | 56                          |
| Labs remaining | ~18                         |
| Labs to redo   | Lab 42 (IPv6), Lab 48 (STP) |

---

## Lab Index

| #   | File                                               | Topic                                         |
| --- | -------------------------------------------------- | --------------------------------------------- |
| 01  | `001-router-security.pkt`                          | Router Security — passwords, encryption       |
| 02  | `002-router-security.pkt`                          | Router Security — enable secret               |
| 03  | `003-router-security.pkt`                          | Router Security — review                      |
| 04  | `004-serial-connection.pkt`                        | Serial Connections — DCE/DTE, clock rate      |
| 05  | `005-vlans-switches.pkt`                           | VLANs on Switches                             |
| 06  | `006-vlans-multilayer-swtiches.pkt`                | VLANs on Multilayer Switches                  |
| 07  | `007-inter-vlan-routing.pkt`                       | Inter-VLAN Routing                            |
| 08  | `008-troubleshooting-inter-vlaning.pkt`            | Troubleshooting Inter-VLAN Routing            |
| 09  | `009-troubleshooting-inter-vlaning.pkt`            | Troubleshooting Inter-VLAN Routing            |
| 10  | `010-local-username-database.pkt`                  | Local Username Database                       |
| 11  | `011-motd-and-login-banners.pkt`                   | MOTD and Login Banners                        |
| 12  | `012-vlan-naming.pkt`                              | VLAN Naming                                   |
| 13  | `013-cisco-discovery-protocol.pkt`                 | Cisco Discovery Protocol (CDP)                |
| 14  | `014-cisco-discovery-protocol.pkt`                 | CDP — disable/enable                          |
| 15  | `015-system-configuration-dialog.pkt`              | System Configuration Dialog                   |
| 16  | `016-loopback-interface.pkt`                       | Loopback Interfaces                           |
| 17  | `017-port-security.pkt`                            | Port Security                                 |
| 18  | `018-port-security.pkt`                            | Port Security — sticky MAC                    |
| 19  | `019-port-security.pkt`                            | Port Security — violation actions             |
| 20  | `020-configuration-review.pkt`                     | Configuration Review                          |
| 21  | `021-troubleshooting-review.pkt`                   | Troubleshooting Review                        |
| 22  | `022-telnet.pkt`                                   | Remote Access — Telnet                        |
| 23  | `023-ssh.pkt`                                      | Remote Access — SSH                           |
| 24  | `024-static-routing.pkt`                           | Static Routing                                |
| 25  | `025-static-routing.pkt`                           | Static Routing — multi-router                 |
| 26  | `026-static-routing-backup.pkt`                    | Static Routing — backup/floating routes       |
| 27  | `027-dynamic-routing-rip.pkt`                      | Dynamic Routing — RIP                         |
| 28  | `028-dynamic-routing-rip.pkt`                      | Dynamic Routing — RIP passive interface       |
| 29  | `029-standard-acls.pkt`                            | Standard ACLs (numbered)                      |
| 30  | `030-extended-acls.pkt`                            | Extended ACLs (numbered)                      |
| 31  | `031-named-acls.pkt`                               | Named ACLs                                    |
| 32  | `032-ntp.pkt`                                      | Network Time Protocol (NTP)                   |
| 33  | `033-ntp.pkt`                                      | NTP — authentication                          |
| 34  | `034-lldp.pkt`                                     | Link Layer Discovery Protocol (LLDP)          |
| 35  | `035-dhcp.pkt`                                     | DHCP — server configuration                   |
| 36  | `036-dns.pkt`                                      | DNS                                           |
| 37  | `037-static-nat.pkt`                               | NAT — Static                                  |
| 38  | `038-dynamic-nat.pkt`                              | NAT — Dynamic                                 |
| 39  | `039-pat.pkt`                                      | NAT — PAT (overload)                          |
| 40  | `040-syslog.pkt`                                   | Syslog                                        |
| 41  | `041-pass-recovery-config-backup-os-upgrading.pkt` | Password Recovery, Config Backup, IOS Upgrade |
| 42  | `042-ipv6.pkt`                                     | IPv6 — addressing and routing _(redo)_        |
| 43  | `043-review-configuration.pkt`                     | Configuration Review                          |
| 44  | `044-review-troubleshooting.pkt`                   | Troubleshooting Review                        |
| 45  | `045-dtp.pkt`                                      | Dynamic Trunking Protocol (DTP)               |
| 46  | `046-vtp.pkt`                                      | VLAN Trunking Protocol (VTP)                  |
| 47  | `047-troubleshooting-vtp.pkt`                      | Troubleshooting VTP                           |
| 48  | `048-stp.pkt`                                      | Spanning Tree Protocol (STP) _(redo)_         |
| 49  | `049-stp-election.pkt`                             | STP — root bridge election                    |
| 50  | `050-etherchannel.pkt`                             | EtherChannel — LACP / PAgP / Static           |
| 51  | `051-troubleshooting-etherchannel.pkt`             | Troubleshooting EtherChannel                  |
| 52  | `052-intervlan-routing.pkt`                        | Inter-VLAN Routing — review                   |
| 53  | `053-troubleshooting-intervlan-routing.pkt`        | Troubleshooting Inter-VLAN Routing — review   |
| —   | `extra-configuring-stp.pkt`                        | STP configuration (extra)                     |
| —   | `extra-rapid-stp.pkt`                              | Rapid STP configuration (extra)               |
| —   | `extra-etherchannel-configuration.pkt`             | EtherChannel — Layer 3 configuration (extra)  |
| 58  | `058-eigrp-configuration.pkt`                      | EIGRP — configuration                         |
| 59  | `059-eigrp-troubleshooting.pkt`                    | Troubleshooting EIGRP                         |
| 60  | `060-ipv6-eigrp-configuration.pkt`                 | IPv6 EIGRP — configuration                    |
| —   | `extra-eigrp-configuration.pkt`                    | EIGRP — unequal-cost load balancing (extra)   |

---

## Notes

### Helpers and General Tips

- Use `?` to view available options at any point in the CLI. Example: `Router(config-if)# clock rate ?`

### Cables

| Cable Type              | Use Case                                               |
| ----------------------- | ------------------------------------------------------ |
| Copper Straight-Through | Connect **different** device types (e.g. PC to Switch) |
| Copper Cross-Over       | Connect **same** device types (e.g. Switch to Switch)  |

---

### CLI Modes

| Prompt            | Mode                 | Capability                                  |
| ----------------- | -------------------- | ------------------------------------------- |
| `Router>`         | User EXEC            | Monitoring commands only, no config changes |
| `Router#`         | Privileged EXEC      | Can run all show and config commands        |
| `Router(config)#` | Global Configuration | Change device configuration                 |

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
>
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

| Term | Meaning                                                   |
| ---- | --------------------------------------------------------- |
| DCE  | Data Communications Equipment — supplies the clock signal |
| DTE  | Data Terminal Equipment — receives the clock signal       |

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

| Mode             | Behaviour                                     |
| ---------------- | --------------------------------------------- |
| Server (default) | Creates, deletes, and advertises VLANs        |
| Client           | Syncs from server, cannot create/delete VLANs |
| Transparent      | Does not sync, but forwards VTP messages      |

```
Switch(config)# vtp mode <server|client|transparent>
Switch(config)# vtp domain <domain_name>
Switch(config)# vtp version <version>
```

> A switch with a null (default) VTP domain will automatically join the domain of any VTP message it receives — be careful.

---

### Spanning Tree Protocol (STP)

Layer 2 protocol that prevents loops by placing redundant ports in a blocking state, creating a single loop-free path through the network. Runs on all switches by default.

#### Bridge ID and Root Bridge Election

- **Bridge ID** = Bridge Priority (default 32768) + MAC address — lowest Bridge ID wins
- Modern (PVST+) Bridge ID splits the priority field: 4-bit priority + 12-bit Extended System ID (= VLAN ID)
- Bridge priority can only be changed in multiples of **4096** (the remaining 12 bits are fixed to the VLAN ID)
- Default priority per VLAN = 32768 + VLAN number (e.g. VLAN 1 → 32769)
- All ports on the root bridge are **designated (forwarding)**
- Tie-breaking order: (1) lowest root cost → (2) lowest neighbor bridge ID → (3) lowest neighbor port ID
- Switches send Hello BPDUs every **2 seconds** by default; receiving one on an interface means it is connected to another switch
- BPDU frames use destination MAC **01:00:0c:cc:cc:cd**
- In classic STP only the root bridge originates BPDUs; all other switches relay the root's BPDUs

#### STP Port Roles

| Role            | Description                                            |
| --------------- | ------------------------------------------------------ |
| Root Port       | Best path toward root bridge (one per non-root switch) |
| Designated Port | Forwarding port on each network segment                |
| Non-Designated  | Blocking port — backup path                            |

#### STP Port States (Classic STP / PVST+)

| State      | Send BPDUs | Receive BPDUs | Forward Traffic | Learn MACs | Type                |
| ---------- | ---------- | ------------- | --------------- | ---------- | ------------------- |
| Blocking   | No         | Yes           | No              | No         | Stable              |
| Listening  | Yes        | Yes           | No              | No         | Transitional (15 s) |
| Learning   | Yes        | Yes           | No              | Yes        | Transitional (15 s) |
| Forwarding | Yes        | Yes           | Yes             | Yes        | Stable              |
| Disabled   | No         | No            | No              | No         | Stable              |

> Convergence from blocking → forwarding = **50 seconds** (20 s Max Age + 15 s Listening + 15 s Learning).
> A port can move from forwarding → blocking **instantly**.

#### RSTP Port States

| State      | Send BPDUs | Receive BPDUs | Forward Traffic | Learn MACs | Type         |
| ---------- | ---------- | ------------- | --------------- | ---------- | ------------ |
| Discarding | No         | Yes           | No              | No         | Stable       |
| Learning   | Yes        | Yes           | No              | Yes        | Transitional |
| Forwarding | Yes        | Yes           | Yes             | Yes        | Stable       |

#### STP Versions

| Version                   | VLANs                         | Encapsulation | Notes                            |
| ------------------------- | ----------------------------- | ------------- | -------------------------------- |
| STP (802.1D)              | Single instance for all VLANs | —             | Original standard                |
| PVST                      | One instance per VLAN         | ISL only      | Cisco proprietary                |
| PVST+                     | One instance per VLAN         | ISL + dot1Q   | Default on older Cisco switches  |
| Rapid STP (RSTP / 802.1w) | Single instance for all VLANs | —             | Much faster convergence          |
| Rapid PVST+               | One instance per VLAN         | ISL + dot1Q   | Default on modern Cisco switches |
| MST (802.1s)              | Groups VLANs into instances   | —             | Uses RSTP mechanics              |

#### STP / RSTP Port Cost

| Speed    | STP Cost | RSTP Cost |
| -------- | -------- | --------- |
| 10 Mb/s  | 100      | 2,000,000 |
| 100 Mb/s | 19       | 200,000   |
| 1 Gb/s   | 4        | 20,000    |
| 10 Gb/s  | 2        | 2,000     |
| 100 Gb/s | 1        | 200       |
| 1 Tb/s   | 1        | 20        |

#### RSTP Specific Behaviour

- RSTP uses a **handshake mechanism** instead of timers for faster convergence
- A switch considers a neighbour lost after **3 missed BPDUs** (~6 s) instead of the 20 s Max Age timer
- All switches originate their own BPDUs from designated ports (classic STP: only root originates)
- Non-designated port role is split into **Alternate** (backup root port, receives superior BPDUs from another switch) and **Backup** (backup designated port, seen only when two interfaces share the same collision domain via a hub — the port with the lower port ID becomes designated, the other becomes Backup)
- Backwards compatible: ports connected to classic STP switches fall back to classic STP behaviour
- UplinkFast, BackboneFast, and PortFast are built into RSTP — they do not need to be configured separately

#### RSTP BPDU Differences vs Classic STP

| Field            | Classic STP | RSTP            |
| ---------------- | ----------- | --------------- |
| Protocol version | 0           | 2               |
| BPDU type        | 0           | 2               |
| Flags field      | Bits 1 & 8  | All 8 bits used |

| RSTP Link Type | Definition                                                                    |
| -------------- | ----------------------------------------------------------------------------- |
| Edge           | Connected to an end host — moves directly to forwarding (PortFast equivalent) |
| Point-to-Point | Full-duplex link between two switches                                         |
| Shared         | Half-duplex link to a hub                                                     |

```
Switch(config-if)# spanning-tree portfast                      ! configure edge port
Switch(config-if)# spanning-tree link-type point-to-point      ! configure P2P link
Switch(config-if)# spanning-tree link-type shared              ! configure shared link
```

#### Verification

```
Switch# show spanning-tree
Switch# show spanning-tree vlan <vlan-id>
Switch# show spanning-tree summary
Switch# show errdisable recovery
```

#### STP Mode and Root Bridge Influence

```
Switch(config)# spanning-tree mode rapid-pvst                  ! enable Rapid PVST+
Switch(config)# spanning-tree vlan <id> root primary           ! force this switch to become root
Switch(config)# spanning-tree vlan <id> root secondary         ! set this switch as secondary root
Switch(config)# spanning-tree vlan <id> priority <value>       ! set priority manually (multiples of 4096)
```

#### STP Toolkit

**PortFast** — lets an access port skip Listening/Learning and go directly to Forwarding. Only use on ports connected to end hosts, never on trunk or switch-connected ports.

```
Switch(config)# spanning-tree portfast default                 ! enable PortFast on all access ports globally
Switch(config-if)# spanning-tree portfast                      ! enable PortFast on a specific interface
Switch(config-if)# spanning-tree portfast trunk                ! enable PortFast on a trunk interface (rare)
```

**BPDU Guard** — shuts the port (err-disabled) if a BPDU is received. Protects PortFast ports from accidentally connecting to another switch.

```
Switch(config)# spanning-tree portfast bpduguard default       ! enable BPDU Guard on all PortFast ports globally
Switch(config-if)# spanning-tree bpduguard enable              ! enable BPDU Guard on a specific interface
```

> BPDU Guard causes **err-disabled** state. Even with BPDU Guard enabled, the port still _sends_ BPDUs.

**BPDU Filter** — prevents a port from sending BPDUs. Two behaviours depending on where it is configured:

```
Switch(config)# spanning-tree portfast bpdufilter default      ! globally: if a BPDU is received, PortFast/filter
                                                               !   are disabled and port runs normal STP (recommended)
Switch(config-if)# spanning-tree bpdufilter enable             ! per-interface: stops sending AND ignores received
                                                               !   BPDUs — effectively disables STP on port (dangerous)
Switch(config-if)# spanning-tree bpdufilter disable            ! disable BPDU Filter on interface
```

**Root Guard** — prevents a port from becoming a Root Port. If a superior BPDU is received, the port enters **root-inconsistent** state (not err-disabled) and stops forwarding until the superior BPDUs stop.

**Loop Guard** — if an interface stops receiving BPDUs, it enters **err-disabled** state instead of transitioning to forwarding, preventing accidental loops caused by a unidirectional link failure.

#### Error Disable Recovery

```
Switch# show errdisable recovery                               ! view recovery status and timers
Switch(config)# errdisable recovery cause bpduguard            ! auto-recover ports disabled by BPDU Guard
Switch(config)# errdisable recovery interval <seconds>         ! set recovery timer (default 300 s)
```

> To manually recover: fix the root cause, then `shutdown` followed by `no shutdown` on the interface.

---

### EtherChannel

Groups multiple physical interfaces into a single logical interface (also called **Port Channel** or **Link Aggregation Group / LAG**). STP sees only one logical link, so no ports are blocked. Provides both increased bandwidth (load-balanced across physical links) and redundancy (if one link fails, the others keep forwarding).

> Multiple connections between two switches without EtherChannel cause STP to block all but one, so the bandwidth problem persists despite extra cables.

#### Load Balancing

EtherChannel load-balances per **flow** — frames belonging to the same source/destination pair always use the same physical link. The algorithm can be based on:

- Source MAC / Destination MAC / Source + Destination MAC
- Source IP / Destination IP / Source + Destination IP

```
Switch# show etherchannel load-balance
Switch(config)# port-channel load-balance <method>     ! e.g. src-dst-mac
```

#### Negotiation Protocols

| Protocol | Standard          | Modes                 | Forms EtherChannel |
| -------- | ----------------- | --------------------- | ------------------ |
| PAgP     | Cisco proprietary | desirable + desirable | Yes                |
| PAgP     | Cisco proprietary | desirable + auto      | Yes                |
| PAgP     | Cisco proprietary | auto + auto           | No                 |
| LACP     | IEEE 802.3ad      | active + active       | Yes                |
| LACP     | IEEE 802.3ad      | active + passive      | Yes                |
| LACP     | IEEE 802.3ad      | passive + passive     | No                 |
| Static   | —                 | on + on               | Yes                |

> Maximum **8 active** interfaces per EtherChannel. LACP supports up to 16 configured (8 active + 8 standby). Static `on` mode only works with `on` on the other side.

#### Configuration

```
Switch(config-if-range)# channel-group <nr> mode <mode>   ! desirable / auto / active / passive / on
Switch(config-if-range)# channel-protocol <pagp|lacp>     ! optional — force protocol
Switch(config)# interface port-channel <nr>               ! enter logical interface to configure
```

Member interfaces must have matching configuration — mismatched ports are excluded from the bundle:

- Same duplex and speed
- Same switchport mode (access or trunk)
- Same allowed VLANs and native VLAN (trunk only)

> The channel-group number must match across member interfaces on the **same** switch, but does not need to match the number on the other switch.

#### Layer 3 EtherChannel

Use multilayer switches. Remove the switchport, then configure an IP on the port-channel interface.

```
Switch(config-if-range)# no switchport
Switch(config-if-range)# channel-group 1 mode active
Switch(config)# interface port-channel 1
Switch(config-if)# ip address 10.0.0.1 255.255.255.252
```

#### Verification

```
Switch# show etherchannel summary
Switch# show etherchannel port-channel
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

| Action             | Drops Traffic | Shuts Port | Message | Counter |
| ------------------ | ------------- | ---------- | ------- | ------- |
| Protect            | Yes           | No         | No      | No      |
| Restrict           | Yes           | No         | Yes     | Yes     |
| Shutdown (default) | Yes           | Yes        | —       | Yes     |

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

| Route Type          | AD  |
| ------------------- | --- |
| Connected interface | 0   |
| Static route        | 1   |
| EIGRP (internal)    | 90  |
| RIP                 | 120 |
| EIGRP (external)    | 170 |

When multiple paths exist, the router prefers the **lowest AD**. Equal AD → compare **metric** (e.g. hop count for RIP).

#### Floating Static Route (Backup)

Set the static route's AD one higher than the primary path's AD so it is only used when the primary fails.

```
Router(config)# ip route <dest> <mask> <next_hop> <administrative_distance>
```

---

### Dynamic Routing — RIP

- **Type**: Distance Vector, Interior Gateway Protocol (IGP)
- **Metric**: hop count — one hop = one router; bandwidth is irrelevant
- **Max hops**: 15 — destinations beyond that are considered unreachable
- **Update interval**: every **30 seconds** by default
- **Message types**: Request (ask neighbours for their routing table) and Response (send local routing table to neighbours)

#### RIPv1 vs RIPv2

| Feature | RIPv1 | RIPv2 |
| ------- | ----- | ----- |
| Address type | Classful only | Supports VLSM / CIDR |
| Subnet mask in advertisement | No | Yes |
| Advertisement method | Broadcast (255.255.255.255) | Multicast (224.0.0.9) |
| Auto-summary | Always on, cannot disable | Can disable with `no auto-summary` |

> **RIPng** (Next Generation) is the IPv6 variant of RIP.

#### Commands

```
Router(config)# router rip
Router(config-router)# version 2
Router(config-router)# no auto-summary                ! advertise subnets, not classful networks
Router(config-router)# network <network_address>      ! enable RIP on matching interfaces (classful)
Router(config-router)# passive-interface <iface>      ! listen only, do not send updates (e.g. toward hosts)
Router(config-router)# default-information originate  ! advertise a default route to neighbours
Router(config-router)# maximum-paths <number>         ! max equal-cost paths (default 4)
Router(config-router)# distance <1-255>               ! override administrative distance
Router# show ip protocols
```

> `network` uses classful matching — e.g. `network 10.0.0.0` activates RIP on all interfaces whose IP falls in the 10.0.0.0/8 range.
> A **passive interface** receives route advertisements but does not send them.

---

### Dynamic Routing — EIGRP

- **Type**: Advanced (hybrid) Distance Vector, Interior Gateway Protocol
- Originally Cisco proprietary; now an open standard (RFC 7868)
- Much faster than RIP at reacting to network changes; no 15-hop limit (default max 100 hops)
- Uses multicast address **224.0.0.10**
- The only IGP that supports **unequal-cost load-balancing**; defaults to ECMP over 4 paths

#### Metric

EIGRP uses **bandwidth** (K1) and **delay** (K3) by default:

> Simplified metric = bandwidth of the slowest link + sum of delays on all links in the path.
> Delay is a static default value per interface type — not measured by ping.

#### Router ID

Selected in this priority order:
1. Manually configured
2. Highest IP on a loopback interface
3. Highest IP on a physical interface

#### Successor and Feasible Successor

| Term | Definition |
| ---- | ---------- |
| Feasible Distance (FD) | This router's total metric to the destination |
| Reported Distance (RD) | The neighbour's metric to the destination |
| Successor | Route with the lowest FD — installed in the routing table |
| Feasible Successor | Alternate route that satisfies the feasibility condition |

**Feasibility condition**: `RD of feasible successor < FD of successor` — guarantees the alternate path is loop-free.

#### Unequal-Cost Load Balancing (Variance)

```
Router(config-router)# variance <multiplier>     ! default 1 = ECMP only
```

A feasible successor is eligible for load balancing when:

> `FS feasible distance ≤ variance × successor feasible distance`

Variance = 1 means only routes with identical FD are used (ECMP). A feasible successor must still satisfy the feasibility condition to be eligible regardless of variance.

#### Commands

```
Router(config)# router eigrp <AS-number>                    ! AS number must match on all routers
Router(config-router)# no auto-summary
Router(config-router)# network <address> <wildcard-mask>    ! wildcard = inverted subnet mask
Router(config-router)# passive-interface <iface>
Router(config-router)# eigrp router-id <A.B.C.D>
Router(config-router)# variance <multiplier>
Router(config-router)# maximum-paths <number>
Router# show ip eigrp neighbors
Router# show ip eigrp topology                              ! successors and feasible successors
Router# show ip eigrp topology all-links                    ! all routes including non-feasible
Router# show ip protocols
```

> Wildcard mask = bitwise inverse of the subnet mask: 255.255.255.0 → 0.0.0.255.
> The `0` bits in the wildcard mask must match; `1` bits are "don't care."

#### Manual Summarization

```
Router(config-if)# ip summary-address eigrp <AS> <network> <mask>
```

#### EIGRP for IPv6

```
Router(config)# ipv6 router eigrp <AS>
Router(config-rtr)# no shutdown                              ! IPv6 EIGRP is shut down by default
Router(config-if)# ipv6 eigrp <AS>                          ! activate on interface
Router(config-if)# ipv6 summary-address eigrp <AS> ::/0     ! advertise default route
```

---

### Access Control Lists (ACLs)

#### Types

| Type     | Number Range | Filters On                              | Best Placed              |
| -------- | ------------ | --------------------------------------- | ------------------------ |
| Standard | 1–99         | Source IP only                          | Close to **destination** |
| Extended | 100–199      | Source + Destination IP, protocol, port | Close to **source**      |

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

## Topics Remaining (~18 labs)

Based on the CCNA 200-301 exam syllabus, the likely remaining topics include:

- OSPF (single-area and multi-area)
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

_CCNA 200-301 certification exam in progress._
