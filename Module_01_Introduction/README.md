# Module 01: Introduction to Ethical Hacking

## Lab Setup Verification

### Network Topology
[Network diagram description]

### Machines Status
| Machine | IP | Wazuh Agent | Status |
| :--- | :--- | :--- | :--- |
| Parrot OS | 192.168.31.129 | ✅ | Active |
| Windows 11 | 192.168.31.135 | ✅ | Active |
| Windows Server 2022 | 192.168.31.132 | ✅ | Active |
| Ubuntu Web Apps | 192.168.31.133 | ✅ | Active |
| Metasploitable 2 | 192.168.31.134 | N/A | Active |
| Wazuh Manager | 192.168.31.150 | Manager | Active |

### Verification Commands
```bash
# Ping test - all machines reachable
ping -c 2 192.168.31.135  # Success
ping -c 2 192.168.31.132  # Success
Wazuh Dashboard Evidence
https://screenshots/wazuh_agents_active.png

Key Learnings
5 Phases of Hacking

CIA Triad + AAA Framework

Hacker Classifications

Information Security Laws

Documented by: Muhammad Imtiaz Shaffi
