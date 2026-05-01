# Wearables & Consumer Health Devices

## Stack Levels Most Relevant
> **Technology (1), Data/DIKW (2), Information System (4), Workflow/Adoption (5)**

---

## What Are Wearables in a Health Context?

Wearable health devices range from consumer fitness trackers to FDA-cleared medical devices. They include:

- **Accelerometers** — movement, falls, activity level
- **Photoplethysmography (PPG)** — heart rate, blood oxygen, atrial fibrillation detection
- **Electrodermal activity (EDA)** — stress, autonomic arousal
- **Electromyography (EMG)** — muscle activity
- **Wearable EEG** — scalp, subscalp, or implanted electrodes measuring brain activity
- **Continuous glucose monitors (CGMs)** — blood glucose without fingersticks

For patient advocates, wearables represent a fundamental shift: **patients become continuous data generators**, not just episodic visitors to the clinic.

---

## The DIKW Hierarchy Applied to Wearable Data

=== "Data"
    Raw sensor signals: accelerometer readings at 100 Hz, galvanic skin conductance in microsiemens, EEG voltage fluctuations in microvolts.

    At this level, the data is nearly meaningless without context.

=== "Information"
    Aggregated, contextualized outputs: "3 tonic-clonic events detected in the last 24 hours," "heart rate variability dropped 40% on Tuesday."

    This is what most consumer wearable dashboards show.

=== "Knowledge"
    Clinically actionable patterns: "Seizure frequency has increased 2× since medication change on Day 14. Consider dose adjustment."

    This requires validated algorithms and clinical context — the *module* and *algorithm* layers of the Stack.

=== "Wisdom"
    Knowing when to trust the device: "This patient's tremor consistently triggers false-positive seizure alerts. Use accelerometry data cautiously."

    Wisdom requires human judgment layered on top of algorithmic output.

---

## Epilepsy and Seizure Detection

!!! quote "Research Context"
    Wearable sensing devices are increasing in popularity for seizure monitoring, with several large surveys documenting urgent need and high willingness to wear devices long-term among people with epilepsy.

Wearable seizure detection approaches include:

| Device Type | Signals Used | Best For |
|---|---|---|
| Wrist accelerometer + EDA | Movement, skin conductance | Generalized tonic-clonic seizures |
| Subscalp EEG (e.g., Epiminder) | Electrographic activity | Focal and subclinical seizures |
| Chest strap (ECG + resp) | Heart rate, respiration | Nocturnal monitoring |
| Scalp EEG headset | Full EEG spectrum | High-accuracy research use |

**Limitations:** Detection of focal seizures (which don't involve large motor movements) remains challenging with non-EEG wearables. Significant network and computational infrastructure is needed for continuous, secure data transmission.

### Seizure Diaries: The Problem Wearables Solve

Self-reported seizure diaries are notoriously inaccurate — patients undercount nocturnal seizures, forget brief events, or lose track during episodes. Yet seizure frequency drives treatment decisions and trial enrollment criteria.

Wearable devices offer the possibility of **objective, continuous seizure documentation** — transforming the data quality available to both clinicians and researchers.

---

## ALS and Wearable Monitoring

For people living with ALS, wearables serve different purposes:

- **Activity monitors** track functional decline over time (a research endpoint)
- **Speech analysis apps** detect early bulbar (speech/swallowing) changes
- **Eye-tracking AAC devices** enable communication as motor function is lost
- **Respiratory monitors** support ventilation management at home

!!! example "AnswerALS"
    The AnswerALS project enrolled 1,000 participants who provided biospecimens and longitudinal clinical data, generating one of the largest multimodal ALS datasets in existence. Wearable and digital biomarker data complemented traditional clinical measures to build a richer picture of disease progression.

---

## Patient-Generated Health Data (PGHD): Policy Implications

**Patient-generated health data** refers to health data created, recorded, gathered, or inferred by or from patients. The 21st Century Cures Act and subsequent ONC rules are beginning to address PGHD:

- Patients have the right to share PGHD with their care team via FHIR APIs
- Research use of PGHD requires informed consent and IRB oversight
- PAGs are increasingly building **data commons** that aggregate PGHD contributed voluntarily by patient members

### The Trust and Ownership Question

<div class="patient-voice">
"I wore this device for two years. The company got acquired and my data disappeared. Who owned that? Who should have owned it?"
<cite>— Patient advocate at a rare disease conference</cite>
</div>

Data governance is an **above-the-line** (World/Organization) question with deep below-the-line implications. Informaticians must be prepared to articulate data ownership, consent, and portability requirements to both patients and technology partners.

---

## Key Takeaways

- Wearables sit at the **Technology and Data levels** of the Stack, but their value is realized only when connected to clinical workflows and research goals above the line
- **Adoption** (Workflow level) is the critical failure point — devices must fit patients' lives, not just researchers' protocols
- For rare disease PAGs, wearables offer a path to **continuous, objective, patient-generated data** at a scale impossible to achieve through clinic visits alone
- Data governance and patient ownership must be addressed *before* deployment, not after
