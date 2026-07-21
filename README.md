# CCNA Lab Notes — Cisco Packet Tracer

Hands-on study repository documenting Cisco Packet Tracer labs completed as part of CCNA (200-301) exam preparation. Each lab is saved as a `.pkt` file and corresponds to a topic from the CCNA syllabus.

## Progress

| Status         | Count         |
| -------------- | ------------- |
| Labs completed | 68            |
| Labs remaining | ~6            |
| Labs to redo   | Lab 42 (IPv6) |

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
| 54  | `054-single-area-ospf.pkt`                         | Single-Area OSPF                              |
| 55  | `055-multi-area-ospf.pkt`                          | Multi-Area OSPF                               |
| 56  | `056-ospf-troubleshooting.pkt`                     | Troubleshooting OSPF                          |
| 57  | `057-ospfv3-ipv6.pkt`                              | OSPFv3 — IPv6                                 |
| 58  | `058-eigrp-configuration.pkt`                      | EIGRP — configuration                         |
| 59  | `059-eigrp-troubleshooting.pkt`                    | Troubleshooting EIGRP                         |
| 60  | `060-ipv6-eigrp-configuration.pkt`                 | IPv6 EIGRP — configuration                    |
| 61  | `061-ppp-pap-chap.pkt`                             | PPP — PAP and CHAP authentication             |
| 62  | `062-ppp-troubleshooting.pkt`                      | PPP — troubleshooting                         |
| 65  | `065-gre-configuration.pkt`                        | GRE Tunnel — configuration                    |
| 66  | `066-gre-troubleshooting.pkt`                      | GRE Tunnel — troubleshooting                  |
| 67  | `067-bgp-configuration.pkt`                        | BGP — configuration                           |
| 68  | `068-bgp-troubleshooting.pkt`                      | BGP — troubleshooting                         |
| 69  | `069-hsrp-configuration.pkt`                       | HSRP — configuration                          |
| 70  | `070-hsrp-troubleshooting.pkt`                     | HSRP — troubleshooting                        |
| —   | `extra-configuring-stp.pkt`                        | STP configuration (extra)                     |
| —   | `extra-rapid-stp.pkt`                              | Rapid STP configuration (extra)               |
| —   | `extra-etherchannel-configuration.pkt`             | EtherChannel — Layer 3 configuration (extra)  |
| —   | `extra-eigrp-configuration.pkt`                    | EIGRP — unequal-cost load balancing (extra)   |
| —   | `extra-ospf-configuration-1.pkt`                   | OSPF configuration (extra)                    |
| —   | `extra-ospf-configuration-2.pkt`                   | OSPF configuration (extra)                    |
| —   | `extra-ospf-config-and-troubleshooting.pkt`        | OSPF configuration & troubleshooting (extra)  |
| —   | `extra-hsrp-configuration.pkt`                     | HSRP configuration (extra)                    |
| —   | `extra-gre-tunnels.pkt`                            | GRE tunnels (extra)                           |

---

## Notes

### Helpers and General Tips

- Use `?` to view available options at any point in the CLI. Example: `Router(config-if)# clock rate ?`

### The TCP/IP Model

A layered model that breaks network communication into independent layers, each with its own job. This course uses the **updated 5-layer** TCP/IP model (the original TCP/IP model has 4 layers; the OSI model has 7).

| # | Layer         | Function                                                     | Addressing   | Key Device | Example Protocols                       |
| - | ------------- | ----------------------------------------------------------- | ------------ | ---------- | --------------------------------------- |
| 5 | Application   | Formats, sends, and interprets application data             | —            | Hosts      | HTTP/HTTPS, FTP, TFTP, SMTP, POP3, IMAP |
| 4 | Transport     | End-to-end **process-to-process** communication             | Port numbers | Hosts      | TCP, UDP                                |
| 3 | Internet      | End-to-end **host-to-host** delivery across networks         | IP addresses | Routers    | IP (IPv4/IPv6), ICMP                    |
| 2 | Local Network | **Hop-to-hop** delivery within a local network              | MAC addresses| Switches   | Ethernet (802.3), Wi-Fi (802.11)        |
| 1 | Physical      | Sends/receives bits as electrical, optical, or radio signals | —           | Cables/NICs| —                                       |

- **Application (Layer 5)** — where network communications meet applications. Commonly called **"Layer 7"** (an OSI-model reference). Network devices (routers, switches) don't care about application data — only the communicating **hosts** interpret it.
- **Transport (Layer 4)** — a.k.a. "process-to-process" / "service-to-service." Uses **port numbers** to identify the process on each host (e.g. web server = **port 80**, FTP = **port 21**). Runs mainly on the end hosts, not routers.
- **Internet (Layer 3)** — "Internet" = *internetwork* (between networks). **Routers** operate here, forwarding based on the destination **IP address**.
- **Local Network (Layer 2)** — provides **hop-to-hop** delivery. A **hop** is one step from one router/host to the next router/host along the path. **Switches don't count as a hop** — they just extend the local network. Each hop re-addresses the frame to the **next hop's MAC address** (the NIC of the next router or the destination host).
- **Physical (Layer 1)** — cables, connectors, signal levels, link speeds (copper UTP, fiber, Wi-Fi radios, NICs).

