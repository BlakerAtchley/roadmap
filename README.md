# Cloud Security Learning Roadmap

Public log of my path into **Cloud Security Engineering (Microsoft Azure)**. I update it every week with certifications, labs and projects, so anyone can see what I've actually built and where I'm headed.

**Background:** Career changer from emergency services. Used to working under pressure, following procedures and making decisions fast, which carries straight into security operations and incident response.

**Target role:** Cloud Security Engineer: identity and access, network security controls, policy-as-code, detection and response in Azure.

---

## Status at a glance

| Area | Status |
| --- | --- |
| Current focus | CompTIA A+ (Core 2) |
| Degree | B.S. Cloud and Network Engineering (Azure), in progress |
| Certifications earned | 0 / 6 |
| Portfolio projects published | 0 / 4 |
| Hands-on networking | Coddy Computer Networking learning path **complete** (6 steps, 282 lessons) |
| Hands-on security | Coddy Cybersecurity: Security Fundamentals complete; Investigating a Breach 15/20 lessons |
| Last updated | 2026-11-16 |

---

## Certification path

| # | Certification | Target | Status |
| --- | --- | --- | --- |
| 1 | CompTIA A+ | Early 2027 | Studying |
| 2 | CompTIA Network+ | Spring 2027 | Planned |
| 3 | CompTIA Security+ | Mid 2027 | Planned |
| 4 | Microsoft AZ-900: Azure Fundamentals | Mid 2027 | Planned |
| 5 | Microsoft AZ-104: Azure Administrator | Late 2027 | Planned |
| 6 | Microsoft AZ-500: Azure Security Engineer | 2028 | Planned |

Status values: `Planned` → `Studying` → `Passed (YYYY-MM)`

---

## Portfolio projects

Each project gets its own repository with an architecture diagram, screenshots, the code or templates, and a "what I learned" section. Resources are torn down after each lab.

| # | Project | What it shows | Target | Repo |
| --- | --- | --- | --- | --- |
| 1 | **Azure foundation and identity:** management groups, Entra ID, MFA, Conditional Access, least-privilege RBAC | Identity is the new perimeter | Q3 2027 | _coming soon_ |
| 2 | **SIEM honeypot:** exposed VM → Log Analytics → Microsoft Sentinel, analytics rules, KQL hunting queries | Detection engineering | Q4 2027 | _coming soon_ |
| 3 | **Secure network and policy as code:** hub-and-spoke VNets, NSGs, Azure Firewall/Bastion, Azure Policy and Defender for Cloud, built with Terraform or Bicep | Secure-by-default infrastructure | Q1 2028 | _coming soon_ |
| 4 | **Incident response playbook:** simulated breach investigated in Sentinel, written up using NIST incident response phases | Investigation and reporting | Q2 2028 | _coming soon_ |

---

## Hands-on practice

| Platform | Progress (as of 2026-11-16) |
| --- | --- |
| Service Desk Simulator | Help Desk Technician (rank 3 of 9), Diamond tier · 3,791 points · 179/250 tickets toward Service Desk Professional · 16.8 hours logged · 90%+ accuracy |
| Coddy | Level 22 · 8 certificates including the Computer Networking learning path (below) · all done hands-on in a browser-based Linux terminal |

### Service Desk Simulator

- **Certificates earned:** First Line Support, IT Support Foundations, Help Desk Technician
- **Ticket skills by category:** Hardware 67 · Network 40 · Email 31 · Access 17 · Software 12

### Coddy certificates

| Completed | Certificate | Lessons | What it covers |
| --- | --- | --- | --- |
| 2026-11-15 | Cybersecurity: Security Fundamentals | — | Working as a new security analyst: investigating alerts, reviewing access, strengthening passwords, handling email attacks, verifying authorization, and containing and recovering from an incident |
| 2026-11-14 | **Computer Networking learning path** | 282 | The full path: Linux command line, OSI model, IP addressing and subnetting, networking with the terminal, and LAN labs |
| 2026-11-14 | Introduction to Docker | — | Container basics from the terminal, including images |
| 2026-11-14 | LAN Labs | 35 | Building, addressing and troubleshooting small networks: hosts, switches, routers, IPv4 addresses and masks, ARP, default gateways, routing tables, and common LAN faults |
| 2026-11-10 | [Networking with the Terminal](https://coddy.tech/certifications/tj6FfM-qnnXQ5) | 47 | Clients and servers, sending HTTP requests with `curl`, and step-by-step reachability troubleshooting from the command line |
| 2026-11-08 | [IP Addressing and Subnetting](https://coddy.tech/certifications/tj6FfM-LDYK7g) | 46 | Binary, IPv4 structure, subnet masks, CIDR, subnetting drills, private ranges, network planning with VLSM, intro to IPv6 |
| 2026-11-07 | [The OSI Model](https://coddy.tech/certifications/tj6FfM-cZAW4t) | 32 | All seven layers, MAC addresses and ARP, IP and routing, TCP vs. UDP and ports, encapsulation, and a packet's full journey |
| 2026-11-05 | [Terminal Fundamentals](https://coddy.tech/certifications/tj6FfM-terminal-JRk84c) | 82 | Navigating and managing files and directories, wildcards, reading file content, pipes and `grep`, file permissions |

### Coddy hands-on projects

| Project | What I built |
| --- | --- |
| Backup Script | A Bash script that prompts for a source directory, creates a timestamped backup folder (`date +%Y%m%d_%H%M%S`), copies the files and reports status at each step |
| Log Analyzer | Command-line log analysis project (Terminal Fundamentals) |
| Organize Photos | Reorganized files across folders with `mv`, `cp` and `rm`, then verified the final structure with `ls` |
| File Organizer by Type | Final challenge of Terminal Fundamentals |
| Greeting App | Completed project in the Computer Networking path |

**In progress:**
- Cybersecurity: Investigating a Breach (15/20 lessons): tracing suspicious programs to their source, saving evidence, removing persistence and proving the recovery
- Git version control (27/58 lessons; branching next)
- Up next: Cybersecurity: Stopping the Spread (tracing suspicious connections, containing affected computers, restricting access)

---

## Skills

- **Now:** OSI model, IPv4 addressing and subnetting (CIDR, VLSM), LAN troubleshooting (ARP, gateways, routing tables), command-line network troubleshooting (`curl`), Linux terminal (pipes, `grep`, wildcards, permissions), Bash scripting, Git basics, Docker basics, incident investigation and recovery basics (alerts, evidence, containment), help desk ticket troubleshooting (hardware, network, email, access, software)
- **Next:** Azure administration, Entra ID, KQL, Microsoft Sentinel, Terraform/Bicep, security frameworks (NIST)

---

## Weekly log

Week-by-week progress lives in [PROGRESS.md](PROGRESS.md).
