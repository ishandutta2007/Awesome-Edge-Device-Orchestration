# Awesome Edge Device Orchestration 🚀

![Awesome Edge Device Orchestration Banner](./assets/banner.svg)

<p align="center">
  <a href="https://github.com/ishandutta2007/Awesome-Awesome-Awesome"><img src="https://img.shields.io/badge/Awesome-%E2%9C%94-blueviolet?style=flat-square&logo=github" alt="Awesome"/></a>
  <a href="https://discord.gg/jc4xtF58Ve"><img src="https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Discord" /></a>
  <a href="https://github.com/ishandutta2007/Awesome-Edge-Device-Orchestration/stargazers"><img src="https://img.shields.io/github/stars/ishandutta2007/Awesome-Edge-Device-Orchestration?style=flat-square" alt="GitHub_Stars"/></a>
  <a href="https://github.com/ishandutta2007/Awesome-Edge-Device-Orchestration/network/members"><img src="https://img.shields.io/github/forks/ishandutta2007/Awesome-Edge-Device-Orchestration?style=flat-square" alt="GitHub Forks"/></a>
  <a href="https://github.com/ishandutta2007/Awesome-Edge-Device-Orchestration/blob/main/LICENSE"><img src="https://img.shields.io/github/license/ishandutta2007/Awesome-Edge-Device-Orchestration?style=flat-square" alt="License"/></a>
  <a href="https://github.com/ishandutta2007"><img alt="GitHub followers" src="https://img.shields.io/github/followers/ishandutta2007?label=Follow" /></a>
</p>

## 🌐 Overview & Ecosystem Map

Welcome to the **Awesome Edge Device Orchestration** ecosystem guide! 🌐 This curated repository tracks top-tier **SaaS platforms** and production-ready **open-source projects** for **Edge Device Orchestration**, **Fleet Management**, **Remote Provisioning**, **Over-The-Air (OTA) Updates**, and **Edge Workload Orchestration**.

Whether you are deploying lightweight Kubernetes clusters across thousands of remote IoT gateways, managing OTA firmware rollbacks on microcontrollers, or orchestrating GPU-accelerated AI models at the enterprise edge, this guide helps infrastructure architects, DevOps engineers, and embedded developers select the optimal tooling.

---

## 📑 Table of Contents

