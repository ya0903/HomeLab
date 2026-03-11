# 🖥️ Homelab Infrastructure Overview

> Personal self‑hosted infrastructure for media streaming, automation, development, AI experimentation and network services.

---

## 📌 Purpose

This homelab is designed to:

• Host a large self‑managed media streaming platform

• Provide private cloud services and data storage

• Run containerised applications for automation and monitoring

• Experiment with AI and local large language models

• Serve as a learning platform for networking, DevOps and systems engineering

• Act as a practical portfolio demonstrating real‑world infrastructure management

All sensitive data, such as public IPs, domains, credentials and exact storage paths are intentionally redacted for privacy.

---

## 🧰 Core Infrastructure

### **Compute**

• Multi‑core desktop server CPU

• Dedicated GPU acceleration for media transcoding and AI workloads

• High‑capacity RAM for virtualisation and container workloads

### **Storage**

• NVMe SSD for operating system and container runtime

• High‑speed SSD for metadata and cache

• Multiple enterprise HDDs for mass media storage

• Automated library organisation and media indexing

### **Networking**

• High‑speed home broadband connection

• Multi‑router architecture

• Secure remote access via encrypted VPN tunnel

• Reverse proxy for secure external service routing

• Internal DNS‑level filtering and ad blocking

• VLAN segmentation for service isolation

---

## 🐳 Containerised Services (Docker)

All services are deployed using containerisation for portability, reliability and simplified updates.

### 🎬 Media & Content Management

• Jellyfin — self‑hosted media streaming server
• Jellyseerr — media request management
• Sonarr — TV automation and indexing
• Radarr — film automation and indexing
• Lidarr — music automation and indexing
• Bazarr — subtitle management
• Prowlarr — indexer aggregation manager
• Jackett — torrent indexer proxy
• qBittorrent — download client
• FlareSolverr — anti‑bot bypass service
• Komga — manga and comics server
• Kaizoku — manga downloader
• Navidrome — music streaming server

### ☁️ Cloud & Productivity

• Nextcloud — private cloud storage platform
• Vaultwarden — secure password manager
• File browser — web‑based file management

### 🤖 AI & Local LLM Services

• Local LLM runtime environment
• Web UI for local model interaction
• GPU‑accelerated inference services
• Text‑to‑speech services
• Image generation services

### 📊 Monitoring & Analytics

• Grafana — visual monitoring dashboards
• Prometheus — metrics collection
• Uptime monitoring service
• Playback reporting and usage statistics
• System resource monitoring

### 🔐 Security & Access Control

• Reverse proxy server with HTTPS encryption
• Authentication and identity management
• VPN server for secure remote access
• Ad and tracker blocking DNS server
• Intrusion prevention and rate‑limiting service
• Container isolation policies

### 🌐 Network & Utility Services

• Dynamic DNS updater
• Wake‑on‑LAN remote power management
• Container management dashboard
• Remote desktop access service
• Game server management panel
• Offline knowledge library server

---

## 🎨 Media Server Customisation

The media platform includes extensive UI and feature customisation:

• Custom themes and interface redesign

• Metadata enhancement plugins

• Intro and credits detection

• Advanced playback statistics

• Custom user profiles and access controls

• Kids‑restricted media libraries

• GPU hardware transcoding

• Direct‑play optimisation for supported devices

---

## 🗂️ Infrastructure Management

### **Deployment Method**

• Docker Compose stack orchestration
• Automatic container restart policies
• Scheduled maintenance and backups
• Centralised configuration management

### **Data Strategy**

• Metadata stored on high‑speed cache drives
• Media stored on large‑capacity arrays
• Automated backups of critical configurations
• Redundant storage for important data

### **Performance Optimisation**

• GPU hardware acceleration
• Metadata caching
• Filesystem optimisation
• Network throughput tuning
• Container resource allocation

---

## 📈 Learning & Engineering Focus

This homelab is used to develop practical experience in:

• Linux server administration
• Container orchestration
• Network architecture design
• Secure remote infrastructure management
• Reverse proxy configuration
• VPN tunnelling and encryption
• Storage planning and optimisation
• GPU workload acceleration
• Monitoring and observability tooling
• Self‑hosting best practices

---

## 🧪 Ongoing Experiments

• AI‑assisted media tagging and metadata enrichment
• Automated media format optimisation
• Advanced caching strategies
• Network segmentation improvements
• Container security hardening
• Scalable storage expansion planning

---

## 🔄 Maintenance Workflow

### Regular Tasks

• Container image updates
• System performance monitoring
• Storage health checks
• Backup verification
• Security patching

### Upgrade Workflow

1. Test changes in isolated containers
2. Validate performance and stability
3. Deploy to production stack
4. Monitor metrics and logs

---

## 🎯 Project Goals

• Maintain a fully self‑hosted digital ecosystem
• Reduce reliance on third‑party cloud services
• Achieve high‑availability media streaming
• Provide secure remote access to services
• Build a scalable infrastructure platform
• Continuously expand technical expertise

---

## ⚠️ Privacy Notice

This documentation intentionally omits or redacts:

• Public IP addresses
• Domain names
• Authentication credentials
• API keys
• Exact storage paths
• Personal identifying information

---

## 📜 Licence

This project documentation is shared for educational and portfolio purposes only.

---

**End of Overview**
