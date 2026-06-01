---
title: "🔄 Key RAN Procedures"
date: 2026-06-01
tags:
  - Networking/5G/Procedures
summary: "Essential Radio Access Network control plane and user plane procedures."
---

# 3. 🔄 Key RAN Procedures

This module outlines the fundamental control and user plane procedures within the Radio Access Network (NG-RAN).

## 📋 Core Topics
- **Cell Search & Selection:** Synchronization Signals (PSS, SSS) and physical cell identity (PCI).
- **System Information Acquisition:** Master Information Block (MIB) and System Information Blocks (SIBs).
- **Random Access Channel (RACH) Procedure:** 2-step and 4-step contention-based and contention-free RACH.
- **Paging:** UE state management (RRC_IDLE, RRC_INACTIVE, RRC_CONNECTED) and paging cycles.

## 📝 Related Notes
- [[01. 5G Cell Search and Initial Access]] — Exhaustive technical deep dive into 5G NR Cell Search and Initial Access procedures, detailing PSS/SSS acquisition, Physical Cell Identity (PCI) calculation ($N_{\text{ID}}^{\text{cell}} = 3 \times N_{\text{ID}}^{(1)} + N_{\text{ID}}^{(2)}$), the Synchronization Signal Block (SSB) structure, Carrier Raster vs. Sync Raster (GSCN) differences, and the parsing of MIB, SIB1 (RMSI), and SIB2 through SIB9 on-demand and periodic architectures.
- [[02. 5G Random Access (RACH) Procedure]] — Exhaustive technical deep dive into the 5G NR Random Access (RACH) procedure, detailing triggers, Contention-Based Random Access (CBRA) 4-step flow (Msg1-Msg4), Timing Advance (TA) and power ramping calculations, Contention-Free Random Access (CFRA) 3-step flow, and collision resolution architectures.

## 📚 Course Materials
All lectures, videos, and reading slides are organized inside the [Materials](file:///c:/All%20vaults/study-brain/Networking/5G/3.%20Key%20RAN%20Procedures/Materials) folder:

### 🎥 Video Lectures
* [[3. Key RAN Procedures/Materials/1. Initial Access.mp4|1. Initial Access (Video)]]
* [[3. Key RAN Procedures/Materials/2. Random Access.mp4|2. Random Access (Video)]]

### 📄 Reference Lecture Slides (PDFs)
* [[3. Key RAN Procedures/Materials/1.1 Initial Access.pdf|1.1 Initial Access (PDF)]]
* [[3. Key RAN Procedures/Materials/2.1 Random Access.pdf|2.1 Random Access (PDF)]]

---
*Back to [[5G Course - Index|🌐 5G Course Index]]*

