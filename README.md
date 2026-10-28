# ✈️ AeroSupply - MRO Station Prototype

![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)

A high-fidelity frontend web prototype for an aviation Maintenance, Repair, and Overhaul (MRO) inventory and procurement management system. This project simulates complex enterprise workflows, business logic validations, and interactive UI/UX without requiring a backend.

**🔗 [Live Demo: AeroSupply MRO Station](https://juancho1221.github.io/aerosupply-prototype/)**

---

## 🎯 Project Overview

AeroSupply is designed to manage the end-to-end lifecycle of aircraft parts requisition, procurement, and warehouse receiving. The interface enforces strict aviation governance policies, such as Aircraft On Ground (AOG) alerts, managerial financial approvals, and physical inspection quarantines.

This prototype was developed to visually validate User Stories and UML diagrams for a Software Engineering academic project.

## ⚙️ Core Modules & Features

### 1. Requisition Management
* **Create Request:** Line mechanics can request parts tied to specific aircraft tail numbers.
* **AOG Protocol:** Selecting "AOG" (Aircraft On Ground) urgency triggers visual alerts and alters the approval workflow.
* **Duplicate Prevention:** The system blocks new requests if an active order for the same part and aircraft already exists.

### 2. Procurement & Quotes
* **Vendor Directory:** Search and filter certified aviation suppliers (FAA/TCCA approved).
* **Quotes Comparison:** Compare vendor quotes based on Unit Price, Freight, and Lead Time.
* **Managerial Approval Policy:** Automated governance triggers. If a quote exceeds $1,500 USD or is flagged as AOG, it requires explicit approval from a Maintenance Manager. Rejections require a mandatory justification.
* **Purchase Order (PO) Issuance:** Finalize procurement by assigning payment methods (Corporate Card, Net 30, Wire Transfer).

### 3. Logistics & Warehouse Receiving
* **Dispatch Tracking:** Assign carriers (FedEx, DHL) and AWB tracking numbers to purchased items.
* **Physical Inspection:** Warehouse clerks must match scanned part numbers with expected data.
* **Quality Assurance (Quarantine):** If the packaging is damaged or the part numbers mismatch, the system automatically routes the component to "Quarantined" (Red Tag). If intact, it moves to "In Stock".

---

## 📋 Agile User Stories Implemented

This prototype successfully fulfills the Acceptance Criteria for the following BDD-structured User Stories:
* **HU-001:** Technical Requisition Registration
* **HU-002:** Requisition Status & Tracking
* **HU-003:** Approved Vendor Directory
* **HU-004:** Vendor Quotes Comparison
* **HU-005:** Executive Purchase Approval Thresholds
* **HU-006:** Purchase Order Generation
* **HU-007:** Logistics Dispatch Tracking
* **HU-008:** Physical Receiving and Inspection

## 🛠️ Technical Stack
* **HTML5:** Semantic structure and accessibility.
* **Vanilla CSS3:** Custom CSS variables, Flexbox/Grid layouts, responsive design, and interactive UI states (no external CSS frameworks used).
* **Vanilla JavaScript (ES6+):** DOM manipulation, modal handling, dynamic data rendering, and client-side business logic validation.
* **FontAwesome:** Scalable vector icons.

---
*Developed as part of a Software Engineering curriculum focusing on UI/UX simulation and requirement traceability.*
