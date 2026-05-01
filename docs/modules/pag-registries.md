# Patient Advocacy Groups and Patient Registries

## Stack Levels Most Relevant
> **Organization (8), Goals/Functions (6), Information System (4), Modules (3)**

---

## What is a Patient Advocacy Group (PAG)?

A **Patient Advocacy Group** is an organization — often patient-founded — whose mission centers on a specific disease or condition. PAGs range from small, volunteer-run family foundations to large organizations with multi-million dollar research budgets.

Their activities span the entire Informatics Stack:

| Activity | Stack Level |
|---|---|
| Federal lobbying for research funding | World |
| Establishing governance for a patient registry | Organization |
| Training patient-researchers | Role |
| Defining research priorities | Goals |
| Building peer support networks | Workflow/Behavior |
| Hosting a registry platform | Information System |
| Designing data-entry forms | Modules |
| Defining data standards (HPO terms, HL7 FHIR) | Data/Knowledge |
| Hosting cloud infrastructure | Technology |

---

## Why PAGs Build Registries

For rare diseases, the traditional research model — waiting for academic researchers to study a small, dispersed population — is too slow. PAGs build **patient registries** to:

1. **Aggregate natural history data** that no single clinic could collect
2. **Accelerate clinical trial recruitment** by pre-identifying eligible patients
3. **Generate patient-reported outcomes (PROs)** that complement or replace clinician-observed endpoints
4. **Negotiate with regulators** using real-world data from their own community
5. **Attract pharmaceutical partners** by demonstrating an organized, data-rich patient population

!!! info "What is a Patient Registry?"
    A patient registry is an organized system that uses observational study methods to collect uniform data (clinical and patient-reported) to evaluate specified outcomes for a population defined by a particular disease, condition, or exposure.

---

## Registry Architecture: A Below-the-Line View

A modern patient registry involves several interconnected modules:

```
Patient enrollment & consent
         ↓
Patient-reported outcome (PRO) data entry
         ↓
Optional: EHR data passthrough (SMART on FHIR)
         ↓
Optional: Wearable / mHealth data ingestion
         ↓
Biospecimen tracking (biobank linkage)
         ↓
De-identification engine
         ↓
Research-ready data export (FHIR, CSV, HL7 CDA)
         ↓
External researcher access portal
```

---

## The Rare Epilepsy Network (REN)

The **Rare Epilepsy Network (REN)**, established by the Epilepsy Foundation, is a landmark example of PAG-led registry infrastructure:

- Funded by a **$3 million PCORI grant** in 2013
- Designed to collect and organize information about people with rare epilepsies
- The registry includes data on over **1,459 patients spanning 40 distinct rare epilepsy disorders**
- Data includes comorbidities, developmental milestones, seizure medications and side effects, and seizure history
- Designed explicitly to enable **patient-centered research** on conditions too rare for traditional clinical trials

!!! success "Why REN Matters"
    For conditions like KCNQ2-related epilepsy or Dravet syndrome, no single hospital sees enough patients to conduct research. REN aggregates data nationally — making research possible that simply couldn't happen otherwise.

---

## The National ALS Registry (CDC)

The **National ALS Registry**, administered by the CDC's Agency for Toxic Substances and Disease Registry (ATSDR), is the largest population-based ALS registry in the United States:

- Collects data on people with ALS to help scientists learn more about who gets the disease and why
- Patients self-enroll and contribute data through a secure web portal
- Links to **Medicare and Medicaid** administrative data for comprehensive longitudinal tracking
- Serves as the foundation for a **National ALS Biorepository** that collects and stores biospecimens

Partners include the ALS Association, NEALS, AnswerALS, the NIH, and patient advocacy organizations across the country.

---

## PRO-ACT: Pooled Resource Open-Access ALS Clinical Trials Database

Created through a partnership between Prize4Life (a patient-founded organization) and NEALS, **PRO-ACT** is one of the most ambitious examples of PAG-driven data aggregation:

- Houses the largest collection of ALS clinical trial datasets globally
- Contains placebo arm data from **11,675 people with ALS** who participated in industry, foundation, and academic trials
- Freely available to researchers — accelerating computational research on ALS biomarkers and disease progression
- Enabled machine learning studies of ALS progression that would have been impossible from any single trial

---

## Data Governance: The Above-the-Line Questions

<div class="patient-voice">
"When patients contribute data to a registry, they are making a gift to science. The least researchers can do is treat that gift with respect — which means being transparent about how the data will be used, who will profit from it, and whether patients will have a voice in those decisions."
<cite>— Sharon Terry, Genetic Alliance founder, patient advocate</cite>
</div>

Key governance questions every registry must answer:

- **Who owns the data?** The patient? The PAG? The hosting institution?
- **What secondary uses are permitted?** Commercial? Academic only?
- **Can data be shared with pharmaceutical companies?**
- **What consent model is used?** Broad consent? Tiered consent? Dynamic consent?
- **What are the rights of withdrawal?**

!!! tip "Informatics Stack Connection"
    These are **World and Organization** level questions. Trying to answer them at the Modules level (in a consent form) without first resolving them at the governance level is a common and costly mistake.

---

## Key Frameworks and Resources

- [National Organization for Rare Disorders (NORD) Registry](https://rarediseases.org)
- [Global Rare Disease Patient Registry & Data Repository (GRDR)](https://grdr.ncats.nih.gov)
- [FDA Guidance on Natural History Studies for Rare Diseases](https://www.fda.gov/patients/rare-diseases-fda)
- [PCORI Patient Engagement Rubric](https://www.pcori.org)
