---
title: "🧠 5G Core Networks"
date: 2026-06-01
tags:
  - Networking/5G/Core
summary: "Service-Based Architecture, key Network Functions (NFs), and network slicing in the 5G Core."
---

# 4. 🧠 5G Core Networks

This module focuses on the 5G Core (5GC) network architecture, design principles, and core Network Functions (NFs).

## 📋 Core Topics
- **Service-Based Architecture (SBA):** HTTP/2, REST APIs, and the service producer/consumer model.
- **Key Network Functions (NFs):**
  - **AMF:** Access and Mobility Management Function
  - **SMF:** Session Management Function
  - **UPF:** User Plane Function
  - **UDM / UDR:** Unified Data Management & Unified Data Repository
  - **AUSF:** Authentication Server Function
  - **NRF:** Network Repository Function
  - **PCF:** Policy Control Function
- **Network Slicing:** Logical virtual networks partitioned on a single physical infrastructure (S-NSSAI, SST, SD).

## 📝 Related Notes
- [[01. 5G Core Network Identifiers]] — Exhaustive technical analysis of identifiers in the 5G Core network, detailing Device Identity (PEI/IMEI/IMEISV structure), Subscription Identity (SUPI vs. SUCI over-the-air encryption mechanics), and Temporary Identity (5G-GUTI = GUAMI + 5G-TMSI math).
- [[02. 5G Service-Based Architecture (SBA)]] — Exhaustive technical deep dive into the 5G Core Service-Based Architecture (SBA), detailing reference point vs. service-based representations, HTTP/2 RESTful API interfaces, and the core registration, discovery, and requesting mechanisms managed by the Network Repository Function (NRF).
- [[03. 5G Access and Mobility Management Function (AMF)]] — Exhaustive technical analysis of the 5G Core Access and Mobility Management Function (AMF), detailing interface architectures, Registration Management (RM states), Connection Management (CM states), and tracked mobility.
- [[04. 5G Session Management Function (SMF)]] — Exhaustive technical deep dive into the 5G Core Session Management Function (SMF), detailing PDU Session properties, Ethernet, IP, and Unstructured session types, and the mechanics of Service and Session Continuity (SSC) Modes 1, 2, and 3.
- [[05. 5G Unified Data Management (UDM) and Unified Data Repository (UDR)]] — Exhaustive technical analysis of the 5G Core Unified Data Management (UDM) and Unified Data Repository (UDR), detailing the stateless cloud design decoupling application logic from database collections.
- [[06. 5G User Plane Function (UPF)]] — Exhaustive technical deep dive into the 5G Core User Plane Function (UPF), detailing user plane anchoring, packet forwarding, N3/N4/N6/N9 interfaces, and PFCP protocol control rule sets (PDR, FAR, BAR, QER, URR).
- [[07. 5G Policy Control Function (PCF)]] — Exhaustive technical analysis of the 5G Core Policy Control Function (PCF), detailing session-related vs. non-session-related policy domains, access area restrictions, RFSP priority indexes, and PCC rule conversions.

## 📚 Course Materials
All lectures, videos, and reading slides are organized inside the [Materials](file:///c:/All%20vaults/study-brain/Networking/5G/4.%205G%20Core%20Networks/Materials) folder:

### 🎥 Video Lectures
* [[4. 5G Core Networks/Materials/1. Identifiers in 5G.mp4|1. Identifiers in 5G (Video)]]
* [[4. 5G Core Networks/Materials/2. Service Based Architecture.mp4|2. Service Based Architecture (Video)]]
* [[4. 5G Core Networks/Materials/3. Access and Mobility Management Function.mp4|3. Access and Mobility Management Function (Video)]]
* [[4. 5G Core Networks/Materials/4. Session Management Function.mp4|4. Session Management Function (Video)]]
* [[4. 5G Core Networks/Materials/5. Unified Data Management and Unified Data Repository.mp4|5. Unified Data Management and Unified Data Repository (Video)]]
* [[4. 5G Core Networks/Materials/6. User Plane Function.mp4|6. User Plane Function (Video)]]
* [[4. 5G Core Networks/Materials/7. Policy Control Function.mp4|7. Policy Control Function (Video)]]

### 📄 Reference Lecture Slides (PDFs)
* [[4. 5G Core Networks/Materials/1.1 Core NW Identifiers.pdf|1.1 Core NW Identifiers (PDF)]]
* [[4. 5G Core Networks/Materials/2.1 Core SBA.pdf|2.1 Core SBA (PDF)]]
* [[4. 5G Core Networks/Materials/3.1 NF AMF.pdf|3.1 NF AMF (PDF)]]
* [[4. 5G Core Networks/Materials/4.1 NF SMF.pdf|4.1 NF SMF (PDF)]]
* [[4. 5G Core Networks/Materials/5.1 NF UDM and UDR.pdf|5.1 NF UDM and UDR (PDF)]]
* [[4. 5G Core Networks/Materials/6.1 NF UPF.pdf|6.1 NF UPF (PDF)]]
* [[4. 5G Core Networks/Materials/7.1 NF PCF.pdf|7.1 NF PCF (PDF)]]

---
*Back to [[5G Course - Index|🌐 5G Course Index]]*

