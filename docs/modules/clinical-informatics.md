# Informatics in Clinical Care

## Stack Levels Most Relevant
> **Information System (4), Workflow/Adoption (5), Goals/Functions (6)**

---

## The EHR as the Hub

The **Electronic Health Record (EHR)** is, in Lehmann's framing, the canonical clinical *information system* — the layer that the user sees and interacts with. EHRs like Epic, Cerner (now Oracle Health), and MEDITECH aggregate structured data (labs, medications, problem lists) and unstructured data (clinical notes) to support clinical decision-making.

But for patients and advocates, the EHR has long been a **black box** — data goes in, but the patient rarely sees it or controls it.

### What Changed: FHIR and the Patient API

The **HL7 FHIR (Fast Healthcare Interoperability Resources)** standard, finalized in regulations under the 21st Century Cures Act, created a mandatory **Patient Access API** that requires covered health systems to expose patient data through standardized FHIR endpoints.

This means:

- Patients can now authorize third-party apps (using SMART on FHIR) to pull their own health records
- PAGs can build apps that request patients' consented data directly from their health system
- Registry platforms can populate automatically from EHR data rather than requiring manual re-entry

!!! example "Real-World Impact"
    A person living with ALS can now authorize the **Answer ALS** research platform to receive their longitudinal clinical data from their ALS clinic's EHR — reducing burden, improving accuracy, and enabling richer natural history research.

---

## Clinical Decision Support and Patient Populations

**Clinical Decision Support (CDS)** systems — embedded alerts, best-practice advisories, order sets — represent the *modules* and *algorithms* levels of the Stack in action. They:

- Alert prescribers to dangerous drug interactions
- Flag patients due for screenings
- Support REMS compliance workflows (see the [CodeX/REMS module](codex-rems.md))

From a patient advocacy standpoint, CDS is increasingly being used to:

- Identify rare disease patients who may be misdiagnosed (e.g., ALS patients waiting 9–12 months for a diagnosis)
- Surface clinical trial eligibility to treating physicians at point of care
- Prompt referrals to specialty centers and PAG resources

---

## Patient Portals and Engagement

Patient portals (MyChart, MyHealth, etc.) are the **interface layer** through which patients access their clinical data. Research consistently shows:

- Portal engagement is **highest among educated, English-speaking, non-elderly patients**
- **Disparities in access** remain significant — a major concern for patient advocates
- Portal design (Workflow level of the Stack) heavily influences whether patients actually engage

### Informatics Stack Application: Evaluating a Patient Portal

| Stack Level | Question to Ask |
|---|---|
| World | Does federal law mandate data availability here? (Yes — Cures Act) |
| Organization | Does the health system have an information-blocking policy? |
| Role | Who uses this portal — patient? Caregiver? Researcher? |
| Goals | What should the patient *do* with this data? |
| Workflow | Is the portal actually usable by someone with a progressive neuromuscular disease? |
| Information System | Does the portal surface FHIR-structured data that PAG apps can consume? |
| Modules | Is there a consent module for research data sharing? |
| Data/Knowledge | Are lab trends presented as information (graphs), not just raw values? |
| Technology | Is the portal accessible on mobile? Low bandwidth? |

---

## Care Coordination in Complex Disease

For patients with rare or serious conditions, clinical care involves **multiple specialists** across **multiple institutions**. Informatics solutions to care fragmentation include:

- **Care coordination platforms** (e.g., CommonWell, Carequality) that federate EHR data across systems
- **Health Information Exchanges (HIEs)** at state and regional level
- **Disease-specific networks** like NEALS for ALS, which create shared care protocols and trial-readiness infrastructure across 156 sites

<div class="patient-voice">
"My daughter's neurologist is at Children's Hospital, her geneticist is at the university, and her epileptologist is at a third system. None of them can see each other's notes. I am the health information exchange."
<cite>— Parent of a child with KCNQ2-related epilepsy</cite>
</div>

---

## Key Concepts

- **FHIR** (Fast Healthcare Interoperability Resources): The HL7 standard for exchanging healthcare data; the technical backbone of the 21st Century Cures Act APIs
- **SMART on FHIR**: An authorization framework allowing apps to access patient data with patient consent
- **CDS Hooks**: A standard for triggering decision support within EHR workflows at key moments (prescription, order entry, encounter)
- **Information Blocking**: Practices by health systems or vendors that impede access to EHI (Electronic Health Information); prohibited under the Cures Act
