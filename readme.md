# OWP Governance Sandbox

Welcome to the official NOAA Office of Water Prediction (OWP) Governance Pipeline and Sandbox environment. 

This repository serves as the centralized location for coordinating, triaging, and accelerating the transition of collaborative hydrologic research into national operational capabilities.

## The TRL Scale
To manage portfolio risk and ensure scientific integrity, OWP categorizes all incoming collaborative work using the standardized Federal Technology Readiness Level (TRL) scale:

* **TRL 1-3 (Research):** Basic scientific principles observed; formulation of research concepts and prototype implementation.
* **TRL 4-5 (Development):** System integration, software quality validation, and integrated testing in simulated environments.
* **TRL 6-7 (Demonstration):** Pre-operational system demonstration, technical performance evaluation, and Operational Readiness Review (ORR).
* **TRL 8-9 (Operations):** Final system integration, successful operational deployment, and full operational capability.

---

## The OWP Governance Gates
To guarantee that external code is stable, compliant, and ready to scale, all submissions must sequentially clear five mandatory OWP Governance Gates:

* **Gate 1: Technical Integration (Requires SG1):** Verifies code quality, automated test coverage standards, and initial system architecture alignment.
* **Gate 2: Environmental Compliance (Requires SG2):** Confirms development environment compatibility and validates that the technology is cloud-agnostic using Infrastructure as Code (IaC) baselines.
* **Gate 3: Operational Readiness Review (Requires SG3):** Evaluates end-to-end reliability, system dependencies, performance benchmarks, and user validation.
* **Gate 4: Security & Risk Assessment (Requires SG4):** Executes exhaustive code vulnerability scans, dependency audits, and verifies open-source licensing compliance.
* **Gate 5: Full Operational Acceptance (Sustainment - Requires SG5):** Grants final clearance for deployment into production and transitions the code to long-term federal maintenance and support.

---

## 🚀 External Stakeholder Portal

To engage with the OWP Governance process, please utilize the authorized secure portals below:

* **[SUBMIT SCIENTIFIC RFC / NEW PROJECT](https://github.com/KyleWinter-NOAA/owp-governance-sandbox/issues/new?template=01-EXTERNAL-INTAKE.yml&projects=KyleWinter-NOAA/1)**
    *Use this high-fidelity form for all partner submissions to declare TRL status, product focus, and complete mandatory security acknowledgments.*

* **[REPORT A TECHNICAL BUG](https://github.com/KyleWinter-NOAA/owp-governance-sandbox/issues/new?template=02-technical-bug.yml&projects=KyleWinter-NOAA/1)**
    *Mandatory portal for all software failures; requires step-by-step replication instructions and expected vs. actual results per OWP SOP.*

* **[VIEW GOVERNANCE DASHBOARD](https://github.com/users/KyleWinter-NOAA/projects/1/views/1)**
    *Monitor the real-time status of active submissions as they move through the OWP Governance Gates.*
