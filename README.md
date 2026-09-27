# Awesome-Edge-Device-Orchestration

## Top Edge Device Orchestration Platforms Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Fleet Management, Remote Provisioning, OTA Updates & Edge Workload Orchestration*  

**Last updated: September 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Edge Device Orchestration**. These tools help organizations deploy, manage, and operate workloads across distributed edge devices — from constrained IoT nodes to GPU-equipped edge servers — with centralized control planes, secure onboarding, and reliable software lifecycle management.



**Examples** include ZEDEDA, Balena, Portainer, Canonical Ubuntu Core, Mender, Foundries.io, KubeEdge, LF Edge, Eclipse ioFog, and ACRN (the category leaders).



**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, custom orchestration workflows, and transparent device management — ideal for teams that need full control over their edge infrastructure without per-device SaaS fees or vendor lock-in.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents



- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[ZEDEDA](https://zededa.com/)**  

  Edge virtualization and orchestration platform. Provides centralized management of edge applications and devices with security and lifecycle management. Built on Project EVE, which was contributed to LF Edge .



- **[Balena](https://www.balena.io/)**  

  IoT fleet management platform built on balenaOS (Linux-based, container-ready OS). Manages Docker containers on embedded devices with OTA updates, VPN access, and fleet monitoring. balenaOS is built on Yocto and runs on 90+ device types. Community Edition free, paid plans for larger fleets.



- **[Portainer](https://www.portainer.io/)**  

  Container management platform for Kubernetes, Docker, and Swarm. Provides a unified UI for managing edge devices and workloads with role-based access control. Community Edition free for up to 3 environments.



- **[Canonical Ubuntu Core](https://ubuntu.com/core)**  

  Immutable, transactional Linux OS designed for IoT and edge devices. Provides Snap-based application packaging with automatic rollback and over-the-air updates.



- **[Mender](https://mender.io/)**  

  End-to-end OTA software update manager for Linux devices. Open-source server available under Apache-2.0 license. Supports atomic updates with rollback, device inventory, and fleet management. Enterprise version offers on-prem hosting and fully managed service .



- **[Foundries.io](https://foundries.io/)**  

  Linux-based platform for IoT and edge device development. Provides secure OTA updates, device management, and container orchestration.



- **[Siemens Industrial Edge Management](https://www.siemens.com/)**  

  Industrial edge management platform with AI integration. PAC RADAR 2026 identifies Siemens as an outperformer with its Industrial AI Suite and software-defined automation vision .



- **[Lenovo XClarity One](https://www.lenovo.com/)**  

  Cloud-based unified management-as-a-service platform. Provides edge-to-cloud device communication, predictive failure analysis with generative AI, and secure management hub through local management hubs .



## Open-Source GitHub Projects



### Edge Orchestration & Management Platforms



- **[Intel Edge Manageability Framework (EMF)](https://github.com/open-edge-platform/edge-manageability-framework)**  

  Open-source infrastructure management solution from Intel's Open Edge Platform. Provides unified platform for managing diverse edge devices including secure zero-touch onboarding, hardware and software provisioning, cluster and application orchestration, observability, and governance. Supports both immutable OS (Edge Microvisor Toolkit) and traditional OS (Ubuntu LTS). Vendor-neutral with respect to orchestration solution. Part of Intel's Open Edge Platform .



- **[Eclipse ioFog](https://github.com/eclipse-iofog)**  

  Complete open-source edge computing platform for building and running applications at enterprise scale. Components include ioFog Agent (universal edge microservice environment), ioFog Controller (distributed control plane), ioFog Router (secure overlay network using Skupper), and deployment tooling. Supports air-gapped deployments, hardware-agnostic management (x86, ARM64, GPUs, VMs), and external KMS integration (HashiCorp Vault, OpenBao, AWS/Azure/GCP Secret Manager). Version 3.7.0 adds NATS messaging as default pub/sub, fine-grained RBAC, and comprehensive auditing .



- **[KubeEdge](https://github.com/kubeedge/kubeedge)**  

  CNCF graduated Kubernetes-native edge computing framework. Extends native containerized application orchestration to edge nodes while providing cloud-edge synergy. Uses digital-twin state modeling to represent physical devices as virtual objects, with MQTT-based messaging. Key feature: node autonomy — edge nodes operate independently when disconnected from cloud. Go-based .



- **[Baetyl](https://github.com/baetyl/baetyl)**  

  LF Edge project (donated by Baidu) extending cloud computing, data, and services to edge devices. Built-in support for 30+ industrial protocols and AI inference through MLflow integration. Docker-compatible orchestration with edge-native design. China's first open-source edge computing platform .



- **[EVE-OS (Project EVE)](https://github.com/lf-edge/eve)**  

  Edge Virtualization Engine from LF Edge, contributed by ZEDEDA. Open, agnostic, standardized architecture for orchestrating cloud-native applications across enterprise on-premises edge. Provides hardware-assisted virtualization and container/Kubernetes runtimes with declarative API for intermittent connectivity and disconnected operations. Runs on ARM64 devices (Raspberry Pi) to Intel/AMD servers with GPUs .



- **[Edge Home Orchestration](https://github.com/lf-edge/edge-home-orchestration-go)**  

  LF Edge Home Edge Project. Implements distributed computing between Docker Container enabled devices in a Home Edge Network. Scans network, rates device performance, and assigns Home Edge Applications to nodes with highest scores. Supports x86-64 Linux, Raspberry Pi3, HiKey960, Orange Pi3. Apache-2.0 .



- **[Eclipse hawkBit](https://github.com/eclipse-hawkbit/hawkbit)**  

  Domain-independent back-end framework for rolling out software updates to constrained edge devices, gateways, and everything in between. **Version 1.0 released April 2026** with Eclipse Mature status. Features three integration APIs (DDI REST/HTTP, DMF AMQP/RabbitMQ, Management REST), multi-tenancy, cascading rollout groups with error thresholds, approval workflows, RBAC, per-device security tokens, mTLS, OAuth 2.0/OIDC. Commercial offerings like Bosch IoT Rollouts and Kynetics Update Factory build on hawkBit. Integrations with SWUpdate, RAUC, Zephyr RTOS, ChirpStack. EPL 2.0 .



- **[Eclipse stratOS](https://github.com/eclipse-stratos)**  

  Open-source edge-cloud-IoT orchestration platform from EU research (aerOS project). Unifies edge, cloud, and IoT environments through advanced orchestration. Supports both Docker-based and Kubernetes-native setups, adaptable to Wasm. Features edge-native federation with distributed state network of brokers (NGSI-LD pub/sub), fully decentralized service orchestration, VPN tunneling via WireGuard. Aligned with EU CEI TF3 Architecture .



- **[Mender](https://github.com/mendersoftware/mender)**  

  Open-source OTA software update manager for Linux devices (Apache-2.0). Also available as **mender-mcu** for resource-constrained devices integrating with Zephyr RTOS and MCUboot for A/B updates with automatic rollback. The mender-mcu module enables atomic, fail-safe OTA updates on MCUs .



### Lightweight Kubernetes for Edge



- **K3s** — Single binary, resource-constrained Kubernetes. Ideal for edge devices with limited resources.

- **K0s** — Zero-friction Kubernetes, supports x86, ARM, and RISC-V architectures.

- **MicroK8s** — Lightweight, production-grade Kubernetes from Canonical.



### Device Management & Orchestration



- **[EdgeX Foundry](https://github.com/edgexfoundry)**  

  LF Edge project building a common open framework for IoT edge computing. Provides interoperability between devices and applications through standardized APIs.



- **[Akraino Edge Stack](https://github.com/akraino-edge-stack)**  

  LF Edge project creating an open-source software stack for high-availability cloud services optimized for edge computing systems and applications. Includes 19+ blueprints for various edge use cases including IoT, telecom access, network cloud, and industrial automation .



### Additional Strong Open-Source Options



- **OTA Updates**: **Eclipse hawkBit** (production-ready 1.0, multi-protocol), **Mender** (Linux + MCU support), **RAUC** (embedded Linux update framework).

- **Edge Virtualization**: **EVE-OS** (LF Edge, hardware-agnostic), **ACRN** (embedded hypervisor for IoT/edge).

- **Orchestration**: **Eclipse ioFog** (enterprise-scale, air-gap capable), **Intel EMF** (Intel platform integration), **stratOS** (EU research, decentralized).

- **Industrial Edge**: **Fledge** (LF Edge, industrial IoT focus), **EdgeX Foundry** (common IoT framework).



**Frameworks for building custom systems**: Combine **Eclipse ioFog** for enterprise-scale edge orchestration with air-gap support, **Eclipse hawkBit** for production-grade OTA updates, **EVE-OS** for hardware-agnostic edge virtualization, and **K3s** for lightweight Kubernetes at the edge. Add **Mender** for MCU-level firmware updates and **Intel EMF** for Intel platform integration .



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Edge device orchestration platforms handle sensitive device and network data; ensure proper security hardening for distributed deployments.

- Self-hosted open-source solutions require proper device management, OTA update infrastructure, and fleet monitoring capabilities. Open-source edge orchestration is mature for Linux-based devices but less developed for constrained MCUs .



---



**Made for edge computing engineers, IoT platform teams, embedded developers, and infrastructure architects.**  

Let's make edge device orchestration more open, resilient, and scalable.