#### Encapsulation and Decapsulation

**Sending host — data moves *down* the stack, each layer adds a header** (Layer 2 also adds a **trailer** for error checking):

1. Application prepares the data
2. Transport adds an **L4 header** → **segment** / **datagram**
3. Internet adds an **L3 header** → **packet**
4. Local Network adds an **L2 header + trailer** → **frame**
5. Physical transmits the frame as **bits** over the medium

**Receiving host — data moves *up* the stack, each layer removes its header (decapsulation):**

1. Receive the stream of bits at Layer 1
2. Examine and remove the **L2 header/trailer** (trailer checks for transmission errors)
3. Remove the **L3 header**, then the **L4 header**
4. Deliver the data to the Application layer, which processes it and may generate a response back down the stack

#### Protocol Data Units (PDUs)

The message has a specific name at each encapsulation stage:

| Layer | PDU              | Made of                     |
| ----- | ---------------- | --------------------------- |
| L4    | **Segment** (TCP) / **Datagram** (UDP) | Data + L4 header |
| L3    | **Packet** (L3PDU)                     | Segment/datagram + L3 header |
| L2    | **Frame** (L2PDU)                      | Packet + L2 header/trailer — *this is what's sent on the wire* |

- **Payload** = everything a layer's header/trailer encapsulates. A segment's payload is the **application data**; a packet's payload is a **segment/datagram**; a frame's payload is a **packet**.

#### Layer Interactions

- **Adjacent-layer interaction** (within one device) — each layer provides a **service to the layer above** it and is **serviced by the layer below** it. E.g. Layer 3 serves Layer 4 by delivering segments to the correct host via IP; Layer 2 serves Layer 3 by delivering packets to the next hop via MAC.
- **Same-layer interaction** (across devices) — each layer logically **communicates with the same layer** on the other device: a segment is addressed to the peer's **L4 port**, a packet to the destination host's **L3 IP**, a frame to the next hop's **L2 MAC**.

---

### Interfaces and Cables

#### Copper Ethernet (UTP)

- **RJ-45** connectors terminate copper Ethernet cables
- Ethernet standards are defined by the **IEEE 802.3** working group (IEEE = Institute of Electrical and Electronics Engineers)
- Speed is measured in **bits per second**: 1 Kb = 1,000 · 1 Mb = 1,000,000 · 1 Gb = 1,000,000,000 · 1 Tb = 1,000,000,000,000 bits

| Speed    | Common Name      | IEEE Standard | Informal Name | Max Length |
| -------- | ---------------- | ------------- | ------------- | ---------- |
| 10 Mbps  | Ethernet         | 802.3i        | 10BASE-T      | 100 m      |
| 100 Mbps | Fast Ethernet    | 802.3u        | 100BASE-T     | 100 m      |
| 1 Gbps   | Gigabit Ethernet | 802.3ab       | 1000BASE-T    | 100 m      |
| 10 Gbps  | 10 Gig Ethernet  | 802.3an       | 10GBASE-T     | 100 m      |

- Copper Ethernet uses **UTP (Unshielded Twisted Pair)** — 4 pairs = 8 wires
- Unshielded copper is vulnerable to **EMI (electromagnetic interference)**; twisting the wire pairs together cancels most of it
- **10BASE-T / 100BASE-T** use only **2 pairs** (4 wires); **1000BASE-T / 10GBASE-T** use all **4 pairs** (8 wires)

#### Pinouts and Cable Types

- For 10/100BASE-T, a **PC/NIC** and a **router** transmit (Tx) on pins **1,2** and receive (Rx) on pins **3,6**; a **switch** is the opposite — Tx on **3,6**, Rx on **1,2**. Because the two ends use separate wire pairs to send and receive, they can run **full-duplex** with no collisions.

| Device Type            | Transmit (Tx) | Receive (Rx) |
| ---------------------- | ------------- | ------------ |
| Router / Firewall / PC | 1, 2          | 3, 6         |
| Switch                 | 3, 6          | 1, 2         |

- **Straight-through cable** — pin 1↔1, 2↔2, 3↔3, 6↔6. Connects devices with **opposite** pin roles (PC↔Switch, Router↔Switch)
- **Cross-over cable** — pin 1↔3 and 2↔6. Connects devices with the **same** pin roles (Switch↔Switch, Router↔Router, PC↔PC, PC↔Router)
- **Auto MDI-X** — modern devices detect which pins the neighbour transmits on and flip their own Tx/Rx automatically, so either cable works
- In **1000BASE-T / 10GBASE-T** all 4 pairs (adding pins 4,5 and 7,8) are **bidirectional** — each pair both transmits and receives

