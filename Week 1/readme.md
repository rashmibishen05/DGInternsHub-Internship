# DG Interns HUB – Week 1 Project README

## 1. Project Overview

The purpose of Week 1 is to establish a secure cybersecurity practice environment and understand the essential concepts of Linux administration, computer networking, and information security.

This week combines theoretical study with practical exercises using virtual machines, Linux commands, network diagnostic tools, and beginner cybersecurity training platforms. All activities should be documented clearly to demonstrate learning progress and technical understanding.

## 2. Project Directory Layout

The following structure will keep the project's study materials, practical evidence, and reports organized.

```text
DG Interns HUB/
└── Week 1/
    ├── Notes/
    │   ├── 01_Cybersecurity_Fundamentals
    │   ├── 02_CIA_Triad
    │   ├── 03_Security_Career_Roles
    │   ├── 04_OSI_and_TCPIP_Models
    │   ├── 05_Networking_Protocols_and_Ports
    │   ├── 06_Linux_Filesystem_and_Permissions
    │   ├── 07_Threats_Vulnerabilities_and_Risks
    │   ├── 08_Virtual_Machine_Networking
    │   └── 09_Cybersecurity_Law_and_Ethics
    │
    ├── Writeups/
    │   ├── TryHackMe/
    │   │   └── Individual room reports
    │   └── Bandit/
    │       └── Level_00 through Level_10
    │
    ├── Findings/
    │   ├── Virtual_Machine_Setup/
    │   │   └── VM configuration, IP details and snapshots
    │   ├── Ubuntu_Exercises/
    │   │   └── Accounts, groups, permissions, commands and cron
    │   ├── Network_Documentation/
    │   │   └── IP inventory and topology diagram
    │   └── Bandit_Evidence/
    │       └── Progress screenshots without credentials
    │
    ├── Cheat Sheet/
    │   └── Linux_Command_Reference
    │
    ├── Week_1_Work_Report.pdf
    ├── Week_1_Presentation.pptx
    └── Week_1_README.docx
```

Folder names may be adjusted to match the internship submission requirements, provided the required materials remain easy to locate.

## 3. Weekly Activity Plan

### Activity 1: Study Cybersecurity Fundamentals

Prepare separate theory documents explaining the essential concepts introduced in the assignment.

Topics to cover include:

- The meaning and objectives of cybersecurity.
- The Confidentiality, Integrity, and Availability (CIA) triad.
- Responsibilities of SOC analysts, penetration testers, and incident responders.
- The OSI and TCP/IP networking models.
- IP and MAC addresses, DNS, DHCP, and commonly used ports.
- Linux directories, ownership, permissions, and SUID.
- The differences between threats, vulnerabilities, exploits, and risks.
- Virtual machine networking configurations.
- Authorization, testing scope, Rules of Engagement, and applicable cybercrime legislation.

Use clear explanations, comparison tables, and practical examples. Write the material independently and cite sources when required.

### Activity 2: Configure the Virtual Lab

Set up the required virtual machines using VirtualBox:

- Kali Linux for cybersecurity learning and authorized testing.
- Ubuntu for Linux administration exercises.
- Windows 10/11 Evaluation for Windows networking and system practice.

Configure the network according to the lab requirements. Use Host-only networking or a carefully configured NAT Network to allow the intended lab communication.

Before conducting exercises:

1. Confirm the operating systems and virtual network adapters.
2. Record the assigned IP addresses and subnet information.
3. Take clean snapshots of the virtual machines.
4. Verify communication between the intended systems.
5. Save screenshots of the actual configuration and test results.

**Safety note:** Intentionally vulnerable machines should not be connected using Bridged networking, as this can expose their services to the physical network.

### Activity 3: Complete Ubuntu Administration Exercises

Use the Ubuntu VM to practice basic account administration and system management.

Required activities:

- Create three user accounts.
- Create two groups.
- Configure a shared directory with appropriate ownership and permissions.
- Verify that the intended users can access the shared resources.
- Practice file searching, text filtering, process inspection, and network socket commands.
- Schedule a cron job and verify its execution.
- Record at least 30 commands with their actual output and explanations.

