# Applying the Informatics Stack to Patient Advocacy

## Mapping Advocacy Work to the Stack

One of the most powerful things about Lehmann's Informatics Stack is that it reveals how patient advocacy work — which often *feels* like it lives entirely above the line — actually requires engagement at every level.

Consider a **Patient Advocacy Group (PAG)** that wants to build a patient registry for a rare neurological disease. Here is how that project maps across all nine levels:

---

## A Worked Example: The PAG Registry Project

=== "World (Level 9)"

    **Context:** The PAG operates in a world shaped by:

    - The **21st Century Cures Act** (2016), which mandates data interoperability and prohibits information blocking
    - **PCORI's** mandate to fund patient-centered comparative effectiveness research
    - **FDA's** Rare Disease Policy Office and the Orphan Drug Act
    - **NIH's** National Center for Advancing Translational Sciences (NCATS), which funds rare disease infrastructure

    **Advocate's role here:** Engage in federal comment periods, lobby for funding allocations, participate in FDA Patient-Focused Drug Development meetings.

=== "Organization (Level 8)"

    **Context:** The PAG itself is an organization, but it operates within a larger ecosystem:

    - Academic medical centers that may host the registry
    - Pharmaceutical sponsors interested in natural history data
    - IRBs and data governance boards

    **Advocate's role here:** Negotiate data-sharing agreements, establish governance structures (who controls data?), define membership and leadership.

=== "Perspective / Role (Level 7)"

    **Key roles in a PAG registry:**

    | Role | Who Fills It |
    |---|---|
    | Patient-participant | Person living with the disease |
    | Patient-researcher | Patient with scientific training |
    | Data contributor | Clinician submitting EHR extracts |
    | Registry steward | PAG staff or academic partner |
    | Secondary researcher | External scientist accessing de-identified data |

    !!! note
        The same person may occupy multiple roles — a PAG founder may simultaneously be a patient, a caregiver, and a scientific advisory board member.

=== "Goals / Functions (Level 6)"

    **What the registry needs to accomplish:**

    - Capture natural history: how does this disease progress over time?
    - Enable clinical trial recruitment (finding eligible patients quickly)
    - Generate patient-reported outcomes that regulators will accept as endpoints
    - Support comparative effectiveness research without requiring a controlled trial

=== "Workflow / Behavior / Adoption (Level 5)"

    **This is where most patient-facing systems fail.**

    - How will patients enroll? (Web form? Clinic referral? mHealth app?)
    - How often will they contribute data? (One-time? Quarterly? Continuous via wearable?)
    - What burden does this place on patients who are already managing illness?
    - Will clinicians remember to submit data?

    <div class="patient-voice">
    "I'm exhausted just from managing my disease. If the registry takes more than five minutes a week, I'm not going to maintain it."
    <cite>— PAG focus group participant (composite)</cite>
    </div>

=== "Information System (Level 4)"

    **Platform options:**

    - Commercial registries (REDCap, Castor, OpenClinica)
    - PAG-built platforms (e.g., NORD's patient registry infrastructure)
    - FHIR-enabled patient portals that allow EHR data passthrough
    - PatientsLikeMe-style social + research hybrid platforms

=== "Modules (Level 3)"

    **Key modules in a registry:**

    - Consent and enrollment module
    - Patient-reported outcome (PRO) questionnaire module
    - Clinician data-entry form
    - Biospecimen tracking module
    - De-identification and data export module
    - API endpoint for external researchers

=== "Data / Information / Knowledge (Level 2)"

    **The DIKW hierarchy in action:**

    - **Data:** Raw survey responses, EHR extracts, wearable sensor readings
    - **Information:** Aggregated tables of symptom progression by age of onset
    - **Knowledge:** "Patients with phenotype X progress faster and are better candidates for trial Y"
    - **Wisdom:** Knowing when to trust the registry data vs. when sample bias limits conclusions
    - **Algorithms:** Natural language processing to extract phenotype from clinical notes; ML models to predict disease trajectory

=== "Technology (Level 1)"

    **Infrastructure considerations:**

    - Cloud hosting (AWS GovCloud, Azure for healthcare) for HIPAA compliance
    - RESTful APIs and HL7 FHIR R4 for interoperability
    - OAuth 2.0 / SMART on FHIR for patient authentication
    - End-to-end encryption for data in transit and at rest

---

## The Line in Advocacy Contexts

<div class="patient-voice">
"Without the Stack framework, I would have conflated Goals with Workflow — I kept trying to describe what we wanted to achieve using IT language, and the developers kept proposing solutions without understanding the disease context."
<cite>— Informatics student reflection (adapted from Lehmann 2017)</cite>
</div>

Patient advocates often speak in goals language: *"We need to know which patients are deteriorating fastest."* Developers may hear that and immediately propose a machine learning model. The Stack reminds the informatician to first nail down:

- **Who** is asking (Role)?
- **In what context** (Organization/World)?
- **What workflow** will they use the prediction in (Workflow)?
- **Only then**: What data and algorithms are needed (DIKW/Algorithms)?

---

## Key Takeaway

The Informatics Stack is not just an academic exercise. When patient advocates walk into a meeting with a health system or a technology company, they are navigating all nine levels simultaneously. The Stack gives informaticians a shared vocabulary to surface what might otherwise be missed — from governance structures (above the line) to data standards (below the line).
