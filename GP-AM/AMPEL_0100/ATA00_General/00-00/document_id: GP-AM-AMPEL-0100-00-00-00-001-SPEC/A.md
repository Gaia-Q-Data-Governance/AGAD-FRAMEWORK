---
title: Aircraft Specifications - ATA 00
document_id: GP-AM-AMPEL-0100-00-00-00-001-SPEC
revision: A
version: 1.0.0
date: 2025-06-01
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
infocode: SPEC
tags:
  - specifications
  - performance
  - weights
  - dimensions
  - ampel
  - bwb
  - q100
related_documents:
  - ID: GP-AM-AMPEL-0100-00-00-00-000-OV
    relationship: child_of
  - ID: GP-AM-AMPEL-0100-00-00-00-002-GLO
    relationship: references
---

| DOCUMENT CONTROL NOTICE                                                                                              |
| :------------------------------------------------------------------------------------------------------------------- |
| **Version 1.0.0** | This document represents the frozen **Gate-1 Concept Baseline** for the AMPEL BWB Q100 program. All parameters herein are validated and serve as the basis for subsequent design and analysis phases. Changes require formal review under the GAIA-QAO configuration management plan. |

# 1. Purpose & Scope

This document provides the top-level technical specifications for the AMPEL BWB Q100 aircraft. The data herein is the single source of truth for Gate-1 baseline performance, weight, and dimensional characteristics. All units are SI primary, with common aviation units in parentheses where applicable.

For definitions of terms, see the [Program Glossary](./GP-AM-AMPEL-0100-00-00-00-002-GLO.md).

# 2. General Specifications

| Parameter                       | Specification                                           |
| :------------------------------ | :------------------------------------------------------ |
| **Aircraft Model**              | AMPEL BWB Q100                                          |
| **Primary Mission**             | Long-Range Point-to-Point Transport                     |
| **Airworthiness Category**      | EASA CS-25 / FAA 14 CFR Part 25                         |
| **Crew**                        | 2 (Flight Deck) + 4 (Cabin)                             |
| **Passenger Capacity**          | 120 (2-Class) to 180 (High-Density)                     |

# 3. Dimensions & Geometry

| Parameter                       | Specification                                           |
| :------------------------------ | :------------------------------------------------------ |
| **Wingspan (b)**                | 58.0 m                                                  |
| **Wing Area (S)**               | 280 m²                                                  |
| **Aspect Ratio (AR)**           | 12.0                                                    |
| **Overall Length**              | 42.0 m                                                  |
| **Overall Height**              | 12.5 m                                                  |
| **Sweep (@ 25% MAC)**           | 32 degrees                                              |
| **Mean Aerodynamic Chord (c̄)**  | 5.5 m                                                   |
| **ICAO Aerodrome Code**         | E                                                       |

# 4. Weights & Payload

| Parameter                       | Specification                                           |
| :------------------------------ | :------------------------------------------------------ |
| **Operating Empty Weight (OEW)**| 82,500 kg                                               |
| **Max Zero Fuel Weight (MZFW)** | 102,500 kg                                              |
| **Max Landing Weight (MLW)**    | 117,000 kg                                              |
| **Max Takeoff Weight (MTOW)**   | 145,000 kg¹                                             |
| **Design Payload**              | 20,000 kg                                               |
| **Max Fuel (LH₂)**              | 16,000 kg (approx. 228 m³)                              |

---
**Note ¹:** *MTOW is a structural limit. Typical design-range TOW is ~118.5 t (OEW + Design Payload + Max Fuel).*

# 5. Propulsion

| Parameter                       | Specification                                           |
| :------------------------------ | :------------------------------------------------------ |
| **Engine Model**                | 2× GAIA-Q-GreenTech GGT-205H                            |
| **Rated TO Thrust (per engine)**| 205 kN (ISA-SL), flat-rated to ISA+15 °C                |
| **Primary Fuel**                | Liquid Hydrogen (LH₂)                                   |
| **Auxiliary Fuel Capability**   | Sustainable Aviation Fuel (SAF)²                        |

---
**Note ²:** *Gate-1 baseline assumes LH₂-only mission profile. Hybrid SAF capability is reserved for future development.*

# 6. Performance & Aerodynamics

| Parameter                       | Specification                                           |
| :------------------------------ | :------------------------------------------------------ |
| **Max Range (at Design Payload)**| 15,500 km (with ETOPS-240 reserves)                     |
| **Cruise Speed (Mcruise)**      | Mach 0.87                                               |
| **Service Ceiling**             | 43,000 ft                                               |
| **Cruise L/D**                  | 26.1                                                    |
| **Cruise CL**                   | 0.52                                                    |
| **CD₀ (cruise, incl. penalties)**| 0.0123                                                  |
| **k (induced drag factor)**     | 0.028 (AR=12, e≈0.95)                                   |
| **Takeoff Distance (MTOW, ISA-SL)**| 2,850 m                                                 |
| **Landing Distance (MLW, ISA-SL)**| 1,650 m                                                 |
| **Second-Segment Gradient (OEI)**| 2.9%                                                    |

---
[↑ Back to Top](#1-purpose--scope)
