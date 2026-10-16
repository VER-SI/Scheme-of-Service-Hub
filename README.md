# Scheme of Service Hub (SoSH)

> ⚠️ **Note:** This project was developed for internal government use at the Public Service Department (Jabatan Perkhidmatan Awam - JPA), Brunei Darussalam. Due to data privacy and government security protocols, the source code, live links, and screenshots are restricted. This repository serves as a technical showcase and portfolio documentation of the system's architecture, impact, and engineering workflow.

---

## Executive Overview

**Scheme of Service Hub (SoSH)** is a centralized web application built to digitize and streamline how Schemes of Service are drafted, reviewed, and approved across the Brunei civil service. 

Prior to this project, managing these frameworks relied on fragmented paper records and static PDF documents. As an **individual intern project**, I designed and engineered SoSH from the ground up to replace those manual procedures with an automated, guided digital platform.

---

## Key Achievements & Technical Architecture

* 🔄 **Workflow Optimization:** Redesigned a legacy 12-step manual drafting and approval process into a streamlined 8-step guided digital workflow featuring multi-tier administrative approvals.
* 🔐 **Security & Role-Based Access (RBAC):** Implemented strict role-based access controls for 4 distinct user tiers, complete with email validation protocols and accidental-deletion safeguards.
* 🗄️ **Database Normalization:** Cleaned and structured unstructured legacy source data into a fully normalized MySQL database—mapping complex relational models between users, scheme templates, submissions, and department assignments.
* 🎨 **User Experience & Prototyping:** Designed high-fidelity prototypes using Figma and Visily, conducting hands-on usability testing sessions with Research & Planning Division (RPD) officers to establish an intuitive, unified admin dashboard.

---

## Tech & Tools

* **Backend:** Laravel (PHP)
* **Database:** MySQL
* **Frontend:** Tailwind CSS, Blade Templates
* **UI/UX Design:** Figma, Visily

---

## Lessons Learned & Professional Growth

Working independently on a high-level public sector project provided deep experience beyond software development:

### 🏛️ Public Sector Dynamics & Workflow Engineering
* **Government Operations:** Gained a practical understanding of civil service hierarchy, administrative procedures, and how government divisions process policy and regulatory documentation.
* **Domain Modeling:** Learned to translate complex civil service salary structures, rank scales, and multi-tier approval rules directly into executable software logic.

### 🗣️ Stakeholder Consulting & Technical Communication
* **Non-Technical Consulting:** Bridged the gap between software engineering and government operations by gathering requirements from non-technical stakeholders and conducting alignment meetings with division heads.
* **Formal Documentation:** Authored executive project documentation, technical feasibility reports, and institutional impact roadmaps.
* **Executive Presentations:** Strengthened public speaking and presentation skills by delivering architecture reviews and deployment roadmaps to department decision-makers.