| Cable Type       | Use Case                                                       |
| ---------------- | -------------------------------------------------------------- |
| Straight-Through | Different pin roles (PC ↔ Switch, Router ↔ Switch)             |
| Cross-Over       | Same pin roles (Switch ↔ Switch, Router ↔ Router, PC ↔ Router) |

#### Fiber Optic

- Switches and routers accept **SFP (Small Form-Factor Pluggable)** transceivers to connect fiber optic cables
- A fiber cable has **two strands** — one to transmit, one to receive

|               | Multimode (MM)                      | Single-mode (SM)     |
| ------------- | ----------------------------------- | -------------------- |
| Core diameter | Wider                               | Narrower             |
| Light source  | LED (multiple angles)               | Laser (single angle) |
| Distance      | Faster than copper, shorter than SM | Longest of all       |
| Cost          | Cheaper                             | More expensive       |

| Speed   | Cable Type          | IEEE Standard | Informal Name | Max Length             |
| ------- | ------------------- | ------------- | ------------- | ---------------------- |
| 1 Gbps  | Multimode or Single | 802.3z        | 1000BASE-LX   | 550 m (MM) · 5 km (SM) |
| 10 Gbps | Multimode           | 802.3ae       | 10GBASE-SR    | 400 m                  |
| 10 Gbps | Single-mode         | 802.3ae       | 10GBASE-LR    | 10 km                  |
| 10 Gbps | Single-mode         | 802.3ae       | 10GBASE-ER    | 40 km                  |

---

### Ethernet LAN Switching

#### Ethernet Frame

An Ethernet frame has three parts: **header**, **payload (packet)**, and **trailer**.

| Field                       | Bytes   | Purpose                                                     |
| --------------------------- | ------- | ----------------------------------------------------------- |
| Preamble                    | 7       | Receiver clock sync; bit pattern `10101010` ×7              |
| SFD (Start Frame Delimiter) | 1       | Marks end of preamble / start of frame; `10101011`          |
| Destination MAC             | 6       | Layer 2 destination address                                 |
| Source MAC                  | 6       | Layer 2 source address                                      |
| Type / Length               | 2       | ≤ 1500 = length; ≥ 1536 = type (EtherType)                  |
| Payload (packet)            | 46–1500 | Encapsulated L3 packet (padded to 46 with zeros if smaller) |
| FCS (Frame Check Sequence)  | 4       | **CRC (Cyclic Redundancy Check)** — receiver detects errors |

- Common **EtherType** values: `0x0800` = IPv4 · `0x86DD` = IPv6 · `0x0806` = ARP

#### MAC Addresses

- 6 bytes, must be globally unique. First 3 bytes = **OUI (Organizationally Unique Identifier)**, assigned to the manufacturer; last 3 bytes are unique to the device
- **Unicast** = one destination · **Broadcast** = all devices on the segment (dest MAC `FFFF.FFFF.FFFF`)

#### Switch Learning and Forwarding

- When a switch receives a frame, it learns the **source** MAC ↔ incoming interface mapping in its **MAC address table**
- **Known unicast** — destination is in the table → forward out that one port
- **Unknown unicast** — destination not in the table → **flood** (send out every port except the one it arrived on)
- A host that receives a frame not addressed to its MAC simply **discards** it
- Dynamic MAC entries age out after **5 minutes (300 s)** of inactivity

```
Switch# show mac address-table
Switch# clear mac address-table dynamic                              ! clear all dynamic entries
Switch# clear mac address-table dynamic address <mac>                ! clear one MAC
Switch# clear mac address-table dynamic interface <interface>        ! clear one interface
```

---

### Address Resolution Protocol (ARP)

- Maps a known **Layer 3 (IP)** address to its **Layer 2 (MAC)** address
- Before sending a frame, a host knows the destination **IP** but not its **MAC**, so it uses ARP to find it
- Minimum Ethernet payload is **46 bytes**; shorter payloads are **padded with zeros**

**Process:**

1. **ARP Request** — a **broadcast** frame (dest MAC `FFFF.FFFF.FFFF`) asking "who has this IP?" A switch floods it out all ports except the ingress
2. **ARP Reply** — a **unicast** frame back to the requester carrying the MAC

- The requester caches the result in its **ARP table**
- ARP EtherType = **`0x0806`**

```
Router# show arp                                   ! view the ARP table
C:\> arp -a                                        ! host ARP cache (Windows)
```

---

### IPv4 Addressing

- A 32-bit address written as 4 octets. The mask splits it into a **network portion** (fixed) and a **host portion** (identifies devices)

#### Address Classes

| Class | Leading Bits | First Octet | Default Prefix | Purpose         |
| ----- | ------------ | ----------- | -------------- | --------------- |
| A     | `0xxxxxxx`   | 0–127       | /8             | Large networks  |
| B     | `10xxxxxx`   | 128–191     | /16            | Medium networks |
| C     | `110xxxxx`   | 192–223     | /24            | Small networks  |
| D     | `1110xxxx`   | 224–239     | —              | Multicast       |
| E     | `1111xxxx`   | 240–255     | —              | Experimental    |

- **127.0.0.0 – 127.255.255.255** = **loopback** range, used to test the local device's network stack

