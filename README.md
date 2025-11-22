# Active Directory in VMware

[![Status](https://img.shields.io/badge/status-colplete-brightgreen)](https://gitlab.com/madachi01/active-directory-in-vmware/-/commits/main)
[![Windows Server](https://img.shields.io/badge/Windows%20Server-2025-blue)](https://www.microsoft.com/en-us/windows-server)
[![VMware](https://img.shields.io/badge/VMware-Workstation-orange)](https://www.vmware.com/products/desktop-hypervisor/workstation-and-fusion)
[![Homelab](https://img.shields.io/badge/Homelab-Setup-lightgrey)](https://linuxblog.io/home-lab-beginners-guide-hardware/)

Simulating an enterprise-grade network environent with a personal homelab, this project brings together Windows Server 2025 and multiple client OSs to recreatea fully functional Active Directory domain - complete with users, groups, policies, amd automation.

<img src="https://github.com/madachi01/Active-Directory-in-VMware/blob/main/Images/Setup_Preview.png?raw=true" width=75%>

---

## Table of Contents
- [Overview](#overview)
- [Network Design](#network-design)
- [Core Features and Takeaways](#core-features-and-takeaways)
- [Reflection](#reflection)

---

## Overview

Developed to explore real-world systemsadministration in a flexible environment, this lab mirrors modern IT infrastructure. I configured a domain, managed Group Policy Objects (GPOs), automated tasks, and experimented with cross-OS compatability, file sharing, and integration tools like JAMF and Ansible.

---

## Network Design

<img src="https://github.com/madachi01/Active-Directory-in-VMware/blob/main/Images/Network_Topology.png?raw=true" width=65%>

The network connects three segments:
- **ISP (orange)**
- **Home (green)**
- **Virtual Lab (blue)**

Each segment has defined roles and protocols, simulating enterprise-grade segmentation for secure and efficient communication.

---

## Core Features and Takeaways

- **VM Snapshots** - Instant recovery points for safe experimentation, allowing fast restoration from errors or failures.
<img src="https://github.com/madachi01/Active-Directory-in-VMware/blob/main/Images/Snapshot_Manager.png?raw=true" width=65%>

- **VM Cloning** - Rapidly deploy additional client machines for testing large-scale environments.
<img src="https://github.com/madachi01/Active-Directory-in-VMware/blob/main/Images/Clone_VM_Wizard.png?raw=true" width=65%>

- **Hardware Efficiency** - A single host replaces multiple physical systems, maximizing flexibility while minimizing hardware requirements.
<img src="https://cdn.prod.website-files.com/60494527fea68422687bfcf1/60620c3038c7591706fb8381_what-is-a-hypervisor-1024x695.png" width=65%>

---

## Reflection

Building this environment strengthened my technical skills and ability to troubleshoot effectively. Each test, error, and solution enhanced my understanding of structure, reliability, and controlled experimentation. The lab continues to evolve as I explore new tools and refine automation workflows.