- [☁️ SaaS / Hosted Platforms](#-saas--hosted-platforms)
- [🔓 Open-Source Projects](#-open-source-projects)
  - [☸️ Lightweight Kubernetes for Edge](#️-lightweight-kubernetes-for-edge)
  - [📦 Edge Orchestration & Control Planes](#-edge-orchestration--control-planes)
  - [📡 Device Management & IoT Frameworks](#-device-management--iot-frameworks)
  - [🔄 OTA Updates & Firmware Management](#-ota-updates--firmware-management)
  - [⚡ Edge AI & Virtualization](#-edge-ai--virtualization)
- [🤝 How to Contribute](#-how-to-contribute)
- [💖 Support & Sponsorship](#-support--sponsorship)
- [📈 Star History](#-star-history)
- [⚠️ Disclaimer](#️-disclaimer)

---

## ☁️ SaaS / Hosted Platforms

> [!NOTE]
> **Market Size & Industry Structure:**  
> The global Edge Device Orchestration & Management sector is estimated at **$5.2 Billion (2026)** and is projected to expand at a CAGR of ~28% through 2032. The sector is **highly fragmented**, characterized by specialized category leaders across virtualization, container fleets, and OTA security rather than a single "winner-take-all" platform.

The table below summarizes top commercial and hosted SaaS edge management platforms, sorted in descending order by **Company Scale / Valuation / Funding**:

| Platform 🚀 | Description 📝 | Pricing (Specific Starting Tier) 💵 | Free Tier Limit / Trial 🆓 | Company Scale / Revenue / Valuation 🏢 |
| :--- | :--- | :--- | :--- | :--- |
| **[Canonical Ubuntu Core](https://ubuntu.com/core)** | Immutable, transactional Linux OS for IoT and edge devices with snap packaging and automatic rollbacks. | Free OS; Commercial support starts at **$25/device/year** (Ubuntu Pro for Infrastructure) | **Free for personal use** on up to 5 machines (Ubuntu Pro free tier) | **~$345M Annual Revenue** (Canonical Ltd.) |
| **[ZEDEDA](https://zededa.com/)** | Cloud-native edge virtualization and zero-trust orchestration platform built on Linux Foundation EVE-OS. | Custom Enterprise quote (typically starts at **~$2–$5/device/month** at volume) | **30-Day Free Trial** (Includes full cloud dashboard & demo cluster access) | **~$400M Valuation** ($130M total VC raised) |
| **[Foundries.io](https://foundries.io/)** | Cloud-native DevSecOps platform (FoundriesFactory) for building and updating secure Linux IoT & edge devices. | Commercial plans start at **$1,500/month** (Flat fee per product line, unlimited devices) | **Free Community Edition** for non-commercial development & evaluation | **Acquired by Qualcomm** in 2024 ($1M–$10M ARR subsidiary) |
| **[Balena](https://www.balena.io/)** | Container-based IoT fleet management platform (balenaCloud) with automated OTA updates and remote access. | Prototype plan starts at **$159/month** (includes first 20 devices, $2/device extra) | **Free Forever for up to 10 devices** (Full balenaCloud feature access) | **~$8.3M Annual Revenue** ($35.1M total VC funding) |
| **[Portainer](https://www.portainer.io/)** | Centralized container management platform for Docker, Kubernetes, and Swarm across cloud and edge nodes. | Portainer Business starts at **$149/year** (per environment/cluster node) | **Free Forever for up to 3 nodes** (Portainer Business 3-node free license) | **~$4.7M Annual Revenue** (~$13.4M total VC funding) |
| **[Mender](https://mender.io/)** | End-to-end OTA software update manager for embedded Linux devices and microcontrollers (Zephyr RTOS). | Basic hosted plan starts at **$34/month** (includes 50 devices) | **12-Month Free Trial** for Enterprise plan (up to 10 devices, no credit card required) | **~$870K Annual Revenue** (Northern.tech subsidiary) |

---

## 🔓 Open-Source Projects

Below is a curated list of active open-source edge orchestration repositories. Each project features a live GitHub Stars_Count badge that links directly to its stargazers page. Sorted by **GitHub Stars_Count (Descending)** 🌟.

### ☸️ Lightweight Kubernetes for Edge

- **[K3s](https://github.com/k3s-io/k3s)** <a href="https://github.com/k3s-io/k3s/stargazers"><img src="https://img.shields.io/github/stars/k3s-io/k3s?style=social&color=white" alt="K3s Stars"/></a>  
  Lightweight, fully compliant Kubernetes distribution packaged as a single binary. Optimized for resource-constrained edge gateways and ARM/x86 devices.

- **[MicroK8s](https://github.com/canonical/microk8s)** <a href="https://github.com/canonical/microk8s/stargazers"><img src="https://img.shields.io/github/stars/canonical/microk8s?style=social&color=white" alt="MicroK8s Stars"/></a>  
  Zero-ops, pure upstream Kubernetes distribution by Canonical. Includes built-in high availability, automatic updates, and edge add-on management.

- **[K0s](https://github.com/k0sproject/k0s)** <a href="https://github.com/k0sproject/k0s/stargazers"><img src="https://img.shields.io/github/stars/k0sproject/k0s?style=social&color=white" alt="K0s Stars"/></a>  
  Frictionless, single-binary Kubernetes distribution with zero host dependencies. Supports x86-64, ARM64, and RISC-V architectures for versatile edge deployments.

### 📦 Edge Orchestration & Control Planes

- **[KubeEdge](https://github.com/kubeedge/kubeedge)** <a href="https://github.com/kubeedge/kubeedge/stargazers"><img src="https://img.shields.io/github/stars/kubeedge/kubeedge?style=social&color=white" alt="KubeEdge Stars"/></a>  
  CNCF Graduated Kubernetes-native edge computing framework. Extends native container orchestration to edge nodes with offline autonomy and MQTT device state sync.

- **[OpenYurt](https://github.com/openyurtio/openyurt)** <a href="https://github.com/openyurtio/openyurt/stargazers"><img src="https://img.shields.io/github/stars/openyurtio/openyurt?style=social&color=white" alt="OpenYurt Stars"/></a>  
  CNCF Hosted open-source platform extending upstream Kubernetes to edge compute scenarios, supporting node autonomy, edge-cloud network tunneling, and unit orchestration.

- **[Baetyl](https://github.com/baetyl/baetyl)** <a href="https://github.com/baetyl/baetyl/stargazers"><img src="https://img.shields.io/github/stars/baetyl/baetyl?style=social&color=white" alt="Baetyl Stars"/></a>  
  LF Edge project extending cloud computing, data processing, and AI inference to edge devices with support for 30+ industrial protocols and MLflow integration.

- **[SuperEdge](https://github.com/superedge/superedge)** <a href="https://github.com/superedge/superedge/stargazers"><img src="https://img.shields.io/github/stars/superedge/superedge?style=social&color=white" alt="SuperEdge Stars"/></a>  
  An open-source container management system for edge computing that extends native Kubernetes to edge sites without modifying core Kubernetes code.

- **[Eclipse ioFog Agent](https://github.com/eclipse-iofog/Agent)** <a href="https://github.com/eclipse-iofog/Agent/stargazers"><img src="https://img.shields.io/github/stars/eclipse-iofog/Agent?style=social&color=white" alt="Eclipse ioFog Agent Stars"/></a>  
  Complete open-source edge computing platform for running microservices at scale. Features universal edge container environment, Skupper overlay networking, and air-gapped deployment support.

### 📡 Device Management & IoT Frameworks

- **[EdgeX Foundry](https://github.com/edgexfoundry/edgex-go)** <a href="https://github.com/edgexfoundry/edgex-go/stargazers"><img src="https://img.shields.io/github/stars/edgexfoundry/edgex-go?style=social&color=white" alt="EdgeX Foundry Stars"/></a>  
  LF Edge project building an open, vendor-neutral microservice framework for IoT edge computing and interoperability between industrial devices and clouds.

- **[Intel Edge Manageability Framework (EMF)](https://github.com/open-edge-platform/edge-manageability-framework)** <a href="https://github.com/open-edge-platform/edge-manageability-framework/stargazers"><img src="https://img.shields.io/github/stars/open-edge-platform/edge-manageability-framework?style=social&color=white" alt="Intel EMF Stars"/></a>  
  Open-source edge manageability stack from Intel's Open Edge Platform for zero-touch provisioning, hardware/software telemetry, cluster orchestration, and governance.

- **[Fledge](https://github.com/fledge-iot/fledge)** <a href="https://github.com/fledge-iot/fledge/stargazers"><img src="https://img.shields.io/github/stars/fledge-iot/fledge?style=social&color=white" alt="Fledge Stars"/></a>  
  LF Edge open-source framework for Industrial IoT (IIoT), focused on sensor integration, data aggregation, edge analytics, and cloud streaming.

### 🔄 OTA Updates & Firmware Management

- **[RAUC](https://github.com/rauc/rauc)** <a href="https://github.com/rauc/rauc/stargazers"><img src="https://img.shields.io/github/stars/rauc/rauc?style=social&color=white" alt="RAUC Stars"/></a>  
  Safe and secure lightweight update client for embedded Linux devices. Handles A/B dual-bank updates with cryptographic signature verification.

- **[Mender Engine](https://github.com/mendersoftware/mender)** <a href="https://github.com/mendersoftware/mender/stargazers"><img src="https://img.shields.io/github/stars/mendersoftware/mender?style=social&color=white" alt="Mender Stars"/></a>  
  Open-source OTA software update manager for Linux devices and MCU microcontrollers, providing atomic dual-system updates with automatic rollback.

- **[Eclipse hawkBit](https://github.com/eclipse-hawkbit/hawkbit)** <a href="https://github.com/eclipse-hawkbit/hawkbit/stargazers"><img src="https://img.shields.io/github/stars/eclipse-hawkbit/hawkbit?style=social&color=white" alt="Eclipse hawkBit Stars"/></a>  
  Domain-independent backend framework for rolling out software and firmware updates to constrained edge devices, gateways, and IoT nodes.

### ⚡ Edge AI & Virtualization

- **[ACRN Hypervisor](https://github.com/projectacrn/acrn-hypervisor)** <a href="https://github.com/projectacrn/acrn-hypervisor/stargazers"><img src="https://img.shields.io/github/stars/projectacrn/acrn-hypervisor?style=social&color=white" alt="ACRN Hypervisor Stars"/></a>  
  Flexible, lightweight open-source reference hypervisor built with safety-critical workloads and IoT edge virtualization in mind.

- **[nos](https://github.com/nebuly-ai/nos)** <a href="https://github.com/nebuly-ai/nos/stargazers"><img src="https://img.shields.io/github/stars/nebuly-ai/nos?style=social&color=white" alt="nos Stars"/></a>  
  Open-source Kubernetes module designed to optimize GPU utilization at the edge for AI model inference and resource scheduling.

- **[EVE-OS (Project EVE)](https://github.com/lf-edge/eve)** <a href="https://github.com/lf-edge/eve/stargazers"><img src="https://img.shields.io/github/stars/lf-edge/eve?style=social&color=white" alt="EVE-OS Stars"/></a>  
  LF Edge Edge Virtualization Engine providing open, standardized hardware-assisted virtualization and container runtimes for enterprise edge nodes.

- **[Sedna (KubeEdge)](https://github.com/kubeedge/sedna)** <a href="https://github.com/kubeedge/sedna/stargazers"><img src="https://img.shields.io/github/stars/kubeedge/sedna?style=social&color=white" alt="Sedna Stars"/></a>  
  Edge AI suite powered by KubeEdge, enabling joint cloud-edge AI inference, incremental learning, federated learning, and lifetime learning.

---

## 🤝 How to Contribute

Contributions are warmly welcomed! 💖 If you know an awesome edge device orchestration tool, OTA updater, or lightweight Kubernetes platform that should be included:

1. Fork this repository. 🍴
2. Add your entry to `README.md` keeping formatting consistent (include name, links, description, and Stars_Badges).
3. Submit a Pull Request (PR) with a brief summary of the project.

Please check existing items before submitting to prevent duplicate entries!

---

## 💖 Support & Sponsorship

If you find this curated list valuable for your edge infrastructure research or projects, please consider supporting the project:

- ⭐ **Star this repository** to help others discover it!
- 🔀 **Fork & Share** with your colleagues, DevOps team, or IoT community.
- ☕ **Sponsor / Buy Me a Coffee:** Support ongoing maintenance and curation on the [GitHub Sponsor Dashboard](https://github.com/sponsors/ishandutta2007).

Thank you for your support! 🙏

---

## 📈 Star History

[![Star History Chart](https://star-history.dera.page/svg?repos=ishandutta2007/Awesome-Edge-Device-Orchestration&type=date&legend=top-left)](https://star-history.dera.page/#ishandutta2007/Awesome-Edge-Device-Orchestration&type=date&legend=top-left)

---

## ⚠️ Disclaimer

- This list is **community-curated** for informational and research purposes only and does not constitute an endorsement.
- Edge device orchestration platforms handle high-privilege device credentials and remote execution capabilities; always perform thorough security reviews before deploying in production environments.
