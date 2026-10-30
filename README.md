# CSE443 — Object-Oriented Analysis and Design
## Term Project Deliverable #1: Requirements Analysis Document (RAD)
### Smart Personal Task Manager (SPTM)

---

## 👥 Team Members

| Name Surname | Student ID |
|---|---|
| **Zeynep Etik** | `220104004035` |
| **Sümeyye Dalga** | `220104004091` |
| **İbrahim Agah Arslan** | `220104004077` |

- **Issue Number:** 1.0
- **Issue Date:** 30 October 2026
- **Course:** CSE443 — Object-Oriented Analysis and Design

---

## 📄 Deliverable Files

| File | Description |
|---|---|
| 📄 [**CSE443_RAD_SPTM.docx**](./CSE443_RAD_SPTM.docx) | Complete Requirements Analysis Document (RAD) in Microsoft Word format following the course template. |
| 📕 [**CSE443_RAD_SPTM.pdf**](./CSE443_RAD_SPTM.pdf) | PDF export of the Requirements Analysis Document for layout-safe viewing. |
| 📋 [**Smart Personal Task Manager.docx**](./Smart%20Personal%20Task%20Manager.docx) | Client Problem Statement (referenced as `[1]` in the RAD). |

---

## 🧭 Overview of the Document

This **Requirements Analysis Document (RAD)** defines the functional and non-functional requirements and the conceptual object-oriented analysis model (UML 2.5) for the **Smart Personal Task Manager (SPTM)**.

SPTM bridges daily execution with long-term personal purpose by integrating two proven productivity methodologies:
1. **Stephen Covey’s *The 7 Habits of Highly Effective People*:** A personal **Mission Statement** (with versioning and hierarchical **Sub-missions**) acts as a compass, and tasks are prioritized across the four **Quadrants** of the Time Management Matrix.
2. **David Allen’s *Getting Things Done (GTD)*:** Commitments are captured in a low-friction **Inbox**, clarified into physical **Next Actions** tagged with **Contexts** (`@work`, `@home`, `@phone`, etc.), and reflected upon during a guided **Weekly Review**.

---

## 📑 Document Structure (Template Compliance)

1. **Introduction**
   - `1.1` Purpose of the system
   - `1.2` Scope of the system
   - `1.3` Objectives and success criteria of the project (`OBJ-1` – `OBJ-7`)
   - `1.4` Definitions, acronyms, and abbreviations
   - `1.5` References (`[1]` – `[10]`)
   - `1.6` Overview
2. **Current System**
   - Analysis of existing fragmented tools and current limitations (`Table 3`).
3. **Proposed System**
   - `3.1` Functional Overview (9 core modules)
   - `3.2` Functional Requirements (`FR-1` – `FR-52`, written using **EARS** syntax)
   - `3.3` Non-Functional Requirements (`NFR-1` – `NFR-29` across Usability, Reliability, Performance, Supportability, Implementation, Interface, Packaging, and Legal)
   - `3.4` System Models (UML 2.5):
     - `3.4.1` Scenarios (5 concrete actor-instance scenarios)
     - `3.4.2` Use Case Model (`UC-1` – `UC-20`, `Figures 1–3`, `Table 5`, and detailed Use Case Specifications)
     - `3.4.3` Object (Domain) Model (`Figure 4` conceptual class diagram and `Table 6` Entity/Boundary/Control analysis object dictionary)
     - `3.4.4` Dynamic Model (`Figures 5–7` Sequence Diagrams, `Figure 8` Task State Machine Diagram, `Figure 9` Weekly Review Activity Diagram)
     - `3.4.5` User Interfaces and Mock-ups (`Figure 10` Navigational Paths and `Figures 11–14` Screen Mock-ups)
4. **Glossary of Terms** (`Table 7`)
5. **Priority** (MoSCoW prioritization — `Tables 8–9`: 26 Must, 20 Should, 6 Could)
6. **Traceability** (`Tables 10–12`: Full backward and forward traceability between Problem Statement `PS-*`, Requirements `FR/NFR`, Use Cases `UC-1..20`, and Domain Classes)
