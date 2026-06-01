---
title: "📡 5G New Radio (NR) Radio Access Network"
date: 2026-06-01
tags:
  - Networking/5G/RAN
summary: "Deep dive into 5G NR, radio physical layer, frequency spectrum, and RAN architecture."
---

# 2. 📡 5G New Radio (NR) Radio Access Network

This module focuses on the 5G New Radio (NR) interface, the architecture of the Next Generation Radio Access Network (NG-RAN), and the physical/protocol stacks.

## 📋 Core Topics
- **Frequency Bands:** Frequency Range 1 (sub-6 GHz) and Frequency Range 2 (millimeter-wave / mmWave).
- **Physical Layer (PHY):** Waveforms (CP-OFDM, DFT-s-OFDM), numerologies, subcarrier spacing, and frame structure.
- **Massive MIMO & Beamforming:** Antenna arrays, spatial multiplexing, beam sweeping, and tracking.
- **RAN Architecture:** gNodeB (gNB) split architecture into Centralized Unit (CU) and Distributed Unit (DU).

## 📝 Related Notes
- [[01. 5G RAN Protocol Stack]] — Exhaustive architectural analysis of the User Plane (SDAP, PDCP, RLC, MAC, PHY) and Control Plane (NAS, RRC) layers, detailing SDU/PDU encapsulation, PDCP security algorithms, split bearers, and reordering.
- [[02. 5G SDAP and QoS Architecture]] — Exhaustive architectural analysis of the Service Data Adaptation Protocol (SDAP) and 5G Quality of Service (QoS) framework, detailing flow-to-bearer mapping, GBR vs Non-GBR parameters, 5QI capabilities, explicit vs reflective routing, and 1-byte header bit-maps.
- [[03. 5G PDCP Sublayer Architecture]] — Exhaustive architectural deep dive into the Packet Data Convergence Protocol (PDCP) layer, detailing the four foundational pillars: header compression (RoHC), ciphering & integrity protection, split bearers, and reordering buffer mechanics.
- [[04. 5G RLC Sublayer Architecture]] — Exhaustive architectural analysis of the 5G NR Radio Link Control (RLC) layer, detailing the three operational modes (TM, UM, AM), segmentation and reassembly mechanics, and a step-by-step ARQ retransmission timeline.
- [[05. 5G MAC Sublayer Architecture]] — Exhaustive architectural deep dive into the 5G NR Medium Access Control (MAC) layer, detailing logical-to-transport channel mappings, dynamic scheduling, MAC Control Elements (MAC CEs), Carrier Aggregation multi-stack binding, Asynchronous HARQ processes, and Code Block Group (CBG) retransmission efficiency.
- [[06. 5G MAC Scheduler and Bandwidth Adaptation]] — Exhaustive architectural breakdown of the 5G NR MAC Scheduler and Bandwidth Adaptation mechanisms, detailing Bandwidth Parts (BWP), downlink preemption (URLLC intercept), Dynamic vs Configured (SPS) scheduling, uplink scheduling parameters (SRS, power-limited constraints), and Configured Grant Type 1 vs Type 2.
- [[07. 5G Physical Layer (PHY) Processing and Channels]] — Exhaustive technical deep dive into the 5G New Radio (NR) Physical Layer (PHY), detailing downlink/uplink channel inventories, block-by-block processing of Transport Blocks (LDPC graphs BG1/BG2, rate matching, scrambling, modulation), layer mapping, precoding, resource grid mapping, and OFDM/RF beamforming.
- [[08. 5G Physical Layer Structure and Numerology]] — Exhaustive architectural deep dive into the 5G NR Physical Layer structure, covering OFDM characteristics, CP-OFDM vs DFT-precoded OFDM multiple access, PAPR constraints, flexible numerologies (SCS exponential scaling), time domain grid hierarchies, Resource Blocks/Elements, and SLIV-based mini-slot scheduling.
- [[09. 5G RRC and NAS States and Mobility]] — Exhaustive technical deep dive into the 5G NR Layer 3 Control Plane protocols, detailing the division between RRC (Access Stratum) and NAS (Non-Access Stratum), the 3-state RRC state machine (Idle, Connected, Inactive) with Suspend/Resume mechanisms, cached context architectures, and mobility frameworks in both idle/inactive (UE-controlled RNA/TA updates) and connected (network-controlled handovers) modes.

