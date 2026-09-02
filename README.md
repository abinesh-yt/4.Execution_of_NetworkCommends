# 4. Execution of Network Commands

## AIM

Use of Network commands in Real Time environment.

## Software

- Command Prompt
- Network Protocol Analyzer

## Procedure

To do this experiment, the following steps are performed.

In this experiment, students have to understand basic networking commands such as `cpdump`, `netstat`, `ifconfig`, `nslookup`, and `traceroute`, and also capture ping and traceroute PDUs using a network protocol analyzer.

All commands related to Network configuration are included, which covers how to switch to privilege mode and normal mode, how to configure router interfaces, and how to save the configuration to flash memory or permanent memory.

### Commands Included

- Configuring the Router commands
- General Commands to configure network
- Privileged Mode commands of a router
- Router Processes & Statistics
- IP Commands
- Other IP Commands e.g. `show ip route`

---

# Output

## 1. Netstat

The `netstat` command is used to display active network connections and related network information.

### Command

```cmd
netstat
```

### Output

<img width="1020" height="932" alt="Screenshot 2026-09-02 102241" src="https://github.com/user-attachments/assets/41b5d442-6ac3-4f31-85f6-71da5d21e5a4" />

---

## 2. Ipconfig

The `ipconfig` command displays the IP configuration information of the system's network adapters.

### Command

```cmd
ipconfig
```

### Output

<img width="632" height="507" alt="Screenshot 2026-09-02 102647" src="https://github.com/user-attachments/assets/f8f0acb2-c2db-4cd8-bf5a-233feb100f79" />


---

## 3. Ping

The `ping` command is used to test network connectivity between the system and a specified host.

### Command

```cmd
ping
```

### Output

<img width="668" height="518" alt="Screenshot 2026-09-02 102708" src="https://github.com/user-attachments/assets/269fdae0-fe89-44c5-bcbf-fdd50635aa78" />



---

## 4. Tracert

The `tracert` command is used to trace the route taken by packets to reach a destination.

### Command

```cmd
tracert
```

### Output

<img width="628" height="236" alt="Screenshot 2026-09-02 102727" src="https://github.com/user-attachments/assets/2beb562e-a5f8-44d5-a32e-6c0d4c638dcb" />


---

## 5. Nslookup

The `nslookup` command is used to obtain DNS information for a specified domain or host.

### Command

```cmd
nslookup
```

### Output
<img width="322" height="58" alt="Screenshot 2026-09-02 102806" src="https://github.com/user-attachments/assets/5798cf79-6d3d-42b8-9066-c0cb7e49d869" />


---

## 6. Getmac

The `getmac` command displays the MAC addresses associated with the network adapters of the system.

### Command

```cmd
getmac
```

### Output

<img width="713" height="127" alt="Screenshot 2026-09-02 102823" src="https://github.com/user-attachments/assets/2c6e1cf0-5329-483e-b635-f69482c58efd" />


---

## 7. Hostname

The `hostname` command displays the host name of the computer.

### Command

```cmd
hostname
```

### Output

<img width="222" height="33" alt="Screenshot 2026-09-02 102836" src="https://github.com/user-attachments/assets/2afb4e26-be8a-406d-a190-a6fe95d994ab" />


---

## 8. Nbtstat

The `nbtstat` command displays protocol statistics and current TCP/IP connections using NetBIOS over TCP/IP.

### Command

```cmd
nbtstat
```

### Output

<img width="855" height="395" alt="Screenshot 2026-09-02 102852" src="https://github.com/user-attachments/assets/057f00f8-6078-471f-82f0-25ae9b295524" />

---

## 9. ARP

The `arp` command displays and modifies the IP-to-physical address translation tables used by the Address Resolution Protocol (ARP).

### Command

```cmd
arp
```

### Output

<img width="757" height="527" alt="Screenshot 2026-09-02 102906" src="https://github.com/user-attachments/assets/27602eda-a257-4229-879c-b489841b243d" />


---

## 10. Systeminfo

The `systeminfo` command displays detailed information about the operating system and computer system configuration.

### Command

```cmd
systeminfo
```

### Output

<img width="842" height="596" alt="Screenshot 2026-09-02 102926" src="https://github.com/user-attachments/assets/db450faa-94f1-41d8-bbed-d2d4b3a2ccb7" />

---

# Result

Thus, the execution of network commands was performed successfully.

---

## Commands Executed

| No. | Command | Purpose |
|-----|---------|---------|
| 1 | `netstat` | Displays active network connections |
| 2 | `ipconfig` | Displays IP configuration |
| 3 | `ping` | Tests network connectivity |
| 4 | `tracert` | Traces the route to a destination |
| 5 | `nslookup` | Obtains DNS information |
| 6 | `getmac` | Displays MAC addresses |
| 7 | `hostname` | Displays the system host name |
| 8 | `nbtstat` | Displays NetBIOS/TCP-IP statistics |
| 9 | `arp` | Displays ARP information |
| 10 | `systeminfo` | Displays system configuration information |

---

## Conclusion

The basic network commands were executed using the Command Prompt. The outputs of commands such as `netstat`, `ipconfig`, `ping`, `tracert`, `nslookup`, `getmac`, `hostname`, `nbtstat`, `arp`, and `systeminfo` were observed and analyzed.
