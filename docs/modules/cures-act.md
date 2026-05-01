# Regulation & Policy: The 21st Century Cures Act

## Stack Levels Most Relevant
> **World (9), Organization (8), Goals/Functions (6)**

---

## Overview

The **21st Century Cures Act**, signed into law in December 2016, is one of the most consequential pieces of health IT legislation in U.S. history. It directly addresses many of the informatics gaps that patient advocates had been fighting for years: fragmented data, inaccessible records, and health systems that treated patient data as a proprietary asset.

For patient advocates and informaticians, understanding the Cures Act is understanding the **World-level context** within which all clinical and research informatics systems now operate.

---

## Key Provisions Relevant to Patient Advocates

### 1. Information Blocking Prohibition

**What it says:** Health IT developers, health information networks, and healthcare providers are **prohibited from information blocking** — practices that are likely to interfere with the access, exchange, or use of electronic health information (EHI).

**What it means for advocates:**
- Health systems can no longer charge excessive fees to access patient data
- Vendors cannot build systems that make data export deliberately difficult
- Patients have stronger legal grounds to demand their records
- PAGs that build FHIR-based apps have the right to access patient-consented data

**Exceptions:** Eight defined exceptions exist (e.g., for security, privacy, infeasibility), but the burden is on the organization to demonstrate the exception applies.

### 2. Standardized Patient Access API

**What it says:** Health systems and payers must implement standardized **FHIR-based Patient Access APIs** to enable patients and their authorized apps to access their health records.

**What it means for advocates:**
- Any smartphone app can, with patient consent, request a complete health record from any Cures-compliant health system
- PAG registry platforms can offer one-click EHR data import for research participants
- Reduces the burden on patients to manually re-enter clinical data

### 3. ONC Health IT Certification

**What it says:** The Office of the National Coordinator for Health IT (ONC) updated its certification criteria for EHRs to require FHIR R4 compliance, standardized clinical terminology (SNOMED CT, LOINC, RxNorm), and support for SMART on FHIR apps.

**What it means for advocates:**
- Creates a level playing field — all certified EHRs must speak the same language
- Patient-facing apps built on FHIR work across health systems, not just within one vendor's ecosystem

### 4. Electronic Prior Authorization

**What it says:** Payers must support electronic prior authorization workflows using FHIR standards.

**What it means for advocates:**
- Reduces delays in patients accessing specialty medications (including REMS drugs)
- Supports automated prior authorization for rare disease therapies that require extensive documentation

---

## The FDA Provisions: Accelerating Drug Development

The Cures Act also includes major FDA-focused provisions directly relevant to rare disease communities:

### Breakthrough Therapy and Regenerative Advanced Therapy (RMAT) Designations

New expedited pathways for:
- Drugs targeting serious conditions with early evidence of substantial improvement
- Cell and gene therapies for life-threatening diseases

These designations matter for PAGs because they **enable earlier access to promising therapies** and create opportunities for patient advocates to participate in the development process through FDA Patient-Focused Drug Development meetings.

### Real-World Evidence

The Cures Act explicitly authorizes FDA to use **real-world evidence (RWE)** — including data from patient registries, EHRs, and claims databases — to support:
- Approval of new indications for approved drugs
- Post-market safety and effectiveness studies

This is transformative for rare disease PAGs: registry data they have been collecting for years can now support regulatory submissions.

---

## Patient Advocates and the Regulatory Process

### FDA Patient-Focused Drug Development (PFDD)

Under the Cures Act, FDA is required to hold **externally-led Patient-Focused Drug Development meetings** — forums where patients, families, and advocates can formally communicate their experience of disease, priorities for treatment, and views on benefit-risk tradeoffs.

**Key points for advocates:**
- PFDD meeting transcripts and summaries are incorporated into FDA review processes
- PAGs can submit **Voice of the Patient** reports that become part of the regulatory record
- Patients can request FDA meetings and influence trial endpoint selection

!!! example "ALS Community Impact"
    ALS patient advocates successfully advocated for the inclusion of **patient-reported functional status** and **digital biomarkers** as acceptable endpoints in ALS trials — a direct result of sustained FDA engagement through PFDD and related mechanisms.

---

## Remaining Challenges

Despite significant progress, gaps remain:

- **FHIR APIs are implemented unevenly** — smaller or rural health systems may lag in compliance
- **Information blocking enforcement** has been slower than advocates hoped
- **Patient data literacy** varies widely — access to data is meaningless without support in understanding it
- **PGHD (patient-generated health data)** remains incompletely addressed — wearable and home monitoring data are not yet fully integrated into the regulatory framework

---

## Informatics Stack Summary

| Stack Level | Cures Act Connection |
|---|---|
| World | The Act itself is the world-level policy context |
| Organization | Health systems must comply or face OIG penalties |
| Role | Advocates, patients gain new legal standing as data requesters |
| Goals | Goal: interoperability, access, innovation |
| Workflow | FHIR APIs change how patients and researchers interact with health data |
| Information System | EHRs must be Cures-certified; patient portals must expose FHIR endpoints |
| Modules | Patient Access API, SMART on FHIR launcher, prior auth module |
| Data | Standardized terminologies (LOINC, SNOMED CT, RxNorm) mandated |
| Technology | FHIR R4 as the technical standard |

---

## Additional Resources

- [ONC 21st Century Cures Act Final Rule (2020)](https://www.healthit.gov/curesrule/)
- [CMS Interoperability and Patient Access Final Rule](https://www.cms.gov/Regulations-and-Guidance/Guidance/Interoperability/index)
- [FDA Patient-Focused Drug Development Guidance](https://www.fda.gov/drugs/development-approval-process-drugs/patient-focused-drug-development)
- [ONC Information Blocking](https://www.healthit.gov/topic/information-blocking)