## 📚 Course Materials
All lectures, videos, and reading slides are organized inside the [Materials](file:///c:/All%20vaults/study-brain/Networking/5G/2.%205G%20New%20Radio%20%28NR%29%20Radio%20Access%20Network/Materials) folder:

### 🎥 Video Lectures
* [[2. 5G New Radio (NR) Radio Access Network/Materials/1. RAN Protocol Stack.mp4|1. RAN Protocol Stack (Video)]]
* [[2. 5G New Radio (NR) Radio Access Network/Materials/2. SDAP Quality of Service.mp4|2. SDAP Quality of Service (Video)]]
* [[2. 5G New Radio (NR) Radio Access Network/Materials/3. PDCP Compression, Ciphering, Integrity, Split bearer.mp4|3. PDCP Compression, Ciphering, Integrity, Split bearer (Video)]]
* [[2. 5G New Radio (NR) Radio Access Network/Materials/4. RLC Segmentation, ARQ.mp4|4. RLC Segmentation, ARQ (Video)]]
* [[2. 5G New Radio (NR) Radio Access Network/Materials/5. MAC Mux, HARQ.mp4|5. MAC Mux, HARQ (Video)]]
* [[2. 5G New Radio (NR) Radio Access Network/Materials/6. MAC Scheduler.mp4|6. MAC Scheduler (Video)]]
* [[2. 5G New Radio (NR) Radio Access Network/Materials/7. PHY Physical Layer functions.mp4|7. PHY Physical Layer functions (Video)]]
* [[2. 5G New Radio (NR) Radio Access Network/Materials/8. PHY Multiple Access, Modulation, Time domain structure etc.mp4|8. PHY Multiple Access, Modulation, Time domain structure etc. (Video)]]
* [[2. 5G New Radio (NR) Radio Access Network/Materials/9. RRC and NAS RRC States, Mobility.mp4|9. RRC and NAS RRC States, Mobility (Video)]]

### 📄 Reference Lecture Slides (PDFs)
* [[2. 5G New Radio (NR) Radio Access Network/Materials/1.1 RAN Protocol Stack.pdf|1.1 RAN Protocol Stack (PDF)]]
* [[2. 5G New Radio (NR) Radio Access Network/Materials/2.1 SDAP.pdf|2.1 SDAP (PDF)]]
* [[2. 5G New Radio (NR) Radio Access Network/Materials/3.1 PDCP.pdf|3.1 PDCP (PDF)]]
* [[2. 5G New Radio (NR) Radio Access Network/Materials/4.1 RLC.pdf|4.1 RLC (PDF)]]
* [[2. 5G New Radio (NR) Radio Access Network/Materials/5.1 MAC.pdf|5.1 MAC (PDF)]]
* [[2. 5G New Radio (NR) Radio Access Network/Materials/6.1 MAC 2 Scheduler.pdf|6.1 MAC 2 Scheduler (PDF)]]
* [[2. 5G New Radio (NR) Radio Access Network/Materials/7.1 PHY.pdf|7.1 PHY (PDF)]]
* [[2. 5G New Radio (NR) Radio Access Network/Materials/8.1 PHY2.pdf|8.1 PHY2 (PDF)]]
* [[2. 5G New Radio (NR) Radio Access Network/Materials/9.1 RRC and NAS.pdf|9.1 RRC and NAS (PDF)]]

---
*Back to [[5G Course - Index|🌐 5G Course Index]]*
