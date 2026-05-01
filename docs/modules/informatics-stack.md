# The Informatics Stack: A Framework for Patient-Centered Systems

## Overview

Harold Lehmann's **Informatics Stack** (2017, *Methods of Information in Medicine*) is a nine-level heuristic originally developed for graduate informatics education at Johns Hopkins. It organizes health IT systems from their foundational technology up through organizational goals and societal context — and has proven valuable as a teaching tool for students from backgrounds as varied as computer science, nursing, public health, and clinical medicine.

This curriculum adopts the Stack as its organizing spine. Every module maps onto one or more Stack levels, helping you see how a patient advocacy group (PAG), a wearable device, or a federal regulation fits into a coherent, structured picture of health information systems.

---

## The Nine Levels

The Stack is divided into a **lower half** ("how" — technical implementation) and an **upper half** ("what" — purpose and context), separated by a conceptual line.

<div class="stack-grid">

<div class="stack-card">
<div class="level-label">Level 9 — Uppermost</div>
<h4>🌍 World</h4>
<p>The political, economic, and policy context. Includes legislation like the 21st Century Cures Act and funding bodies like PCORI.</p>
</div>

<div class="stack-card">
<div class="level-label">Level 8</div>
<h4>🏢 Organization</h4>
<p>The local context — a hospital, a PAG, a rare disease network. For ALS TDI, the Organization is the advocacy institute; the World includes NIH and FDA.</p>
</div>

<div class="stack-card">
<div class="level-label">Level 7</div>
<h4>👤 Perspective / Role</h4>
<p>Patient, caregiver, clinician, researcher, advocate. One person may hold many roles — a patient-researcher is both consumer and producer of data.</p>
</div>

<div class="stack-card">
<div class="level-label">Level 6</div>
<h4>🎯 Goals / Functions</h4>
<p>What the system is meant to accomplish. For a PAG registry: collect natural history data; for a REMS system: ensure safe prescribing.</p>
</div>

<div class="stack-card">
<div class="level-label">Level 5 — "The Line"</div>
<h4>🔄 Workflow / Behavior / Adoption</h4>
<p>How people actually interact with the system. Adoption is often where patient-facing tools fail — wearables go unworn, portals go unused.</p>
</div>

<div class="stack-card">
<div class="level-label">Level 4</div>
<h4>💻 Information System</h4>
<p>The EHR, the patient registry platform, the FHIR-enabled portal. This is what the user sees and touches.</p>
</div>

<div class="stack-card">
<div class="level-label">Level 3</div>
<h4>🧩 Modules</h4>
<p>Software entities with a single function — a consent module, a data-entry form, a CDS Hooks alert for a REMS drug.</p>
</div>

<div class="stack-card">
<div class="level-label">Level 2</div>
<h4>📊 Data / Information / Knowledge / Algorithms (DIKW)</h4>
<p>How raw sensor readings become clinical knowledge. Wearable EEG data → seizure count → treatment decision.</p>
</div>

<div class="stack-card">
<div class="level-label">Level 1 — Foundational</div>
<h4>⚙️ Technology</h4>
<p>Hardware, networking, cloud storage. The iPhone that syncs wearable data; the FHIR server that exposes registry data.</p>
</div>

</div>

---

## Above the Line vs. Below the Line

A key teaching concept is **the Line** — the boundary between levels 5 and 4 (Workflow and Information System):

- **Above the Line** = *What* does the system need to accomplish? (Roles, Goals, Organization, World)
- **Below the Line** = *How* will it accomplish that? (Information System, Modules, Data, Technology)

!!! important "The Informatician's Translation Task"
    Lehmann describes the informatician's core job as **translating** between stakeholders speaking above-the-line language (needs, goals, policies) and technical teams working below the line (databases, APIs, FHIR). Patient advocates often speak *well above* the line — your role is to bridge that gap without losing their meaning.

---

## Vertical Issues

Several concerns cut *across* all levels of the Stack:

| Vertical Issue | Patient Advocacy Relevance |
|---|---|
| **Privacy** | Who owns patient-contributed registry data? Can a PAG sell it? |
| **Confidentiality** | De-identification requirements for rare disease registries |
| **Security** | Protecting wearable health streams from breach |
| **Ethics** | Informed consent for secondary research use of patient data |
| **Law** | HIPAA, 21st Century Cures Act, FDA REMS regulations |
| **Evaluation** | Are patient portals actually improving engagement? PCORI-style methods |

---

## Use Cases for This Curriculum

Lehmann described four Stack use cases. We adapt them for advocacy contexts:

1. **Readiness Assessment** — A PAG asks you to build a patient registry. Is the request well-formulated? What data standards should you use?
2. **IT Enthusiast** — A device company wants to donate wearables to an epilepsy PAG. Is there a clinical need that matches this technology?
3. **Formative Evaluation** — You are brought into an ongoing PCORI project and asked whether the patient engagement is meaningful. Is the project at risk?
4. **Report Review** — You are reviewing a CMSS/PLRC Scorecard submission from a rare disease research collaborative. Is it complete? Do the above- and below-the-line elements cohere?

---

## Further Reading

- Lehmann, H. (2017). The Informatics Stack: A Heuristic Tool for Informatics Teaching. *Methods of Information in Medicine*, 56(01), 1-10. [doi:10.3414/ME16-01-0152](https://doi.org/10.3414/ME16-01-0152)
