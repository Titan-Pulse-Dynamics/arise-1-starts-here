
# ARISE-1
### Mission Overview & Engineering Resources

**Titan Pulse Dynamics**

[Official Website](https://titanpulsedynamics.com/) · [LinkedIn](https://www.linkedin.com/company/titan-pulse-dynamics/)

Welcome to **ARISE-1**, a modular, AI-enabled 3U CubeSat platform under development by Titan Pulse Dynamics.

ARISE-1 is designed around a standardized spacecraft bus and mission-specific payload cards, with a tiered computing architecture intended to support onboard data processing, Edge AI, and multiple potential mission applications.

This repository provides an entry point for understanding the project, navigating its system architecture, and accessing useful CubeSat engineering resources.

---

## 1. Project Overview

ARISE-1 follows a modular spacecraft architecture designed to separate the standardized bus from mission-specific payload functionality.

**Core architectural principles**

- **Modular design:** A standardized bus architecture with mission-specific payload configurations.
- **Tiered computing:** Separation of supervisory control, Linux-based processing, and dedicated AI inference.
- **Fault isolation:** Independent power regulation and supervisory control are part of the design baseline.
- **Open-source design heritage:** Publicly available OreSat design resources inform the architectural approach.

### Mission Concepts Under Consideration

The current mission profile considers the following potential applications:

- Earth observation with onboard AI processing.
- Internet of Things (IoT) data relay.
- Multi-tenant in-orbit technology testbed.

These are mission concepts under consideration, not a statement that all three missions are confirmed or scheduled for flight.

---

## 2. System Architecture

ARISE-1's current computing architecture is organized into three tiers.

| Tier | Primary Role |
|---|---|
| Tier 1 — Watchdog | Command and telemetry supervision, safe-mode control, and hardware fault recovery |
| Tier 2 — Processing Host | Linux-based payload processing, data management, and AI pipeline orchestration |
| Tier 3 — AI Accelerator | Dedicated hardware acceleration for onboard AI inference |

The architecture is intended to support mission-specific payload processing while maintaining supervisory control and fault isolation.

### System Block Diagram

The block diagram provides a high-level view of the spacecraft subsystems and their interfaces.

<img width="1026" height="1634" alt="ARS-TPD-SYS-BD_Iss01r00" src="https://github.com/user-attachments/assets/938039b7-29b7-48d1-bc81-ab426d8736c8" />

<!-- Replace the link above with the actual relative path or URL of the uploaded SVG file. -->

---

## 3. OreSat Open-Source Design Reference

ARISE-1 draws on publicly available design resources from the **OreSat open-source CubeSat project**, particularly its modular card-cage architecture.

The ARISE-1 team is evaluating and developing its own implementation of relevant architectural concepts to meet the platform's mission, interface, and engineering requirements.

This section describes a design reference and development approach. It does not imply a formal partnership, joint mission, endorsement, or signed collaboration agreement with OreSat.

Potential future collaboration may be explored separately, subject to mutual agreement.

**Reference resources**

- [OreSat Open-Source Project](https://www.oresat.org/About-PSAS/open-source)
- [OreSat GitHub Organization](https://github.com/oresat)

When using or modifying upstream design files, consult the license and attribution requirements of the specific OreSat repository.

---

## 4. CubeSat Engineering Resources

The following references support CubeSat familiarization, preliminary design, and interface planning.

### NASA CubeSat 101

An introduction to the basic concepts and processes involved in developing CubeSat missions.

[Read NASA CubeSat 101 (PDF)](https://science.nasa.gov/wp-content/uploads/2023/06/nasa_csli_cubesat_101_508.pdf)

### CubeSat Design Specification (CDS)

The project mission profile references the CubeSat Design Specification for 1U–12U spacecraft, Revision 14.1.

[Access the CubeSat Design Specification and related resources](https://static1.squarespace.com/static/5418c831e4b0fa4ecac1bacd/t/62193b7fc9e72e0053f00910/1645820809779/CDS+REV14_1+2022-02-09.pdf)

The applicable specification revision, launch-provider requirements, and mission-specific compliance obligations must be verified during detailed design.

### Additional Engineering Resources

- [NASA CubeSat Launch Initiative Resources](https://www.nasa.gov/kennedy/launch-services-program/cubesat-launch-initiative/cubesat-launch-initiative-resources/)


---

## 5. Project Documentation

The Mission Profile & ARISE-1 Overview defines the current platform concept, architectural principles, interfaces, mission profiles, and compliance verification approach.

Controlled engineering documents and approved subsystem documentation should be accessed through the team's designated documentation repository or workspace.

Subsystem-specific documentation and additional project resources may be added to this README as they become available and are approved for publication.

---

## 6. Contact Us

**Titan Pulse Dynamics**

- **Official Website:** [titanpulsedynamics.com](https://titanpulsedynamics.com/)
- **LinkedIn:** [Titan Pulse Dynamics on LinkedIn](https://www.linkedin.com/company/titan-pulse-dynamics/)
- **General Inquiries:** [info@titanpulsedynamics.com](mailto:info@titanpulsedynamics.com)
- **Open-Source Collaboration:** [collab@titanpulsedynamics.com](mailto:collab@titanpulsedynamics.com)
  
**Open-source collaboration inquiries**

For collaboration inquiries, please email the team using a relevant subject category:

`Agency`, `Professional`, `Student`, `Supplier`, `Sponsor`, `Investor`, or `General`.



---

*This README is an introductory project reference. Technical details, interfaces, and mission configurations remain subject to engineering review and controlled documentation updates.*
