# Awesome-Desktop-As-A-Service

## Top Desktop as a Service (DaaS) Platforms Ecosystem
**Curated List of SaaS Products & Open-Source GitHub Projects**
*Focused on Cloud Desktops, Virtual Desktop Infrastructure (VDI), Remote Workspaces, Browser-Based Desktops & Secure Remote Access*
**Last updated: September 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Desktop as a Service (DaaS)**. These systems deliver Windows or Linux desktops (and applications) from the cloud or self-hosted infrastructure to end users via browser or client.

**Examples** include Amazon WorkSpaces, Azure Virtual Desktop, Citrix DaaS, VMware Horizon Cloud (Omnissa), Nerdio, Shells, Kasm Workspaces, Workspot, Apporto, and V2 Cloud (the category leaders).

**Open-source emphasis**: Full managed DaaS is largely commercial, but strong open building blocks exist—**Kasm** (community edition / open components), **Apache Guacamole**, **FreeRDP**, **xrdp**, and related remote desktop stacks. This section expands those options and is realistic about the commercial gap for enterprise-scale managed desktops.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms
- **[Amazon WorkSpaces](https://aws.amazon.com/workspaces/)**  
  AWS-managed Desktop as a Service for Windows and Linux desktops with flexible hourly or monthly pricing and GPU options.

- **[Azure Virtual Desktop](https://azure.microsoft.com/products/virtual-desktop)**  
  Microsoft’s cloud VDI platform for multi-session and personal Windows desktops on Azure, tightly integrated with Microsoft 365 and identity.

- **[Citrix DaaS](https://www.citrix.com/)**  
  Enterprise Desktop-as-a-Service and virtual apps platform known for protocol performance, management, and hybrid delivery.

- **[VMware Horizon Cloud / Omnissa Horizon](https://www.omnissa.com/)**  
  Cloud and hybrid virtual desktop platform for delivering Windows desktops and applications at scale.

- **[Nerdio](https://nerdio.net/)**  
  Management and automation platform that simplifies Azure Virtual Desktop and Windows 365 operations for MSPs and enterprises.

- **[Shells](https://www.shells.com/)**  
  Consumer and prosumer cloud computer / DaaS offering for personal cloud desktops accessible from any device.

- **[Kasm Workspaces](https://kasmweb.com/)**  
  Containerized streaming platform for browser-based desktops and apps (community and commercial editions)—strong open components.

- **[Workspot](https://www.workspot.com/)**  
  Enterprise cloud desktop platform focused on secure, high-performance virtual desktops across clouds.

- **[Apporto](https://www.apporto.com/)**  
  Browser-based virtual desktop and application delivery platform often used in education and training.

- **[V2 Cloud](https://v2cloud.com/)**  
  Cloud desktop service providing Windows desktops as a service for businesses and remote teams.

## Open-Source GitHub Projects
- **[Kasm Workspaces (community / open components)](https://github.com/kasmtech)**  
  Containerized workspace and browser isolation platform with open-sourced images and KasmVNC—self-hostable browser-based desktops and apps.

- **[KasmVNC](https://github.com/kasmtech/KasmVNC)**  
  Modern, web-based VNC server focused on secure browser access to Linux desktops and applications.

- **[Apache Guacamole](https://github.com/apache/guacamole-server)**  
  Clientless open-source remote desktop gateway—access desktops and apps via browser using RDP, VNC, and SSH without plugins.

- **[FreeRDP](https://github.com/FreeRDP/FreeRDP)**  
  Open-source implementation of the Remote Desktop Protocol (RDP) used as a foundation for many remote desktop solutions.

- **[xrdp](https://github.com/neutrinolabs/xrdp)**  
  Open-source RDP server for Linux that allows connections from standard RDP clients.

- **[abcdesktop.io](https://github.com/abcdesktopio)**  
  Open-source Kubernetes-native virtual desktop and remote application platform for self-hosted DaaS-style delivery.

- **[TigerVNC / TurboVNC](https://github.com/TigerVNC/tigervnc)**  
  High-performance open-source VNC implementations commonly used for remote Linux desktops.

- **[RustDesk](https://github.com/rustdesk/rustdesk)**  
  Open-source remote desktop software that can be self-hosted as an alternative to commercial remote-access tools.

- **[X2Go](https://github.com/)**  
  Open-source remote desktop solution based on NX technology for Linux terminal services.

- **[Documentation and self-hosted DaaS open playbooks](https://guacamole.apache.org/)**  
  Guides for deploying Guacamole, Kasm community stacks, or xrdp/FreeRDP-based remote desktop environments.

### Additional Strong Open-Source Options
- Building browser-accessible desktops with **Apache Guacamole** in front of RDP/VNC/SSH backends.
- Using **Kasm** community edition or container images for isolated, browser-streamed workspaces.
- Deploying **xrdp + FreeRDP** or VNC stacks for Linux remote desktops on your own infrastructure.
- Accepting that fully managed Windows Cloud PCs, enterprise multi-session scale, protocol optimization, identity integration, and support still favor commercial DaaS (Azure Virtual Desktop, Windows 365, Amazon WorkSpaces, Citrix, Horizon, Workspot, etc.).
- Focusing open-source efforts on data residency, cost control, and secure browser-based access.

**Frameworks for building custom systems**: Provision VMs or containers → expose via xrdp/VNC or stream with Kasm → front with Guacamole for browser access → manage identity and policies yourself. Suitable for technical teams and privacy-focused deployments. Most enterprises still use commercial DaaS for operational simplicity and Windows desktop support.

## How to Contribute
1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer
- This is a **community-curated** list — not exhaustive and not an endorsement.
- Remote desktops handle user sessions and potentially sensitive data. Open-source deployments require strong authentication, network security, and patching. This list is not security advice.

---
**Made for IT admins, platform engineers, and open-source remote-desktop advocates.**
Let's keep desktops accessible, secure, and as open as practical.