#### Network and Broadcast Addresses

- **Network address** — first address in the subnet, all **host bits = 0**
- **Broadcast address** — last address in the subnet, all **host bits = 1**
- Neither can be assigned to a host; the usable host range is everything in between

#### Interface Default States

- **Router** interfaces are **administratively down** by default (disabled by `shutdown`) — bring them up with `no shutdown`
- **Switch** interfaces are **not** administratively down by default — they come up when a cable is connected

---

### Cisco IOS CLI

#### Console Access

- The **first-time** configuration of a device must be done over a **console** connection (SSH/Telnet require prior setup — see [Remote Access](#remote-access--telnet-and-ssh))
- Console ports use an **RJ-45** or **USB** connector. For an RJ-45 console you need a **rollover cable** (RJ-45 → DB-9 serial); most modern laptops also need a USB-to-serial adapter
- A rollover cable reverses the pins end-to-end: 1↔8, 2↔7, 3↔6, 4↔5
- Connect with a **terminal emulator** (e.g. PuTTY) using the default serial parameters:

| Parameter    | Value    |
| ------------ | -------- |
| Speed (baud) | 9600 bps |
| Data bits    | 8        |
| Stop bits    | 1        |
| Parity       | none     |
| Flow control | none     |

#### CLI Help

- `?` — list available commands / options at the current point (e.g. `Router(config-if)# clock rate ?`)
- **Tab** — autocomplete a partially typed keyword

#### Modes

| Prompt            | Mode                 | Entered With         | Capability                                                      |
| ----------------- | -------------------- | -------------------- | --------------------------------------------------------------- |
| `Router>`         | User EXEC            | (default login)      | Limited monitoring commands                                     |
| `Router#`         | Privileged EXEC      | `enable`             | View full config, reload, save, set clock — but not edit config |
| `Router(config)#` | Global Configuration | `configure terminal` | Change the device configuration                                 |

```
Router> enable                   ! enter privileged EXEC
Router# configure terminal       ! enter global config
```

> Two configuration files exist at once: the **running-config** (active, in RAM) and the **startup-config** (loaded on reboot, in NVRAM). Editing config changes only the running-config — save it to survive a reload (see [Save Configuration](#save-configuration)).

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

| Feature                      | RIPv1                       | RIPv2                              |
| ---------------------------- | --------------------------- | ---------------------------------- |
| Address type                 | Classful only               | Supports VLSM / CIDR               |
| Subnet mask in advertisement | No                          | Yes                                |
| Advertisement method         | Broadcast (255.255.255.255) | Multicast (224.0.0.9)              |
| Auto-summary                 | Always on, cannot disable   | Can disable with `no auto-summary` |

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

| Term                   | Definition                                                |
| ---------------------- | --------------------------------------------------------- |
| Feasible Distance (FD) | This router's total metric to the destination             |
| Reported Distance (RD) | The neighbour's metric to the destination                 |
| Successor              | Route with the lowest FD — installed in the routing table |
| Feasible Successor     | Alternate route that satisfies the feasibility condition  |

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

### Dynamic Routing — OSPF

- **Type**: Link-state, Interior Gateway Protocol (IGP)
- Every router builds an identical map of the network and independently runs the **Shortest Path First (SPF / Dijkstra)** algorithm to calculate the best route to each destination
- More demanding on router resources than distance vector protocols, but reacts to network changes faster
- Uses multicast **224.0.0.5** (all OSPF routers) and **224.0.0.6** (DR/BDR); encapsulated directly in IP with protocol number **89**
- Default administrative distance = **110**
- Supports ECMP (default max 4 paths); does **not** support unequal-cost load balancing

| Version | Use           | CCNA         |
| ------- | ------------- | ------------ |
| OSPFv1  | Obsolete      | —            |
| OSPFv2  | IPv4 networks | Required     |
| OSPFv3  | IPv6 networks | Good to know |

#### LSAs, LSDB, and Neighbor Formation

- Routers store network information in **Link State Advertisements (LSAs)**, organized in the **Link State Database (LSDB)**
- LSAs are flooded until every router in the area has an identical LSDB. Each LSA is **refreshed (re-flooded) every 30 minutes** and expires at a **max age of 60 minutes** if not refreshed
- High-level process: (1) become neighbors → (2) exchange LSAs / build LSDB → (3) run SPF and install best routes

#### Neighbor States

| State    | Meaning                                                                                     |
| -------- | ------------------------------------------------------------------------------------------- |
| Down     | No Hellos received yet                                                                      |
| Init     | A Hello received, but own Router ID not yet listed in the neighbor's Hello                  |
| 2-Way    | Bidirectional communication confirmed (both RIDs seen); DR/BDR elected here                 |
| Exstart  | Master/Slave decided via DBD exchange — **higher Router ID becomes Master**                 |
| Exchange | Routers exchange DBD packets (summaries of their LSDB)                                      |
| Loading  | Routers send LSRs for missing LSAs; neighbors reply with LSUs; receipt confirmed with LSAck |
| Full     | Full adjacency, identical LSDB — steady state                                               |

> DROthers only reach **Full** with the DR and BDR; between two DROthers the state stays **2-Way** (this reduces flooding).

#### OSPF Message Types

| Type | Name                               | Purpose                                |
| ---- | ---------------------------------- | -------------------------------------- |
| 1    | Hello                              | Neighbor discovery and maintenance     |
| 2    | Database Description (DBD)         | Summary of the router's LSDB           |
| 3    | Link-State Request (LSR)           | Requests specific LSAs from a neighbor |
| 4    | Link-State Update (LSU)            | Carries the requested LSAs             |
| 5    | Link-State Acknowledgement (LSAck) | Confirms receipt of an LSA             |

#### Areas

- OSPF divides the network into **areas** to limit the scope of LSA flooding and SPF recalculation
- An area is a set of routers/links sharing the same LSDB
- **Area 0 (backbone)** — every other area must connect to it
- **Internal router** — all interfaces in one area
- **Area Border Router (ABR)** — interfaces in multiple areas; keeps a separate LSDB per area (recommended max 2 areas)
- **Backbone router** — has an interface in Area 0 (includes ABRs)
- **Autonomous System Boundary Router (ASBR)** — connects OSPF to an external network
- **Intra-area route** = destination in the same area; **inter-area route** = destination in a different area

**Area rules:** areas must be contiguous · every non-backbone area needs at least one ABR to Area 0 · OSPF interfaces in the same subnet must be in the same area.

#### Metric (Cost)

- `Cost = Reference bandwidth / interface bandwidth`, rounded up — any result below 1 becomes **1**
- Default reference bandwidth = **100 Mbps**
- Example: Ethernet (10 Mbps) → 100 / 10 = **10**; Fast Ethernet (100 Mbps) → **1**; Gigabit (1000 Mbps) → 0.1 → **1**
- Loopback interfaces always have a cost of **1**
- Total cost to a destination = sum of the outgoing interface costs along the path
- Best practice: raise the reference bandwidth above the fastest link, keep it **identical on all routers**, and tune individual links with `ip ospf cost` rather than changing bandwidth (which affects other calculations without changing actual link speed)

```
Router(config-router)# auto-cost reference-bandwidth <mbps>
Router(config-if)# ip ospf cost <number>            ! manual cost, overrides auto-calculated
Router(config-if)# bandwidth <kbps>                 ! changes metric only, not real speed (not recommended)
Router# show ip ospf interface brief                ! view per-interface cost
```

#### Timers

| Network type               | Hello | Dead  |
| -------------------------- | ----- | ----- |
| Broadcast / Point-to-Point | 10 s  | 40 s  |
| Non-broadcast              | 30 s  | 120 s |

> Every received Hello resets the Dead timer. If it reaches 0, the neighbor is removed. Hello and Dead timers **must match** to form an adjacency.

#### Network Types

| Type           | Default on         | DR/BDR? | Neighbor discovery  |
| -------------- | ------------------ | ------- | ------------------- |
| Broadcast      | Ethernet, FDDI     | Yes     | Dynamic (224.0.0.5) |
| Point-to-Point | PPP, HDLC (serial) | No      | Dynamic (224.0.0.5) |
| Non-broadcast  | X.25, Frame Relay  | —       | —                   |

- **DR/BDR election** (broadcast networks) — reduces flooding by having all routers form Full adjacency only with the DR/BDR:
  1. Highest OSPF interface **priority** (default 1; range 0–255; **0** = never DR/BDR)
  2. Highest **Router ID** (tie-breaker)
- First place = DR, second = BDR, everyone else = **DROther**. Roles are not preemptive — they only change on OSPF reset or interface failure (when the DR fails, the BDR is promoted and a new BDR is elected).
- On a directly connected point-to-point Ethernet link you can manually set the P2P type to skip the DR/BDR election. A serial link cannot use the broadcast type.

```
Router(config-if)# ip ospf priority <0-255>
Router(config-if)# ip ospf network <broadcast|point-to-point|non-broadcast>
```

#### Router ID — selection priority

1. Manually configured (`router-id`)
2. Highest IP on a **loopback** interface
3. Highest IP on a physical interface

```
Router(config-router)# router-id <A.B.C.D>          ! reload or `clear ip ospf process` to apply
```

#### Neighbor Requirements

Must match / be satisfied to form an adjacency:

1. Same **area** number
2. Interfaces in the **same subnet**
3. OSPF process not shut down
4. **Unique** Router IDs
5. Matching **Hello / Dead** timers
6. Matching **authentication** settings

> Mismatched **IP MTU** or **OSPF network type** can still form a neighbor relationship but OSPF won't function correctly. MTU defaults to 1500 bytes (`ip mtu <bytes>`).

```
Router(config-if)# ip ospf authentication-key <key>
Router(config-if)# ip ospf authentication          ! enable authentication on the interface
```

#### LSA Types (CCNA)

| Type | Name            | Generated by                         | Describes                                   |
| ---- | --------------- | ------------------------------------ | ------------------------------------------- |
| 1    | Router LSA      | Every OSPF router                    | The router (by RID) + its attached networks |
| 2    | Network LSA     | The **DR** of a multi-access network | Routers attached to that segment            |
| 5    | AS-External LSA | An **ASBR**                          | Routes to destinations outside the AS       |

#### Configuration

```
Router(config)# router ospf <process_id>                  ! process ID is locally significant
Router(config-router)# network <address> <wildcard> area <area>   ! activate OSPF on matching interfaces
Router(config-router)# passive-interface <iface>          ! stop Hellos on the interface (still advertises its subnet)
Router(config-router)# passive-interface default          ! make all interfaces passive
Router(config-router)# default-information originate       ! advertise a default route
Router(config-router)# maximum-paths <number>             ! max equal-cost paths (default 4)
Router(config-router)# distance <number>                  ! override administrative distance
Router(config-router)# area <area> range <address> <mask> ! summarize routes on an ABR
Router(config-if)# ip ospf <process_id> area <area>       ! activate OSPF per interface (alternative to `network`)
```

> Unlike EIGRP's AS number, the OSPF **process ID is locally significant** — routers with different process IDs can still become neighbors.

#### OSPFv3 (IPv6)

```
Router(config)# ipv6 unicast-routing
Router(config)# ipv6 router ospf <process_id>             ! create the OSPFv3 process
Router(config-if)# ipv6 ospf <process_id> area <area>     ! activate per interface
Router# show ipv6 ospf
Router# show ipv6 ospf neighbor
```

#### Verification

```
Router# show ip ospf interface [<interface>]
Router# show ip ospf database                             ! view the LSDB
Router# show ip ospf neighbor
Router# show ip route ospf
```

---

### First Hop Redundancy Protocols (FHRP)

Protects the default gateway of a subnet by letting two or more routers back each other up. If the active router fails, a backup takes over — usually within a few seconds — so hosts keep their connectivity.

- Routers share a **Virtual IP (VIP)**, and each host's default gateway is set to that VIP
- Routers negotiate their roles by exchanging multicast Hello messages
- One router becomes **active**, the rest are **standby**
- Hosts don't know the MAC of the VIP, so they send an **ARP request**; only the active router replies with the **Virtual MAC** for the VIP
- If standby routers stop hearing from the active router (e.g. hardware failure), a new active router is elected
- The host's ARP cache never changes — it always sends to the Virtual MAC. Only the **switches** must relearn where that Virtual MAC lives
- The newly elected active router sends a **Gratuitous ARP reply** (an unrequested ARP reply, sent as a broadcast) sourced from the Virtual MAC, so every switch updates its MAC address table

> A normal ARP reply is **unicast**; a Gratuitous ARP reply is **broadcast**, which is why all switches learn the new port for the Virtual MAC.

#### Protocol Comparison

| FHRP | Terminology    | Multicast IP                    | Virtual MAC                                 | Cisco Proprietary |
| ---- | -------------- | ------------------------------- | ------------------------------------------- | ----------------- |
| HSRP | Active/Standby | v1: 224.0.0.2 · v2: 224.0.0.102 | v1: `0000.0C07.ACXX` · v2: `0000.0C9F.FXXX` | Yes               |
| VRRP | Master/Backup  | 224.0.0.18                      | `0000.5E00.01XX`                            | No                |
| GLBP | AVG/AVF        | 224.0.0.102                     | `0007.B400.XXYY`                            | Yes               |

- **HSRP** — Cisco proprietary. v2 adds IPv6 support and more groups. `XX` / `XXX` = HSRP group number (hex).
- **VRRP** — open standard. Master/Backup is just different naming for Active/Standby. `XX` = VRRP group number.
- **GLBP** — Cisco proprietary; load-balances across routers within a **single** subnet. One **Active Virtual Gateway (AVG)** assigns up to **4 Active Virtual Forwarders (AVFs)** (the AVG can also be an AVF); each AVF is the gateway for a portion of the hosts. `XX` = GLBP group, `YY` = AVF number.

> With HSRP and VRRP you can still load-balance by making a **different router active in each subnet/VLAN**. GLBP load-balances **within** one subnet.

#### Preemption

- **HSRP is non-preemptive by default**: if the former active router comes back online it becomes standby rather than reclaiming the active role (configurable with `preempt`).
- **VRRP is preemptive by default** — a returning higher-priority master reclaims the role automatically.

#### HSRP Configuration

```
Router(config-if)# standby version 2                       ! use HSRP v2 (do this before other standby commands)
Router(config-if)# standby <group> ip <virtual_ip>         ! set the Virtual IP
Router(config-if)# standby <group> priority <number>       ! set priority (default 100)
Router(config-if)# standby <group> preempt                 ! allow this router to reclaim the active role
```

Active router **election order**:

1. Highest **priority** (default 100)
2. Highest **IP address** (tie-breaker)

> All routers must use the **same version** and the **same group number**. Enable `preempt` only on the router you want to become active.

#### Verification

```
Router# show standby                                       ! HSRP state, priority, VIP, virtual MAC
C:\> arp -a                                                ! view a host's ARP cache (Windows)
```

---

### Wide Area Networks (WAN)

A WAN extends over a large geographical area. In an enterprise it usually refers to the **private** connections that link offices, data centers, and other sites together — either over dedicated links or over the public internet using VPNs.

- **Hub-and-Spoke topology** — the central site (usually the data center) is the **hub**; the remote sites that connect back to it are the **spokes**. Each site connects to the service provider, which ties the hub and spokes together
- A VPN creates a virtual tunnel across a shared/public network (like the internet) and can encrypt traffic so only the intended recipient can read it — the original IP packet is encapsulated inside a new packet

#### Leased Lines

- A dedicated **physical** connection between two sites
- Use serial connections with **PPP** or **HDLC** encapsulation
- Downsides vs. Ethernet WAN: higher cost, longer installation lead time, and slower speeds

#### Multiprotocol Label Switching (MPLS)

Service-provider networks are **shared** infrastructure — many customer enterprises connect to the same provider network to build their WAN connections. VPNs are created across MPLS using **labels**.

| Term      | Meaning              |
| --------- | -------------------- |
| CE router | Customer Edge router |
| PE router | Provider Edge router |
| P router  | Provider Core router |

- When a **PE** router receives a frame from a **CE** router, it adds a **label**. Labels — not the destination IP — are used to make forwarding decisions **inside** the provider network
- MPLS is used only by the **PE and P** routers; the **CE** routers do not run MPLS
- **Layer 3 MPLS VPN** — CE and PE routers peer using a routing protocol (OSPF, EIGRP, BGP…) or static routes with the PE as next hop, so the customer exchanges routes with the provider
- **Layer 2 MPLS VPN** — the CE and PE routers do **not** peer. The provider network is fully transparent, as if the two CE routers were directly connected; if a routing protocol is used, the two CEs peer **directly with each other**

#### Internet Access Technologies

- **DSL (Digital Subscriber Line)** — internet over existing telephone lines; can share the line already installed in most homes. A **DSL modem** (modulator-demodulator) converts data into a format suitable for the phone line — a standalone device or built into the home router
- **Cable** — internet over the same coax **CATV** lines used for cable TV. A **cable modem** performs the conversion

#### Redundant Internet Connections

| Term             | Meaning                         |
| ---------------- | ------------------------------- |
| Single-homed     | 1 connection to 1 ISP           |
| Dual-homed       | 2 connections to 1 ISP          |
| Multi-homed      | 1 connection to each of 2 ISPs  |
| Dual multi-homed | 2 connections to each of 2 ISPs |

---

### Point-to-Point Protocol (PPP)

A Layer 2 protocol commonly used over serial WAN (leased-line) connections. The default Layer 2 encapsulation on a Cisco router serial interface is **Cisco HDLC** (Cisco proprietary); switching to PPP adds features such as authentication.

- Both ends of the link must use the **same** encapsulation
- PPP's main advantage over HDLC is built-in **authentication**

```
Router# show interfaces <interface>                  ! view current encapsulation (HDLC or PPP)
Router(config-if)# encapsulation ppp                 ! set encapsulation to PPP
```

#### PAP vs CHAP

| Feature       | PAP (Password Authentication Protocol) | CHAP (Challenge Handshake Authentication Protocol) |
| ------------- | -------------------------------------- | -------------------------------------------------- |
| Handshake     | Two-way                                | Three-way                                          |
| Password sent | Static password in **cleartext**       | Never sent — an **MD5 hash** of a challenge        |
| Challenge     | None                                   | Random, dynamically generated string               |
| Security      | Weak                                   | Strong (preferred)                                 |

#### PAP Configuration

```
Router(config)# username <username> password <password>            ! credentials the peer will send us
Router(config-if)# encapsulation ppp
Router(config-if)# ppp authentication pap                          ! require PAP on this link
Router(config-if)# ppp pap sent-username <username> password <password>   ! credentials we send to the peer
```

#### CHAP Configuration

```
Router(config)# username <peer_hostname> password <shared_password>   ! username = the OTHER router's hostname
Router(config-if)# encapsulation ppp
Router(config-if)# ppp authentication chap                            ! require CHAP on this link
```

> For CHAP, each router's local `username` must match the **other router's hostname**, and the **password must be identical** on both routers. The password is used to compute the MD5 hash and is never transmitted across the link.

A VPN between two devices (typically routers/firewalls) that connects two sites together over the internet. A tunnel is formed by encapsulating the original IP packet with a VPN header and a new IP header; with **IPSec** the original packet is also **encrypted**.

1. The sending device combines the original packet with a session (encryption) key and runs them through an encryption algorithm
2. It encapsulates the encrypted packet with a VPN header and a new IP header
3. The new packet is sent to the other end of the tunnel
4. The receiving device decrypts the data to recover the original packet, then forwards it to its destination

**Limitations of plain IPSec:**

- Does not support broadcast/multicast traffic, so dynamic routing protocols (which rely on multicast) can't run over the tunnel — solved with **GRE over IPSec**
- Manually configuring a full mesh of tunnels between many sites is labor-intensive — solved with **DMVPN**

#### GRE over IPSec

- **GRE (Generic Routing Encapsulation)** creates tunnels like IPSec, but on its own it does **not** encrypt the payload — so plain GRE is **not secure**
- GRE can encapsulate a wide variety of Layer 3 protocols as well as **broadcast and multicast** traffic (so routing protocols work over it)
- **GRE over IPSec** combines both: the original packet is wrapped in a GRE header + new IP header, then that GRE packet is **encrypted and encapsulated inside IPSec** — you get GRE's flexibility _and_ IPSec's security

#### Dynamic Multipoint VPN (DMVPN)

- Cisco solution that lets routers **dynamically** build a full mesh of IPSec tunnels without manually configuring every single one
- Each spoke first builds a tunnel to the **hub**; the hub then supplies the information needed for spokes to form **direct spoke-to-spoke** tunnels on demand

#### Remote Access VPN

- Lets end devices (PCs, phones, laptops) securely reach the company's internal resources over the internet
- Typically uses **TLS (Transport Layer Security)**
- **VPN client software** on the end device forms a secure tunnel to a company router/firewall acting as a TLS server, so a remote user can reach internal resources without being physically on the company network

---

### GRE Tunnels — Configuration

Create a virtual tunnel interface, tie it to a physical source/destination, give it an IP, then run a routing protocol over it so each side learns the other's LANs dynamically.

```
Router(config)# interface tunnel <number>
Router(config-if)# tunnel source <local_physical_interface_or_ip>
Router(config-if)# tunnel destination <remote_physical_ip>
Router(config-if)# ip address <ip_address> <subnet_mask>     ! tunnel-interface IP (its own subnet)
```

> `tunnel source` / `tunnel destination` reference the **physical** (underlay) addresses that the tunnel rides over. The `ip address` on the tunnel interface is a separate **overlay** subnet shared by the two tunnel endpoints.
> After both ends are up, configure a routing protocol (e.g. OSPF/EIGRP) so the routers advertise their LANs across the tunnel.

```
Router# show ip interface brief                    ! confirm the tunnel interface is up/up
Router# show interfaces tunnel <number>
```

---

### BGP — Border Gateway Protocol

- **Type**: **Exterior Gateway Protocol (EGP)** — the routing protocol of the internet; it routes **between** organizations / autonomous systems (whereas OSPF, EIGRP, RIP are interior gateway protocols used _within_ an organization)
- A **path-vector** protocol — instead of a simple metric it chooses paths using BGP **attributes** (e.g. AS-path length)
- Runs over **TCP port 179** for reliable delivery; neighbors (peers) are **manually configured** — there is no automatic neighbor discovery
- Each organization is assigned an **Autonomous System Number (ASN)**
- **eBGP** — peering between routers in **different** AS numbers (administrative distance **20**)
- **iBGP** — peering between routers in the **same** AS number (administrative distance **200**)

> BGP was removed from the CCNA 200-301 exam; these labs cover basic configuration only.

#### Configuration

```
Router(config)# router bgp <local_as_number>                          ! local AS number
Router(config-router)# neighbor <neighbor_ip> remote-as <neighbor_as> ! define a peer
Router(config-router)# network <network_address> mask <subnet_mask>   ! originate a network into BGP
```

- The AS in `router bgp` is the router's **own** AS. On the `neighbor` line, if `remote-as` matches the local AS it's **iBGP**; if it differs it's **eBGP**
- Unlike OSPF/EIGRP, the BGP **`network` command does not activate BGP on an interface**. It tells BGP to **originate (advertise)** that exact prefix, and the route must already exist in the routing table with the **exact** network + mask to be advertised

#### Advertising a Summary with a Null0 Route

To advertise an aggregate (e.g. a single `10.0.0.0/16` covering `10.0.12.0/30`, `10.0.13.0/30`, `10.0.23.0/30`) the exact summary route must exist in the routing table. Point it at **Null0** — a virtual discard interface — so the entry exists; more specific routes still win, so real traffic is unaffected.

```
Router(config)# ip route 10.0.0.0 255.255.0.0 null0        ! create the summary route (discard interface)
Router(config-router)# network 10.0.0.0 mask 255.255.0.0   ! now BGP can advertise the /16
```

#### Verification

```
Router# show ip bgp                                        ! BGP table (learned/advertised prefixes)
Router# show ip bgp summary                                ! neighbors, state, prefixes received
Router# show ip route bgp                                  ! BGP routes installed in the routing table
```

> A neighbor stuck in `Idle`/`Active` (never reaching `Established`) usually means the peer IP, `remote-as`, or underlying IP reachability is wrong.

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

## Topics Remaining (~8 labs)

Based on the CCNA 200-301 exam syllabus, the likely remaining topics include:

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
