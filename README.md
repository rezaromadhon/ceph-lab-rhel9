# Ceph Reef 3-Node Lab (RHEL 9 + cephadm)

## 📌 Project Overview
This project is a hands-on Ceph storage cluster lab built using 3 virtual machines running RHEL 9 and deployed using `cephadm`.

The goal is to simulate a production-like distributed storage system for learning and portfolio purposes.

---

## 🏗️ Architecture

---

## 🌐 Network Design

- Cluster Network: `192.168.56.0/24`
- All nodes communicate via internal bridge network

| Host | IP Address | Role |
|------|-----------|------|
| vm1  | 192.168.56.10 | MON + MGR + OSD |
| vm2  | 192.168.56.11 | MON + OSD |
| vm3  | 192.168.56.12 | MON + OSD |

---

## ⚙️ Tech Stack

- RHEL 9
- Ceph Reef
- cephadm (container-based deployment)
- VirtualBox / KVM (lab environment)

---

## 📊 Cluster Status

Cluster is currently running in healthy state:

- 3 Monitors (quorum active)
- 1 Manager active + standby
- 3 OSDs active
- HEALTH_OK

---

## 📁 Evidence

All real cluster outputs are documented in `/docs`:

- ceph cluster status
- host inventory
- OSD tree
- topology design

---

## 🎯 Learning Objectives

- Ceph distributed storage architecture
- MON / MGR / OSD roles
- cephadm deployment workflow
- Linux storage networking
- Git + GitHub documentation workflow

---

## 👤 Author

Reza Romadhon
