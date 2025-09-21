---
title: AMPEL BWB Q100 - Glossary and Abbreviations
document_id: GP-AM-AMPEL-0100-00-00-00-002-GLO-C
revision: C
version: 1.0.0
date: 2025-05-22
status: Baseline (Frozen)
classification: INTERNAL
authors:
  - GAIA-Q-Data-Governance
reviewers:
  - First Officer (Technical Validation)
approvers:
  - Amedeo Pelliccia
project: AMPEL BWB Q100
ata_chapter: "00 - Intro & General"
infocode: GLO
tags:
  - glossary
  - acronyms
  - definitions
  - baseline
  - ampel
  - bwb
  - q100
related_documents:
  - ID: GP-AM-AMPEL-0100-00-00-00-000-OV-D
    relationship: referenced_by
---

| DOCUMENT CONTROL NOTICE                                                                                              |
| :------------------------------------------------------------------------------------------------------------------- |
| **Version 1.0.0** | This document represents the frozen **Gate-1 Concept Baseline** for the AMPEL BWB Q100 program. It is the single source of truth for all project-specific terminology and abbreviations. Changes require formal review under the GAIA-QAO configuration management plan. |

# AMPEL BWB Q100 - Glossary and Abbreviations

## 1. Introduction

This document provides definitions for key terminology, acronyms, and abbreviations used throughout the AMPEL BWB Q100 program documentation. Its purpose is to ensure clear, consistent, and unambiguous communication across all project teams and stakeholders.

## 2. Project & Framework Terminology

| Term               | Definition                                                                                                                              |
| :----------------- | :-------------------------------------------------------------------------------------------------------------------------------------- |
| **AGAD**           | **Aircraft Generative Algorithm Development.** The GAIA-QAO lifecycle framework for aerospace development, from concept to decommissioning. |
| **AMPEL BWB Q100** | The official designation for the Blended Wing Body aircraft platform, designed for 100-180 passengers with quantum-augmented systems.    |
| **GAIA-CO-ASD-LIB**| The GAIA-QAO standard for documentation, defining file formats, naming conventions, and metadata.                                         |
| **GAIA-QAO**       | **Quantum Aerospace Organization.** The federated parent organization developing the AMPEL BWB Q100.                                      |
| **i-Aher0**        | The designated name for the agentic Artificial Intelligence (AI) core responsible for autonomy, predictive maintenance, and optimization. |
| **INFOCODE**       | Two-letter document code per GAIA-CO-ASD-LIB used in filenames/front-matter (e.g., **OV** Overview, **GLO** Glossary, **SYS** Systems, **SAF** Safety, **TST** Test). Applies to front-matter and filenames and is normative across AMPEL documentation. |

## 3. Aircraft & System Terminology

| Term                     | Definition                                                                                                                            |
| :----------------------- | :------------------------------------------------------------------------------------------------------------------------------------ |
| **BB84**                 | The canonical Charles Bennett and Gilles Brassard quantum cryptography protocol used for Quantum Key Distribution (QKD).              |
| **BWB**                  | **Blended Wing Body.** An aircraft design where the body and wing are seamlessly integrated, offering high aerodynamic efficiency.        |
| **CDP**                  | **Chromatic Display Panel.** The technical term for the high-resolution screen hardware used to build the Panoramic Viewing Belt.       |
| **Continuous Load-Bearing Shell** | Frame-and-skin composite shell without passenger window cut-outs; load paths are carried via frames, stringers, and spars. The PVB sits inside the pressure vessel with no primary structural discontinuity. |
| **IMA**                  | **Integrated Modular Avionics.** A partitioned operating system (e.g., ARINC 653) hosting multiple applications on shared compute modules. |
| **KMS**                  | **Key Management System.** Orchestrates the lifecycle and distribution of cryptographic keys generated via QKD.                       |
| **LH₂**                  | **Liquid Hydrogen.** The primary cryogenic fuel for the AMPEL BWB Q100, valued for its high specific energy.                             |
| **PVB**                  | **Panoramic Viewing Belt.** The signature cabin system consisting of a continuous band of displays that provides a 360-degree virtual view. |
| **PVB Safety Note**      | PVB failure effects are bounded to Minor/Major; display blackout is mitigated per PSSA and is not a primary flight display.             |
| **QBER**                 | **Quantum Bit Error Rate.** The primary health and performance metric for a QKD link.                                                  |
| **QKD**                  | **Quantum Key Distribution.** A secure communication method using quantum mechanics to produce and distribute a cryptographic key.       |
| **SAF**                  | **Sustainable Aviation Fuel.** A biofuel used as an alternative or blend with conventional jet fuel. Reserved for future hybrid mission profiles. |

