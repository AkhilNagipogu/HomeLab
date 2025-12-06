# 🏠 Homelab Documentation

This repository contains documentation of my personal **homelab setup** and the services I run.

I use **Proxmox VE** as the base hypervisor, with multiple virtual machines and containers running on top of it.  
For a personal homelab, Proxmox is a great choice due to its flexibility, ease of use, and powerful virtualization features.

> ⚠️ Warning: Homelabbing is highly addictive 🙂

---

## 🧱 Base Setup

- **Hypervisor:** Proxmox VE  
- **Workloads:** Virtual Machines + Containers  
- **Goal:** Learn virtualization, networking, self-hosting, and system administration through hands-on practice.

---

## 🔑 Essential Services

These are the **core services** that I consider essential for my homelab and keep running at all times:

    1. Twingate
    Secure remote access to my homelab without exposing ports.

    2. Cloudflare Tunnel  
    Safely exposes selected local services and websites to the internet.

    3. TrueNAS  
    Used for centralized storage and file management.

To keep the setup simple:
- A **lightweight container** runs Twingate and Cloudflare Tunnel
- A **dedicated VM** runs TrueNAS

This minimal setup covers secure access, storage, and external connectivity.

---

## ⚙️ Services I Currently Run

Below are the services I actively use in my homelab:

    1. Twingate 
     – Secure remote connection  

    2. Cloudflare Tunnel – Exposing services from the local network safely  

    3. Docker
     – Quick deployment and management of services  
    
    4. Immich
     – Self-hosted, open-source photo and video backup solution  
    
    5. Jellyfin
     – Media server for hosting my favorite movies


---

## 🎯 Why This Homelab?

This homelab exists primarily to:
- Learn Linux and system administration
- Understand virtualization and containers
- Experiment with self-hosted services
- Gain real-world experience beyond theory

All configurations here are **learning-focused**, not production-grade.

---

## 🚧 Work in Progress

This repository is a living document and will be updated as I:
- Add new services
- Improve security
- Optimize resource usage
- Learn new tools and technologies
