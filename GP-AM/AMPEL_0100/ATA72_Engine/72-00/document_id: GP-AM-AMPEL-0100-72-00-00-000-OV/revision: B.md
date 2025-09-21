---
title: Propulsion System Overview - ATA 72
document_id: GP-AM-AMPEL-0100-72-00-00-000-OV
revision: B
version: 1.0.0
date: 2025-05-24
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
  - ID: GP-AM-AMPEL-0100-00-00-00-000-OV-D
    relationship: parent_document
  - ID: GP-AM-AMPEL-0100-73-00-00-000-OV-A
    relationship: child_document
  - ID: GP-AM-AMPEL-0100-77-00-00-000-OV-A
    relationship: child_document
---

| DOCUMENT CONTROL NOTICE                                                                                              |
| :------------------------------------------------------------------------------------------------------------------- |
| **Version 1.0.0** | This document represents the frozen **Gate-1 Concept Baseline** for the AMPEL BWB Q100 propulsion system. All parameters herein are validated and serve as the basis for subsequent design and analysis phases. Changes require formal review under the GAIA-QAO configuration management plan. |

# Propulsion System Overview - ATA 72

## 1. Document Purpose

This document provides a high-level technical overview of the **GAIA-Q-GreenTech GGT-205H** propulsion system selected for the AMPEL BWB Q100 aircraft. It outlines the engine's mission, core design philosophy, key performance parameters, and system architecture. This document serves as the primary entry point for all engine-related documentation within the AToC.

## 2. System Overview

### 2.1 General Description & Mission

The GGT-205H is a two-spool, high-bypass ratio turbofan engine specifically designed for exceptional efficiency during long-duration cruise at high altitudes and transonic speeds (M 0.87). Two engines are installed in a closely-coupled configuration on the upper aft section of the Blended Wing Body. This placement is designed to leverage the airframe's boundary layer ingestion (BLI) potential; the BLI contribution is estimated at a 3-5% propulsive efficiency gain at M 0.87, to be quantified in the ATA 71 integration analysis.

The primary mission of the GGT-205H is to enable the AMPEL BWB Q100's ultra-long-range capability while minimizing environmental impact through its hydrogen-first design.

### 2.2 Design Philosophy

The propulsion system is a direct reflection of the GAIA-QAO framework:
*   **Sustainability-First:** The engine is architected for primary operation on cryogenic Liquid Hydrogen (LH₂) to eliminate CO₂ emissions. It retains full compatibility with 100% Sustainable Aviation Fuel (SAF) for operational flexibility.
*   **Ultra-High Efficiency:** The design targets revolutionary thermal and propulsive efficiency through a high **Overall Pressure Ratio (OPR)** of 55:1 (compressor exit / inlet total pressure), advanced materials like Ceramic Matrix Composites (CMCs) in the hot section, and optimized airframe integration.
*   **AI-Enhanced Control:** The engine is controlled by a next-generation Full Authority Digital Engine Control (FADEC) system that is fully integrated with the `i-Aher0` AI core for real-time performance optimization and predictive health monitoring.
*   **Low Noise:** The high-bypass design, coupled with advanced acoustic liners and chevrons, is engineered to exceed ICAO Chapter 14 noise limits by a target of **≥10 EPNdB cumulative margin**.

### 2.3 Key Innovations
-   **Direct-Burn Hydrogen Combustion:** A novel multi-point injection and combustion chamber design to ensure stable, low-NOx operation with LH₂.
-   **Cryogenic Thermal Management:** An integrated heat exchanger system that uses the cryogenic LH₂ fuel to cool engine oil, hydraulic fluids, and environmental control systems, improving the aircraft's overall thermal efficiency.
-   **Quantum-Informed Design:** Turbine blade and combustor designs were optimized using quantum-simulation-informed models. This is documented in the **Quantum Propulsion Extension (ATA 72-Q01)**.

## 3. Principal Characteristics

| Parameter                       | Specification                                     |
| :------------------------------ | :------------------------------------------------ |
| **Engine Model**                | GAIA-Q-GreenTech GGT-205H                         |
| **Configuration**               | Two-spool, High-Bypass Turbofan                   |
| **Rated TO Thrust**             | 205 kN (46,086 lbf), flat-rated to ISA+15°C        |
| **Bypass Ratio (BPR)**          | 15:1                                              |
| **Overall Pressure Ratio (OPR)**| 55:1                                              |
| **TSFC_J**                      | 0.46 lb/(lbf·hr) (≈13.0 g/kN·s)                     |
| **TSFC_H2 (index)**             | ~2.8x better by mass vs. Jet-A (dimensionless)    |
| **Dry Weight**                  | 4,850 kg (Preliminary target, subject to material validation) |
| **Inlet Diameter**              | 2.6 m                                             |

## 4. System Architecture & Interfaces

The GGT-205H is comprised of standard turbofan modules but features unique interfaces critical to its function on the AMPEL BWB Q100.
*   **Fuel System Interface (ATA 73):** Dual-mode interface for both cryogenic LH₂ and SAF.
*   **Control System Interface (ATA 73):** The FADEC interfaces directly with the Integrated Modular Avionics (IMA) backplane via an **ARINC 664 Part 7 (AFDX)** network.
*   **Air System Interface (ATA 75):** Minimal bleed air extraction, primarily for anti-ice systems.
*   **Indication Interface (ATA 77):** Provides comprehensive sensor data to the cockpit displays and Central Maintenance System (CMS).

## 5. Compliance & Safety

The GGT-205H is designed for certification under **EASA CS-E** and **FAA 14 CFR Part 33**. The program anticipates the need for **Special Conditions** to address direct-burn hydrogen combustion and novel powerplant installation (**CS-25.901(c)**), with Means of Compliance based on ARP4761A safety assessments.

## 6. Glossary

For a comprehensive list of all terms and acronyms, refer to the master program glossary:
-   [**Glossary and Abbreviations** (`...-00-00-00-002-GLO-C.md`)](../../ATA00_General/00-00/GP-AM-AMPEL-0100-00-00-00-002-GLO-C.md)

---
[↑ Back to Top](#propulsion-system-overview---ata-72)