## 4. Aerospace Performance & Design Acronyms

| Term                  | Definition                                                                                                                                |
| :-------------------- | :---------------------------------------------------------------------------------------------------------------------------------------- |
| **AR**                | **Aspect Ratio.** The ratio of the wingspan squared to the wing area (b²/S).                                                                |
| **b**                 | **Wingspan.** The maximum distance from wingtip to wingtip.                                                                                |
| **BPR**               | **Bypass Ratio.** The ratio between the mass flow rate of the bypass stream to the mass flow rate entering the core of a turbofan engine.   |
| **c̄ (MAC)**           | **Mean Aerodynamic Chord.** The chord of an equivalent rectangular wing.                                                                    |
| **CD₀**               | **Zero-Lift Drag Coefficient.** A measure of parasitic drag. Per program convention, includes compressibility/wave drag at M 0.87.       |
| **CG**                | **Center of Gravity.** The point at which the aircraft's weight is considered to be concentrated.                                           |
| **CL**                | **Lift Coefficient.** A dimensionless coefficient relating lift to fluid density, velocity, and area.                                      |
| **e**                 | **Oswald Efficiency Factor.** A correction factor relating the induced drag of a real wing to an ideal elliptical wing.                  |
| **k**                 | **Induced Drag Factor.** A parameter used in the drag polar equation (k = 1 / (π · e · AR)).                                                  |
| **L/D**               | **Lift-to-Drag Ratio.** A primary measure of an aircraft's aerodynamic efficiency.                                                           |
| **MLW**               | **Maximum Landing Weight.** The maximum certified weight at which the aircraft is permitted to land.                                          |
| **MTOW**              | **Maximum Takeoff Weight.** The maximum certified weight at which the aircraft is permitted to begin the takeoff run.                       |
| **MZFW**              | **Maximum Zero Fuel Weight.** The maximum weight of the aircraft before usable fuel is loaded (OEW + Max Payload).                           |
| **OEW**               | **Operating Empty Weight.** The weight of the aircraft ready for flight, including crew and all systems, but excluding payload and fuel.     |
| **OPR**               | **Overall Pressure Ratio.** Ratio of compressor exit total pressure to inlet total pressure.                                                |
| **S**                 | **Wing Area.** The planform (top-down view) area of the wing.                                                                               |
| **T/W**               | **Thrust-to-Weight Ratio.** The ratio of the total engine thrust to the aircraft's weight.                                                |
| **TSFC_J**            | **Thrust-Specific Fuel Consumption** on Jet-A mass basis [lb/(lbf·hr)] (≈ kg/(N·s)).                                                         |
| **TSFC_H2 (index)**   | Program shorthand for LH₂ mass-basis efficiency relative to Jet-A (dimensionless index).                                                    |
| **Vapp**              | **Approach Speed.** The target speed during the final approach phase, typically 1.23 times the stall speed (Vs).                |
| **Vs**                | **Stall Speed.** The minimum steady flight speed at which the aircraft is controllable.                                                      |
| **W/S**               | **Wing Loading.** The ratio of the aircraft's weight to its wing area.                                                                      |

