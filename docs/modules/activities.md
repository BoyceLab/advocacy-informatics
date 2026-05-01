# Learning Activities & Assessments

## How to Use These Activities

These activities are designed to help you apply the Informatics Stack framework to real patient advocacy and engagement contexts. They range from structured reflection exercises to full group projects. Each activity identifies the Stack levels most relevant and the learning objectives it addresses.

---

## Activity 1: Stack Mapping Exercise

**Time:** 45–60 minutes | **Format:** Individual or pairs

**Objective:** Practice identifying which levels of the Informatics Stack are present — and which are missing — in a published description of a patient-facing health IT system.

**Instructions:**

1. Choose one of the following resources:
    - The [Rare Epilepsy Network (REN)](https://www.epilepsy.com/what-is-epilepsy/rare-epilepsies/ren) description on the Epilepsy Foundation website
    - The [AnswerALS project description](https://www.answerals.org/about/)
    - A HIMSS Davies Award report of your choice (available at [himss.org](https://www.himss.org))

2. For each level of the Stack, identify:
    - What evidence in the report addresses this level?
    - What is notably **absent** from the description?
    - What questions would you ask the project team to fill in the gaps?

3. Write a 1-page reflection addressing:
    - What did the Stack help you notice that you might have missed?
    - Where was the above-the-line / below-the-line translation happening in this project?

---

## Activity 2: CMSS Scorecard Assessment

**Time:** 60–90 minutes | **Format:** Small group (3–4 students)

**Objective:** Apply the CMSS/PLRC Patient-Led Research Scorecard to a real or simulated patient-researcher collaboration.

**Instructions:**

Choose **one** of the following:

=== "Option A: Real Collaboration"
    Select a published study that involved patient engagement. PCORI-funded studies are good choices because they are required to report on patient engagement.

    Read the Methods section and any patient engagement appendices. Score the collaboration on all four scorecard domains (Governance, Research Integration, Patient Burden, Research Organization Readiness).

    Be prepared to defend your scores with specific textual evidence.

=== "Option B: Simulated Collaboration"
    Your instructor will provide a scenario describing a collaboration between a rare disease PAG and a university research team. The scenario contains both positive and problematic elements.

    Score the collaboration, identify the lowest-scoring domain, and propose three specific changes the research team could make to move from their current score to "Great Collaboration" on that domain.

**Deliverable:** 2-page scoring memo with domain scores, justifications, and recommendations.

---

## Activity 3: REMS Workflow Redesign

**Time:** 90 minutes | **Format:** Group project

**Objective:** Apply below-the-line informatics knowledge (FHIR, CDS Hooks) to an above-the-line patient advocacy problem (medication access delay).

**Background:** Read the [REMS & HL7 CodeX module](codex-rems.md) and review the [CodeX REMS FHIR IG overview](https://confluence.hl7.org/display/COD/Risk+Evaluation+and+Mitigation+Strategies+(REMS)+Integration).

**Scenario:** A PAG representing patients who take a REMS-required medication has documented that the average time from prescription to first dose is **21 days**, largely due to REMS enrollment delays. They have asked your informatics team to propose a FHIR-based solution.

**Deliverable:** A swimlane diagram (use the required method from Lehmann's course instructions) showing:
- Current state workflow (with REMS delay points annotated)
- Future state workflow with FHIR/CDS Hooks integration
- A brief narrative explaining which Stack levels your solution addresses

---

## Activity 4: Patient Data Governance Policy Brief

**Time:** 2–3 hours | **Format:** Individual

**Objective:** Connect World-level regulatory context (Cures Act, PCORI, HIPAA) to organizational-level governance decisions for a patient registry.

**Scenario:** The Fictitious Ataxia Alliance wants to build a national patient registry. They ask you to write a governance policy brief addressing:

1. **Data ownership** — Who owns patient-contributed data? What rights does the patient retain?
2. **Consent model** — What consent framework will you use? Broad consent? Dynamic consent? What are the trade-offs?
3. **Secondary use** — Under what conditions may de-identified data be shared with pharmaceutical companies?
4. **Information blocking** — What does the 21st Century Cures Act require of any EHR partners who may provide data passthrough?
5. **PCORI requirements** — If the registry seeks PCORI funding, what patient engagement standards must the governance structure reflect?

**Deliverable:** 3–4 page policy brief organized around these five questions.

---

## Activity 5: PAG Readiness Assessment

**Time:** Group project over 1–2 weeks | **Format:** Group (4–6 students)

**Objective:** Conduct a full Informatics Stack readiness assessment for a real PAG interested in building a patient registry or research program.

This mirrors Lehmann's **Use Case 1: Readiness Assessment** applied to a patient advocacy context.

**Instructions:**

1. Select a rare disease PAG (instructor can approve others):
    - An epilepsy PAG (e.g., CURE Epilepsy, Dravet Syndrome Foundation)
    - An ALS PAG (e.g., ALS TDI, I AM ALS)
    - A PAG of your choice relevant to your own interests

2. Research the organization's current informatics infrastructure, stated research goals, and patient community characteristics using:
    - Their public website
    - Published papers they've funded or co-authored
    - Any available registry or database descriptions

3. Produce a **Stack Assessment Report** (structured wiki, following Lehmann's Final Project format) addressing:
    - All nine Stack levels
    - Above-the-line / below-the-line consistency
    - Key gaps and risks
    - CMSS Scorecard assessment of any stated research collaborations

4. **Reflection:** What aspects of the PAG's work would you have missed without the Stack framework?

**Deliverable:** Group wiki or structured document + 15-minute presentation.

---

## Reflection Prompts (Weekly Journals)

These prompts can be used for weekly written reflections throughout the course:

**Week 1:** What does "patient-centered" mean in informatics? How is it different from "user-centered"?

**Week 2:** Identify a health IT system you interact with as a patient (or that a family member uses). Map it to the Stack. What level is most frustrating? Why?

**Week 3:** Read the NEALS PEACe committee description: *"Nothing about us should be done without us."* What would need to be true at each Stack level to actually realize this principle?

**Week 4:** The 21st Century Cures Act prohibits "information blocking." Based on what you know about health systems, why do you think information blocking happens? What above-the-line and below-the-line factors explain it?

**Week 5:** A patient advocate tells you: "I don't care about FHIR. I just want my data." How would you respond? What does this tell you about the gap between above- and below-the-line perspectives?

**Week 6:** Review the CMSS Scorecard and identify one domain where you think most research organizations would score lowest. Why? What structural changes would be required to improve it?
