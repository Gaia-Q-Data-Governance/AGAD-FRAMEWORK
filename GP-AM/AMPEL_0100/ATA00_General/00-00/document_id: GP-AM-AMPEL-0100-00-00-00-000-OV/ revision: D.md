---
title: AMPEL BWB Q100 - General Information Overview
document_id: GP-AM-AMPEL-0100-00-00-00-000-OV
revision: D
version: 1.0.0
date: 2025-05-20
status: Baseline (Frozen)
classification: INTERNAL
authors:
  - GAIA-Q-Air
reviewers:
  - First Officer (Technical Validation)
approvers:
  - Amedeo Pelliccia
project: AMPEL BWB Q100
ata_chapter: "00 - Intro & General"
infocode: OV
tags:
  - overview
  - baseline
  - ampel
  - bwb
  - q100
  - aircraft
  - general
  - introduction
  - long-range
  - point-to-point
related_documents:
  - ID: Master AToC (ATA General Index for Advanced Aircraft Clusters)
    relationship: child_of
---

| DOCUMENT CONTROL NOTICE                                                                                              |
| :------------------------------------------------------------------------------------------------------------------- |
| **Version 1.0.0** | This document represents the frozen **Gate-1 Concept Baseline** for the AMPEL BWB Q100 program. All parameters herein are validated and serve as the basis for subsequent design and analysis phases. Changes require formal review under the GAIA-QAO configuration management plan. |

# AMPEL BWB Q100 - General Information Overview

## 1. Document Purpose

This document serves as the primary introduction and high-level overview for the **AMPEL BWB Q100** advanced aircraft platform. It is the designated entry point for all project personnel, stakeholders, and regulatory bodies seeking to understand the fundamental mission, design philosophy, and core characteristics of the aircraft.

## 2. Aircraft Program Overview

### 2.1 Mission Profile

The AMPEL BWB Q100 is a next-generation, long-range aircraft designed to efficiently serve point-to-point intercontinental routes. With a capacity of 100-180 passengers, its primary mission is to open new city pairs that are not economically viable for larger wide-body aircraft, while offering a revolutionary, premium passenger experience.

### 2.2 Design Philosophy

The aircraft is developed under the GAIA-QAO's unified semantic and computational framework, rooted in principles of Efficiency, Premium Passenger Experience, Digital First development, Agentic Autonomy, and Quantum Augmentation.

### 2.3 Key Differentiating Technologies
-   **Airframe:** Structurally optimized Blended Wing Body (BWB) design using advanced composites, featuring a **continuous load-bearing shell** for maximum strength and efficiency.
-   **Cabin:** The revolutionary **Panoramic Viewing Belt (PVB)**, a continuous band of high-resolution Chromatic Display Panels providing a seamless, 360-degree external view.
-   **Propulsion:** Twin GAIA-Q-GreenTech Hybrid H2/SAF High-Bypass Turbofans, designed for a primary LH₂ mission profile. ([ATA 72](../../ATA72_Engine/72-00/GP-AM-AMPEL-0100-72-00-00-000-OV-B.md), [ATA 73](../../ATA73_EngFuelCtrl/73-00/GP-AM-AMPEL-0100-73-00-00-000-OV-A.md), [ATA 49](../../ATA49_APU/49-00/GP-AM-AMPEL-0100-49-00-00-000-OV-A.md))
-   **Avionics & Autonomy:** Integrated Modular Avionics (IMA) architecture managed by the `i-Aher0` AI core.
-   **Communications:** Quantum Key Distribution (QKD) for ultra-secure data links.

## 3. Principal Characteristics

| Parameter                       | Specification                                           |
| :------------------------------ | :------------------------------------------------------ |
| **General**                     |                                                         |
| Crew                            | 2 (Flight Deck) + 4 (Cabin)                             |
| Passengers                      | 120 (Typical 2-Class), up to 180 (High-Density)         |
| **Geometry**                    |                                                         |
| Wingspan (b)                    | 58.0 m                                                  |
| Wing Area (S)                   | 280 m²                                                  |
| Aspect Ratio (AR)               | 12.0                                                    |
| **Weights**¹                    |                                                         |
| Operating Empty Weight (OEW)    | 82,500 kg                                               |
| Max Zero Fuel Weight (MZFW)     | 102,500 kg                                              |
| Max Landing Weight (MLW)        | 117,000 kg                                              |
| Max Takeoff Weight (MTOW)       | 145,000 kg                                              |
| **Payload & Fuel**²             |                                                         |
| Design Payload                  | 20,000 kg                                               |
| Max Fuel (LH₂)                  | 16,000 kg (approx. 228 m³)                              |
| **Propulsion**                  |                                                         |
| Engines                         | 2× high-bypass turbofan (hybrid-fuel capable)           |
| Rated TO Thrust (per engine)    | ~205 kN (ISA-SL), flat-rated to ISA+15 °C               |
| Cruise TSFC (Jet-A basis)       | 0.46 lb/(lbf·hr); LH₂ mass TSFC index ~2.8× better      |
| **Performance & Aerodynamics**  |                                                         |
| Max Range (at Design Payload)   | 15,500 km (with ETOPS-240 reserves)                     |
| Cruise Speed (Mcruise)          | Mach 0.87                                               |
| Cruise L/D                      | 26.1                                                    |
| Cruise CL                       | 0.52                                                    |
| CD₀ (cruise, incl. excrescences) | 0.0123                                                  |
| k (induced drag factor)         | 0.028 (AR=12, e≈0.95)                                   |
| **Field Performance (ISA, SL)** |                                                         |
| Takeoff Distance (MTOW)         | 2,850 m                                                 |
| Landing Distance (MLW)          | 1,650 m                                                 |

---
**Notes:**
1.  *MTOW 145 t is structural. Typical design-range TOW ≈ 118.5 t (OEW 82.5 t + payload 20 t + LH₂ 16 t). Field-performance figures quoted for MTOW remain valid for hot-high margins and growth.*
2.  *Gate-1 baseline assumes LH₂-only; no SAF carried. Hybrid option reserved for later Gate per ATA 49/71.*

## 4. Documentation Navigation & Compliance

All project documentation is indexed in the **Master Table of Contents (AToC)**. The design is intended for compliance with **EASA CS-25** and **FAA 14 CFR Part 25**, with special conditions anticipated for BWB primary structures, cryogenic fuel systems, and advanced avionics.

## 5. Glossary and Abbreviations

For a comprehensive list of terms, please refer to the master glossary:
-   [**Glossary and Abbreviations** (`...-00-00-00-002-GLO-A.md`)](./GP-AM-AMPEL-0100-00-00-00-002-GLO-A.md)

---
[↑ Back to Top](#ampel-bwb-q100---general-information-overview)