### 4.1 Symbols & Units Policy
*Scalars are italicized (*CL, CD, e, k, b, S, c̄*), while common variables such as **ρ** (air density), **a** (speed of sound), and **M** (Mach number) are also defined. Subscripts are plain (*CD₀, CLmax-TO*). SI units are primary; common aviation non-SI units are provided in parentheses. Angles are in degrees unless otherwise noted.*

## 5. Regulatory & Safety Acronyms

| Term               | Definition                                                                                                                                |
| :----------------- | :---------------------------------------------------------------------------------------------------------------------------------------- |
| **14 CFR Part 25** | **FAA Airworthiness Standards: Transport Category Airplanes.** The U.S. federal regulation for large civil aircraft.                     |
| **AMC/GM**         | **Acceptable Means of Compliance / Guidance Material.** Documents provided by EASA to support the certification process.                 |
| **ARINC 661**      | **Cockpit Display System (CDS) Interface.** Standard for defining the UI between the CDS and user applications (e.g., for PVB).         |
| **ARINC 664 P7 (AFDX)** | **Avionics Full-Duplex Switched Ethernet.** A deterministic Ethernet standard for safety-critical avionics networks.                |
| **ARP4754A**       | **Guidelines for Development of Civil Aircraft and Systems.** A key SAE standard for the systems engineering process.                      |
| **ARP4761A**       | **Guidelines and Methods for Conducting the Safety Assessment Process.** A key SAE standard for safety analysis (FHA, PSSA, SSA).        |
| **CS-25**          | **EASA Certification Specification for Large Aeroplanes.** The European airworthiness code for large civil aircraft.                       |
| **DAL**            | **Design Assurance Level.** A classification (A to E) of software and hardware criticality according to DO-178C and DO-254.                |
| **DO-160G/H**      | **Environmental Conditions and Test Procedures for Airborne Equipment.** A standard defining environmental test conditions.              |
| **DO-178C**        | The primary standard for certifying safety-critical software in airborne systems.                                                        |
| **DO-254**         | The primary standard for certifying safety-critical electronic hardware in airborne systems.                                               |
| **DO-326A**        | **Airworthiness Security Process Specification.** A standard for protecting aircraft systems from cybersecurity threats.                     |
| **DO-330**         | **Software Tool Qualification Considerations.** A supplement to DO-178C/DO-254 for qualifying development tools.                         |
| **DO-331**         | **Model-Based Development and Verification Supplement.** A supplement to DO-178C for model-based design.                                 |
| **DO-356A**        | **Airworthiness Security Methods and Considerations.** A guidance document supporting DO-326A.                                             |
| **EDTO**           | **Extended Diversion Time Operations.** The modern ICAO regulatory framework. The program adopts EDTO as the normative term.                |
| **ETOPS**          | **Extended-range Twin-engine Operational Performance Standards.** Legacy term still in common use; maps 1:1 to EDTO for this program.      |
| **FAA**            | **Federal Aviation Administration.** The primary civil aviation regulatory authority in the United States.                                 |
| **FHA**            | **Functional Hazard Assessment.** A systematic safety analysis process to identify and classify failure conditions.                       |
| **ICAO**           | **International Civil Aviation Organization.** A specialized agency of the United Nations that codifies global aviation standards.           |
| **MoC**            | **Means of Compliance.** The specific method (e.g., analysis, test) used to demonstrate that a system meets a certification requirement. |
| **OEI**            | **One Engine Inoperative.** A critical flight condition used for analyzing takeoff and climb performance.                                     |
| **PSSA**           | **Preliminary System Safety Assessment.** An early-phase safety analysis performed during the design process.                               |
| **Special Condition** | A set of unique airworthiness requirements prescribed by a regulatory authority for a novel design feature not covered by existing regulations. |

---
**Conventions Lock:** This glossary is normative for symbols, acronyms, and units across the AMPEL BWB Q100 program. Any deviations must be explicitly stated in the local document’s “Assumptions & Conventions” section.
---
[↑ Back to Top](#ampel-bwb-q100---glossary-and-abbreviations)
