# Rare Epilepsy Community: Patient-Led Informatics

## Stack Levels Most Relevant
> **Organization (8), Role (7), Information System (4), Technology (1), Data/DIKW (2)**

---

## The Rare Epilepsy Landscape

Epilepsy is one of the most common neurological conditions — affecting over 3.4 million people in the United States. But epilepsy is considered **rare** when the underlying cause affects fewer than 200,000 people in the U.S. There are dozens of such rare epilepsies, including:

- **Dravet syndrome** (SCN1A mutation)
- **KCNQ2-related epilepsy**
- **Lennox-Gastaut syndrome**
- **Angelman syndrome**
- **Tuberous sclerosis complex**
- **CDKL5 deficiency disorder**

Each of these conditions is, by definition, too rare for traditional clinical trials to easily recruit sufficient participants. This is precisely where patient advocacy and informatics intersect most powerfully.

---

## The Rare Epilepsy Network (REN)

The **Rare Epilepsy Network (REN)**, housed within the Epilepsy Foundation, is one of the clearest examples of PCORI-funded, PAG-driven informatics success.

### Origins and Funding

- Established in **2013** with a **$3 million PCORI grant**
- Designed from the ground up as a **patient-centered research infrastructure** — patients and families helped define the data elements that mattered most
- Built as a **federated network** representing multiple rare epilepsy patient advocacy groups, each with their own member populations

### What REN Accomplished

- Built a registry capturing data on over **1,459 patients spanning 40 distinct rare epilepsy disorders**
- Data elements include: comorbidities, developmental milestones, seizure medications and side effects, seizure history, quality of life measures
- Enabled **cross-condition research** impossible within any single rare epilepsy group
- Demonstrated that patient-contributed registry data could meet research-grade quality standards

!!! success "Why This Matters"
    Before REN, a researcher studying KCNQ2-related epilepsy might have access to 20 patients. After REN, they could access 200+ — a difference that transforms what research questions can be asked.

---

## Individual PAG Contributions to Registry Infrastructure

### CURE Epilepsy

**CURE Epilepsy** (Citizens United for Research in Epilepsy) funds research and advocacy with a strong informatics component:

- Supports the **SUDEP (Sudden Unexpected Death in Epilepsy) Institute** — tracking this rare but devastating outcome
- Funds research into wearable-based early warning systems for SUDEP prevention

### Dravet Syndrome Foundation

The **Dravet Syndrome Foundation** built its own natural history registry in collaboration with academic partners — demonstrating that even single-disease PAGs can generate research-grade longitudinal datasets when the informatics infrastructure is right.

---

## Wearables in Epilepsy: From Research to Clinic

The epilepsy community is at the forefront of applying consumer and medical wearables to real-world disease monitoring.

### The Problem: Unreliable Seizure Diaries

Self-reported seizure diaries — the clinical standard for tracking seizure frequency — are known to be inaccurate. Patients miss nocturnal seizures, forget brief focal events, or lose track during postictal states. Yet seizure count drives:
- Medication adjustments
- Surgical evaluation decisions
- Clinical trial eligibility
- FDA endpoint assessments

**Wearables offer the potential for objective, continuous seizure documentation** — transforming the data quality available to both patients and researchers.

### Approaches and Devices

| Device/Approach | Mechanism | Use Case |
|---|---|---|
| **Emfit seizure monitor** | Bed-based motion sensor | Nocturnal GTCS detection |
| **Embrace/Embrace2 (Empatica)** | EDA + accelerometry | GTCS detection, clinical alert |
| **Epiminder subscalp EEG** | Minimally invasive subdermal electrode | Long-term electrographic monitoring |
| **Wrist accelerometry** | Movement pattern analysis | GTCS and myoclonic detection |
| **Multimodal chest strap** | ECG, respiration, accelerometry | Real-world seizure detection research |

!!! note "Detection Limitations"
    Detection of **focal seizures** (without prominent motor manifestations) remains challenging with non-EEG devices. This is a genuine unmet need — focal seizures may be the most functionally impactful for many patients but are the hardest to detect objectively.

### From DIKW Perspective

- **Data:** Wrist EDA signal fluctuations, accelerometer data at 64 Hz
- **Information:** "2 probable generalized events detected overnight"
- **Knowledge:** "Seizure frequency has increased since medication change — clinical reassessment warranted"
- **Wisdom:** "This patient's panic attacks produce EDA signatures that trigger false positives — adjust threshold accordingly"

---

## The SUDEP Prevention Imperative

**Sudden Unexpected Death in Epilepsy (SUDEP)** kills approximately 1 in 1,000 adults with epilepsy annually — and more in high-risk groups like Dravet syndrome. Nocturnal seizures, particularly generalized tonic-clonic seizures during sleep, are a major risk factor.

Patient advocates in the epilepsy community have pushed hard for:

1. **Clinical disclosure** — patients and families being told about SUDEP risk
2. **Nocturnal monitoring** — wearable and bed-based alerting devices
3. **Research investment** — understanding the mechanisms of SUDEP to develop preventive strategies

The informatics implications are significant: **real-time, connected seizure detection devices** that can alert caregivers represent an Information System (with Technology, Module, and Data layers below the line) built in direct response to a Goal articulated by patient advocates.

---

## Parent-Advocate as Informatician

In the rare pediatric epilepsy world, parents frequently become de facto informatics experts — tracking seizure data in spreadsheets, coordinating care across multiple specialists, and navigating complex medication regimens that may change weekly.

<div class="patient-voice">
"I have a seizure log going back seven years. I've correlated seizure frequency with sleep, temperature, illness, medication changes. I know this disease better than most researchers do — not because I'm smarter, but because I never stop watching."
<cite>— Mother of a child with Dravet syndrome, parent researcher</cite>
</div>

This kind of lived-experience data — systematically collected by parents over years — is precisely the kind of real-world evidence that the 21st Century Cures Act is beginning to create pathways for incorporating into the regulatory process.

---

## Informatics Stack Reflection: The Rare Epilepsy Community

| Stack Level | Rare Epilepsy Example |
|---|---|
| World | PCORI funding mandate, FDA orphan drug policy, 21st Century Cures |
| Organization | Epilepsy Foundation, CURE, Dravet Foundation, individual disease PAGs |
| Role | Parents as researchers; patients as data contributors; advocates as registry co-designers |
| Goals | Understand natural history; enable trial recruitment; prevent SUDEP |
| Workflow | Wearable device wear protocols; parent-reported seizure diary apps |
| Information System | REN registry platform; Empatica cloud dashboard; clinic portal |
| Modules | PRO questionnaires; seizure detection algorithms; caregiver alert module |
| Data/Knowledge | Seizure logs → validated frequency counts → treatment decision support |
| Technology | Wearable EDA + accelerometry; subscalp EEG; FHIR-enabled registry |

---

## Key Resources

- [Rare Epilepsy Network (REN) — Epilepsy Foundation](https://www.epilepsy.com/what-is-epilepsy/rare-epilepsies/ren)
- [CURE Epilepsy](https://www.cureepilepsy.org)
- [Dravet Syndrome Foundation](https://www.dravetfoundation.org)
- [SUDEP Institute](https://www.sudep.org)
- [Empatica Embrace2](https://www.empatica.com/embrace2)
- [Epiminder (subscalp EEG)](https://www.epiminder.com)