Useful commands include `find`, `grep`, `ps`, `ss -tulpn`, `chmod`, `chown`, `ip a`, and `crontab`.

Keep the command log and supporting screenshots in `Findings/Ubuntu_Exercises/`.

### Activity 4: Document the Lab Network

Create a network inventory for all three virtual machines.

For each machine, record:

| Information | Description |
|---|---|
| VM name | The name assigned in VirtualBox |
| Operating system | Installed OS and version |
| IP address | Actual address and prefix |
| Default gateway | Configured gateway, if applicable |
| DNS server | Configured DNS resolver |
| Adapter mode | Host-only, NAT Network, or other configured mode |
| Connectivity | Actual ping and other diagnostic results |

Use Linux networking commands and Windows network utilities to collect the information.

Create a topology diagram in draw.io showing the virtual network and connected machines. Save the editable diagram and an exported image or PDF in `Findings/Network_Documentation/`.

### Activity 5: Work Through the Training Platforms

Complete the eight assigned TryHackMe rooms:

1. Search Skills
2. Learning Cyber Security
3. Linux Fundamentals Part 1
4. What is Networking
5. Introductory Networking
6. Networking Concepts
7. Pyramid Of Pain
8. Intro to LAN

Prepare a separate writeup for each room that is completed.

Each writeup should contain the room objective, important concepts, tasks completed, commands or tools used, challenges, and personal learning points.

Also complete OverTheWire Bandit levels 0–10. Keep an individual report for every level, describing the approach and lessons learned.

Never include Bandit passwords, authentication secrets, private keys, or tokens in writeups or screenshots.

### Activity 6: Prepare the Linux Command Reference

Develop a reference table with these columns:

| Column | Purpose |
|---|---|
| Linux Command | Command or command syntax |
| What It Does | Explanation of its function |
| When to Use It | Practical situation in which it is useful |

Include at least 30 entries covering navigation, file handling, permissions, user management, processes, networking, logs, and scheduled tasks.

Store the finished reference in the `Cheat Sheet/` directory.

### Activity 7: Assemble the Final Reports

Prepare the three required documentation files.

**A. Weekly Work Report (PDF)**

Summarize the week's objectives, lab configuration, exercises performed, technical observations, learning-platform progress, challenges, and next steps. Reference the evidence collected during the practical tasks.

**B. Weekly Presentation (PowerPoint)**

Present the project objectives, lab design, Linux administration exercises, networking concepts, training progress, significant findings, and key learning outcomes. Use genuine screenshots and keep the slides concise.

**C. Project README (Word document)**

Describe the project objective, directory layout, weekly activities, evidence requirements, safety rules, and completion status. This README serves as a guide to the entire Week 1 folder.

## 4. Evidence Management

Keep evidence organized by activity instead of collecting everything in one directory.

Recommended evidence includes:

- VirtualBox VM list and adapter configuration.
- IP configuration for Kali, Ubuntu, and Windows.
- Successful ping results where connectivity is permitted.
- Clean VM snapshots.
- User and group creation.
- Shared-directory ownership and permissions.
- Linux command outputs and cron verification.
- Network inventory and topology diagram.
- Completed training-room and Bandit progress evidence.

Screenshots must represent actual results. If a test fails, document the failure and investigation rather than modifying the evidence to suggest success.

## 5. Expected Week 1 Outcomes

By the end of Week 1, the following outcomes should be achieved:

- Foundational cybersecurity theory notes completed.
- Virtual machines configured with appropriate network isolation.
- VM network details recorded and connectivity tests documented.
- Linux users, groups, permissions, and shared-folder exercises completed.
- At least 30 Linux command outputs documented.
- A cron job created and verified.
- Assigned TryHackMe rooms completed and documented.
- OverTheWire Bandit levels 0–10 completed and documented.
- Network inventory and diagram completed.
- Linux command cheat sheet completed.
- Weekly work report and presentation completed.
- README reviewed and all evidence checked for accuracy and secrets.
