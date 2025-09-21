---
title: Propulsion System Overview - ATA 72-00
version: 1.0.0
date: 2025-06-02
status: Baseline (Frozen)
classification: INTERNAL
authors:
  - GAIA-Q-Air Propulsion Team
reviewers:
  - First Officer (Technical Validation)
approvers:
  - Amedeo Pelliccia
project: AMPEL BWB Q100
ata_chapter: "72 - Engine (Turbine/Hybrid/H2)"
infocode: OV
tags:
  - overview
  - engine
  - propulsion
  - hydrogen
  - lh2
  - baseline
  - ata72
related_documents:
  - ID: GP-AM-AMPEL-0100-00-00-00-000-OV
    relationship: parent_document
    revision: D
  - ID: GP-AM-AMPEL-0100-73-00-00-000-OV
    relationship: child_document
    revision: E
  - ID: GP-AM-AMPEL-0100-77-00-00-000-OV
    relationship: child_document
    revision: A
---

| DOCUMENT CONTROL NOTICE                                                                                              |
| :------------------------------------------------------------------------------------------------------------------- |
| **Version 1.0.0** | This document represents the frozen **Gate-1 Concept Baseline** for the AMPEL BWB Q100 propulsion system. All parameters herein are validated and serve as the basis for subsequent design and analysis phases. Changes require formal review under the GAIA-QAO configuration management plan. |

# 1. Purpose & Scope

This document provides a high-level technical overview of the **GAIA-Q-GreenTech GGT-205H** propulsion system for the AMPEL BWB Q100 aircraft. It serves as the primary index for all ATA Chapter 72 documentation, outlining the engine's mission, core design, key parameters, and its critical interfaces with other aircraft systems.

## Revision lineage
- **Current (Rev C)** — this document.
- **Previous:** **[Rev B](_revisions/GP-AM-AMPEL-0100-72-00-00-000-OV/B.md)** · **[Rev A](_revisions/GP-AM-AMPEL-0100-72-00-00-000-OV/A.md)**

# 2. System Overview

## 2.1 General Description & Mission

The GGT-205H is a two-spool, high-bypass ratio turbofan engine designed for exceptional efficiency during long-duration cruise at high altitudes (FL390+) and transonic speeds (M 0.87). Two engines are installed on the upper aft section of the Blended Wing Body, a configuration designed to leverage the airframe's boundary layer ingestion (BLI) potential for enhanced propulsive efficiency.

## 2.2 Key Performance Parameters

| Parameter                       | Specification                                     |
| :------------------------------ | :------------------------------------------------ |
| **Engine Model**                | GAIA-Q-GreenTech GGT-205H                         |
| **Rated Takeoff Thrust**        | 205 kN, flat-rated to ISA+15°C                    |
| **Bypass Ratio (BPR)**          | 15:1                                              |
| **Overall Pressure Ratio (OPR)**| 55:1                                              |
| **TSFC_J**                      | 0.46 lb/(lbf·hr) (≈13.0 g/kN·s)                     |
| **TSFC_H2 (index)**             | ~2.8x better by mass vs. Jet-A (dimensionless)    |
| **Dry Weight**                  | 4,850 kg (Preliminary target)                     |

# 3. Engine Module Breakdown (ATA 72 Index)

This overview is the parent document for the following detailed system descriptions within ATA 72:

-   **[72-30: Compressor Section](./../72-30/GP-AM-AMPEL-0100-72-30-00-000-SYS.md)**
-   **[72-40: Combustion Section](./../72-40/GP-AM-AMPEL-0100-72-40-00-000-SYS.md)**
-   **[72-50: Turbine Section](./../72-50/GP-AM-AMPEL-0100-72-50-00-000-SYS.md)**
-   **[72-60: Accessory Drive](./../72-60/GP-AM-AMPEL-0100-72-60-00-000-SYS.md)**
-   **[72-Q01: Quantum Propulsion Extension](./../72-Q01/GP-AM-AMPEL-0100-72-Q01-00-000-SYS.md)**

# 4. Key System Interfaces (Cross-Reference)

The GGT-205H engine is tightly integrated with multiple aircraft systems. The primary interfaces are defined below:

| ATA Chapter | Interfacing System                               | Function & Key Interactions                                                                                                                            |
| :---------- | :----------------------------------------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------- |
| **[ATA 28](../../ATA28_Fuel/28-00/GP-AM-AMPEL-0100-28-00-00-000-OV.md)** | **Airframe Fuel System**                         | Receives conditioned LH₂ (as GH₂) and SAF from the airframe boost pumps. Manages boil-off and provides tank data.                                       |
| **[ATA 73](../../ATA73_EngFuelCtrl/73-00/GP-AM-AMPEL-0100-73-00-00-000-OV.md)** | **Engine Fuel & Control**                        | The FADEC is the primary control interface, executing thrust commands, managing hybrid fuel transitions, and enforcing all engine protection limits. |
| **[ATA 77](../../ATA77_EngineIndic/77-00/GP-AM-AMPEL-0100-77-00-00-000-OV.md)** | **Engine Indication**                            | Provides all health and performance parameters (N1, N2, EGT, vibration, pressures, temperatures) for cockpit indication and maintenance logging. |
| **[ATA 76](../../ATA76_EngineCtrl/76-00/GP-AM-AMPEL-0100-76-00-00-000-OV.md)** | **Engine Controls (Cockpit)**                    | Receives pilot thrust lever angle (TLA) commands and emergency shutdown signals.                                                                       |
| **[ATA 24](../../ATA24_Electrical/24-00/GP-AM-AMPEL-0100-24-00-00-000-OV.md)** | **Electrical Power**                             | Receives redundant electrical power for the FADEC and engine actuators. The engine's integrated starter-generator provides power back to the aircraft. |
| **[ATA 79](../../ATA79_Oil/79-00/GP-AM-AMPEL-0100-79-00-00-000-OV.md)** | **Oil System**                                   | Manages lubrication and cooling of engine bearings and gears. Interfaces with the LH₂ heat exchanger for primary cooling.                               |
| **[ATA 75](../../ATA75_EngineAir/75-00/GP-AM-AMPEL-0100-75-00-00-000-OV.md)** | **Air System**                                   | Provides minimal bleed air for engine and nacelle anti-ice functions.                                                                                  |
| **[ATA 26](../../ATA26_FireProtection/26-00/GP-AM-AMPEL-0100-26-00-00-000-OV.md)** | **Fire Protection**                              | Interfaces with fire detection loops and provides status for the High-Pressure Shutoff Valve (HPSOV) and Shutoff Valve (SOV).                       |
| **[ATA 54](../../ATA54_Nacelles/54-00/GP-AM-AMPEL-0100-54-00-00-000-OV.md)** | **Nacelles/Pylons**                              | Defines the physical mounting, aerodynamic fairings, and thrust reverser integration.                                                                  |

# 5. Compliance & Safety

The GGT-205H is designed for certification under **EASA CS-E** and **FAA 14 CFR Part 33**. The program anticipates the need for **Special Conditions** to address direct-burn hydrogen combustion and novel powerplant installation (**CS-25.901(c)**), with Means of Compliance based on ARP4761A safety assessments.

# 6. Glossary

For a comprehensive list of all terms and acronyms, refer to the master program glossary:
-   [**Glossary and Abbreviations** (`...-00-00-00-002-GLO-C.md`)](../../ATA00_General/00-00/GP-AM-AMPEL-0100-00-00-00-002-GLO.md)

---
[↑ Back to Top](#1-purpose--scope)
