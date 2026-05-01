# REMS Programs & HL7 CodeX

## Stack Levels Most Relevant
> **Modules (3), Data/DIKW (2), Workflow/Adoption (5), Goals/Functions (6)**

---

## What is a REMS Program?

A **Risk Evaluation and Mitigation Strategy (REMS)** is a drug safety program that the U.S. Food and Drug Administration (FDA) requires for certain medications with serious safety concerns — designed to ensure that the benefits of these drugs outweigh their risks.

As of early 2025, there are approximately **73 active REMS programs**, with about 94.5% requiring "elements to assure safe use." Examples of drugs requiring REMS include:

- **Isotretinoin (iPLEDGE)** — teratogenicity requiring monthly pregnancy testing
- **Clozapine** — agranulocytosis requiring regular absolute neutrophil count monitoring
- **Thalidomide and analogues (RevAssist/REMS)** — severe birth defects
- **CAR-T cell therapies** — cytokine release syndrome risk
- **Opioid analgesics** — misuse and addiction

### REMS Requirements Can Include:
- Provider certification before prescribing
- Patient enrollment and education
- Pharmacy enrollment and dispensing restrictions
- Ongoing patient monitoring and lab testing
- Periodic reporting to FDA

---

## The Problem: REMS Burden on Patients and Providers

REMS programs save lives. But their **implementation has historically been cumbersome**:

- Providers must enroll in separate, drug-specific portals — often outside their EHR workflow
- Patient enrollment forms require manual re-entry of data already in the EHR
- Pharmacies must independently verify REMS compliance before dispensing
- Delays in completing REMS steps mean patients wait longer to start treatment

For patients with rare diseases or serious conditions, these delays are not just inconvenient — they can be **dangerous**.

<div class="patient-voice">
"I had a prescription written. The REMS paperwork took three weeks. Three weeks. For a drug I needed immediately."
<cite>— Patient with a rare hematologic disorder</cite>
</div>

---

## HL7 CodeX: The Standards-Based Solution

**CodeX™** (Common Oncology Data Elements eXtensions) is a HL7 FHIR Accelerator Program — a community of stakeholders using HL7 FHIR to solve specific interoperability problems. While initially focused on oncology, CodeX has expanded into **REMS automation** as one of its core use cases.

### The CodeX REMS Integration Use Case

The CodeX REMS use case is an open, collaborative, stakeholder-driven approach to developing a **scalable, standards-based solution for REMS integration** — using FHIR to connect EHR workflows directly to REMS Administrator systems.

Key capabilities enabled by the FHIR-based REMS IG (Implementation Guide):

=== "CDS Hooks Integration"
    When a provider considers prescribing a REMS drug, a **CDS Hooks alert** fires within the EHR workflow — surfacing REMS requirements, enrollment steps, and pre-filled forms *without* the provider leaving their EHR.

    This is a **Modules-level** solution that dramatically improves **Workflow-level** compliance.

=== "SMART App Launch"
    REMS enrollment applications can launch directly within the EHR as a SMART on FHIR app — pre-populated with patient data already in the record. Providers see one system, not two.

=== "Automated Data Exchange"
    Patient monitoring data (e.g., lab results confirming neutrophil counts are safe for clozapine) can be **automatically transmitted** to the REMS Administrator via FHIR, replacing manual fax or portal entry.

=== "Patient Enrollment Automation"
    Patient registration for a REMS program can be initiated from the EHR at the time of prescribing, with consent collected via patient portal — eliminating the paper-based enrollment delay.

---

## What This Means for Patient Advocates

From an advocacy perspective, REMS automation through CodeX represents a convergence of **below-the-line technical work** (FHIR standards, CDS Hooks) with **above-the-line goals** (getting patients onto needed medications faster).

Implications for PAGs and patient advocates:

1. **Reduced time-to-treatment** for REMS-required medications — critical for progressive diseases
2. **Better adherence monitoring data** — captured automatically, not via manual reporting
3. **Reduced disparities** — current REMS burden falls disproportionately on patients with fewer resources to navigate complex paperwork
4. **Richer real-world data** — automated REMS data flows can support post-market surveillance and regulatory submissions

!!! info "Informatics Stack Connection"
    CodeX REMS is an excellent below-the-line (Modules, Data, Technology) solution to an above-the-line problem (Goals: get patients on safe medications efficiently; Workflow: don't add burden to already-stressed clinical teams).

    As an informatician working with patient advocates, your job is to help advocates understand *what* technical standards like FHIR enable — and to help developers understand *why* the patient's experience demands it.

---

## The White House Cancer Moonshot Connection

CodeX's REMS work was cited by the White House Office of Science and Technology Policy (OSTP) in connection with the **Biden Cancer Moonshot** initiative — recognition that FHIR-based interoperability for high-risk oncology drugs is not just a technical nicety but a patient safety imperative.

---

## Key Resources

- [HL7 CodeX REMS Integration Use Case](https://confluence.hl7.org/display/COD/Risk+Evaluation+and+Mitigation+Strategies+(REMS)+Integration)
- [FDA REMS Public Dashboard](https://www.accessdata.fda.gov/scripts/cder/rems/index.cfm)
- [CodeX REMS FHIR Implementation Guide](https://confluence.hl7.org/spaces/FHIR/pages/204277715/CodeX+Medication+Risk+Evaluation+and+Mitigation+Strategies+REMS+FHIR+IG)
- [NCPDP REMS Standards Work](https://www.ncpdp.org)
