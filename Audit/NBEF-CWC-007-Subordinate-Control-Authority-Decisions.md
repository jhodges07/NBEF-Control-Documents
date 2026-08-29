# NBEF-CWC #7 — Subordinate CONTROL Authority Decisions

**Status:** Human Engineer authority record. Not a CONTROL. Not CONTROL 01.  
**Agent:** NBEF — Control Steward  
**Repository:** `X:\GitHub\NBEF-Control-Documents`  
**Date:** 2026-08-29  
**Starting HEAD:** `01c12ae1d75684006232a394f0f7670f13f9360b` (`main` = `origin/main`)

This document records Human Engineer answers given in NBEF-CWC #7.

It does **not** draft CONTROL 01.  
It does **not** create any numbered CONTROL.  
It does **not** define Node, Signal, Community Schools, rights, governance, measurement, or interfaces.  
It does **not** modify CONTROL 00.  
It does **not** modify CWC #1–#6 records.  
It does **not** begin CWC #8.

These decisions are **Level 1** authority for subsequent NBEF CWCs. They remain subject to later Human Engineer amendment through a controlled CWC.

No answer below is expanded beyond the explicit Human Engineer choice.

---

## 1. Certified starting state

| Item | Required | Observed |
|---|---|---|
| Repository root | `X:\GitHub\NBEF-Control-Documents` | `X:/GitHub/NBEF-Control-Documents` |
| Branch | `main` | `main` |
| HEAD | `01c12ae1d75684006232a394f0f7670f13f9360b` | `01c12ae1d75684006232a394f0f7670f13f9360b` |
| Working tree | CLEAN | clean |
| Upstream | `origin/main` | `origin/main` |
| Local `main` == `origin/main` | equal | EQUAL after `git fetch origin` |

Starting conditions matched. Work proceeded.

Subordinate CONTROLs present at start: **none**. `controls/` contained only `00_Control.md` and `README.md`.

Git history inspected through CWC #6.

---

## 2. Authority sources examined

Read before the decision packet:

- `controls/00_Control.md`
- `Audit/NBEF-CWC-006-Subordinate-Control-Architecture-Discovery.md`
- `Audit/NBEF-CWC-005-Root-Control-00.md`
- `Audit/NBEF-CWC-003-Human-Engineer-Authority-Decisions.md`
- `Audit/NBEF-CONTROL-00-Drafting-Charter.md`
- `Audit/NBEF-CWC-002-Source-Authority-Discovery.md`
- `README.md`
- `controls/README.md`
- `.cursor/rules/nbef-control-steward.mdc`

CWC #6 verdict D (insufficient authority to designate CONTROL 01) was the starting condition. This CWC did not close that gap by agent inference.

---

## 3. Human Engineer decisions

Each decision is recorded as: question; existing authority; unresolved before this CWC; choices offered; Human Engineer answer; status; consequence; prerequisite CWC implication.

### Decision 1 — CONTROL 01 status

**Question:** Designate CONTROL 01 now, keep it undesignated until prerequisite work, or require additional architecture discovery because current candidates should not become CONTROL 01?

**Existing authority:** CONTROL 00 §§5, 7: numbered CONTROLs exist only when the Human Engineer authorizes a named CONTROL through a CWC. CWC #6 verdict D: existing authority is insufficient to designate CONTROL 01. Candidate status is not designation.

**Unresolved before this CWC:** CONTROL 01 subject, path, and whether any current candidate is CONTROL 01.

**Choices offered:**

- A. Designate a specific subject for CONTROL 01 now (Human Engineer must name it).
- B. Keep CONTROL 01 undesignated until prerequisite discovery or adoption work is completed.
- C. Currently identified candidate domains should not become CONTROL 01; additional architecture discovery is required.

**Human Engineer answer:** **B**

**Status:** DECIDED

**Consequence:** CONTROL 01 is **not designated**. Candidate Community Schools, Node, Signal, parent authority, governance, measurement, or interface intent recorded elsewhere in this CWC does **not** make any of those CONTROL 01. Drafting CONTROL 01 is **not** authorized by this CWC.

**Prerequisite CWC:** Required before CONTROL 01 may be designated. This CWC does not name that CWC’s subject. Decisions 11-B and 12-B establish that the prerequisite is **not** an NBBF named-reference CWC before all subordinate CONTROLs, and **not** a Level 5 CURRENT STATE CWC before CONTROL 01. The Human Engineer must authorize the next CWC and name its bounded subject. CWC #8 is not started.

---

### Decision 2 — Community Schools

**Question:** Classify Community Schools.

**Existing authority:** CWC #3 Decision 3 and CONTROL 00 §8: candidate NBEF implementation concept; not a Root architecture term; no canonical definition; not designated CONTROL 01; reserved to later CONTROLs.

**Unresolved before this CWC:** architecture vs implementation vs informative vs deferred vs out of scope; whether a dedicated CONTROL home is intended.

**Choices offered:**

- A. An NBEF architecture concept requiring later definition.
- B. An NBEF implementation concept requiring later definition.
- C. Informative terminology only.
- D. Deferred / UNKNOWN.
- E. Outside NBEF scope.

**Human Engineer answer:** **B** — An NBEF implementation concept requiring later definition.

**Follow-up (if A or B):** Is a dedicated CONTROL home intended?

**Human Engineer answer:** **YES**

**Status:** DECIDED

**Consequence:** Community Schools remains an NBEF **implementation** concept, not Root architecture. It **requires later definition**. A **dedicated CONTROL home is intended**. That CONTROL is **not** created here and is **not** CONTROL 01 (Decision 1-B). No Community Schools definition is adopted.

**Prerequisite CWC:** A later Human Engineer–authorized CWC must define Community Schools before any Community Schools CONTROL may be drafted. That drafting CWC must be separately authorized. Not started.

---

### Decision 3 — Organic Community Schools

**Question:** Classify Organic Community Schools relative to NBEF / Community Schools.

**Existing authority:** CWC #3 Decision 3 and CONTROL 00 §8: historical/predecessor terminology requiring later reconciliation; not a Root architecture term; CONTROL 00 does not reconcile the terms. CWC #6 G3 remained UNKNOWN.

**Unresolved before this CWC:** retired vs predecessor name vs distinct concept vs informative only vs still unresolved.

**Choices offered:**

- A. Retired terminology.
- B. A predecessor name for Community Schools.
- C. A distinct concept.
- D. Informative historical terminology only.
- E. Still unresolved.

**Human Engineer answer:** **B** — A predecessor name for Community Schools.

**Status:** DECIDED

**Consequence:** Organic Community Schools is a **predecessor name for Community Schools**. This is the Human Engineer’s explicit relationship decision. It does **not** define Community Schools. It does **not** create a CONTROL titled Organic Community Schools. It does **not** make Organic Community Schools a current architecture term. Synonymy of operating rules is **not** inferred beyond “predecessor name.”

**Prerequisite CWC:** None required solely to record this relationship. Later Community Schools definition work SHALL treat Organic Community Schools as predecessor name, not as a second live architecture term, unless a later CWC amends this decision.

---

### Decision 4 — Education-node terminology

**Question:** Does NBEF itself require a canonical concept called “Node” or “Education Node”?

**Existing authority:** CONTROL 00 does not define an NBEF education-node ontology and excludes it from Root (CONTROL 00 §16). NBBF Node doctrine is external and SHALL NOT be silently imported (CONTROL 00 §§2, 8, 10). CWC #6: no CONTROL home yet; drafting would invent or import NBBF.

**Unresolved before this CWC:** whether NBEF has such a term at all.

**Choices offered:**

- A. YES — NBEF requires its own independently defined Node concept.
- B. YES — but definition requires prerequisite source/discovery work.
- C. NO — NBEF will use different terminology.
- D. UNDECIDED.

**Human Engineer answer:** **A**

**Follow-up (if YES):** Is the concept expected to become a foundational subordinate CONTROL subject?

**Human Engineer answer:** **YES**

**Status:** DECIDED (requirement and intended CONTROL class). Node **definition** is **not** decided in this CWC.

**Consequence:** NBEF **requires its own independently defined Node concept**. NBBF Node meaning is **not** adopted. The concept is **expected to become a foundational subordinate CONTROL subject**. That CONTROL is **not** created here. It is **not** designated CONTROL 01 (Decision 1-B). No Node ontology is written here.

**Prerequisite CWC:** A later Human Engineer–authorized CWC must define the NBEF Node concept (independently of NBBF) before a Node CONTROL may be drafted. Drafting that CONTROL requires separate authorization. Not started.

---

### Decision 5 — Education-Signal terminology

**Question:** Does NBEF require a canonical Signal concept?

**Existing authority:** CONTROL 00 does not define education-Signal doctrine and excludes education-Signal operating rules from Root (CONTROL 00 §16). NBBF Signal is external. CWC #6: no CONTROL home yet.

**Unresolved before this CWC:** whether NBEF has a Signal term at all.

**Choices offered:**

- A. YES — independently defined NBEF Signal.
- B. YES — but prerequisite source/adoption work is required.
- C. NO.
- D. UNDECIDED.

**Human Engineer answer:** **A**

**Status:** DECIDED (requirement). Signal **definition** is **not** decided in this CWC.

**Consequence:** NBEF **requires an independently defined NBEF Signal**. NBBF Signal meaning is **not** adopted. No Signal CONTROL is created here. Not CONTROL 01.

**Prerequisite CWC:** A later Human Engineer–authorized CWC must define NBEF Signal before a Signal CONTROL may be drafted. Separate authorization required to draft. Not started.

---

### Decision 6 — Rights / authority domain

**Question:** Is NBEF intended eventually to contain a canonical rights/authority domain?

**Existing authority:** CONTROL 00 does not establish parent-rights, student-rights, teacher-rights, or education-authority doctrine. Those subjects are out of Root scope (CONTROL 00 §16). CWC #6: no CONTROL home yet; G8 unpublished notes UNKNOWN.

**Unresolved before this CWC:** whether such a domain is intended.

**Choices offered:**

- A. YES — parent authority/rights is foundational.
- B. YES — broader parent/student/teacher authority requires later definition.
- C. Rights doctrine belongs outside NBEF.
- D. Deferred / UNKNOWN.

**Human Engineer answer:** **A**

**Status:** DECIDED (intent that parent authority/rights is foundational). **No substantive rights** are defined.

**Consequence:** NBEF is intended eventually to contain a canonical **parent authority/rights** domain, classified as **foundational**. No parent-rights CONTROL is created here. Not CONTROL 01. Student-rights and teacher-rights were **not** chosen in this answer and are **not** silently included.

**Prerequisite CWC:** A later Human Engineer–authorized CWC must define parent authority/rights before any such CONTROL may be drafted. Separate authorization required to draft. Not started.

---

### Decision 7 — Governance / local control

**Question:** Is NBEF intended eventually to define governance or local-control architecture?

**Existing authority:** CONTROL 00 does not establish NBEF school-governance or local-control doctrine and excludes school-governance from Root (CONTROL 00 §16). NBBF jurisdiction/local-control is external. CWC #6: no NBEF local-control CONTROL home.

**Unresolved before this CWC:** whether NBEF will define governance/local-control.

**Choices offered:**

- A. YES.
- B. NO.
- C. Only through Community Schools.
- D. Requires prerequisite discovery.
- E. Deferred / UNKNOWN.

**Human Engineer answer:** **A**

**Status:** DECIDED (intent). **No governance architecture** is defined.

**Consequence:** NBEF is intended eventually to define **governance or local-control architecture**. NBBF jurisdiction/local-control doctrine is **not** imported. No governance CONTROL is created here. Not CONTROL 01. “Only through Community Schools” was **not** chosen; relationship between governance and Community Schools is **not** specified beyond this intent.

**Prerequisite CWC:** A later Human Engineer–authorized CWC must define the NBEF governance/local-control home before such a CONTROL may be drafted. Separate authorization required. Not started.

---

### Decision 8 — Curriculum / pedagogy

**Question:** Are curriculum and pedagogy intended to be canonical CONTROL subjects, implementation-layer matters, outside NBEF, or deferred?

**Existing authority:** CONTROL 00 §16 excludes curriculum and pedagogy from Root. CWC #6: no CONTROL home.

**Unresolved before this CWC:** whether they become NBEF CONTROL subjects.

**Choices offered:**

- A. Canonical NBEF CONTROL subjects.
- B. Implementation-layer matters governed by higher NBEF principles but not centrally defined.
- C. Outside NBEF scope.
- D. Deferred / UNKNOWN.

**Human Engineer answer:** **B**

**Status:** DECIDED

**Consequence:** Curriculum and pedagogy are **implementation-layer matters** governed by higher NBEF principles and are **not centrally defined** as NBEF CONTROL subjects. No curriculum CONTROL is created. No curriculum content is authorized.

**Prerequisite CWC:** None for a curriculum CONTROL. Later implementation definition of Community Schools or other implementation concepts SHALL NOT treat this Decision as a license to write curriculum doctrine into a CONTROL unless a later CWC amends this decision.

---

### Decision 9 — Measurement / performance / accountability

**Question:** Does NBEF eventually require a canonical domain governing measurement/performance/accountability?

**Existing authority:** CONTROL 00 does not define NBEF measurement, performance, testing, or accountability doctrine. Measurement systems and performance formulas are excluded from Root (CONTROL 00 §16). NBBF measurable-performance and review rules are external. CWC #6: no CONTROL home.

**Unresolved before this CWC:** whether NBEF has such a domain, and whether it is one or several.

**Choices offered:**

- A. YES — one integrated domain.
- B. YES — separate domains.
- C. NO.
- D. Requires prerequisite discovery.
- E. Deferred / UNKNOWN.

**Human Engineer answer:** **A**

**Status:** DECIDED (intent: one integrated domain). **No measurement system** is defined.

**Consequence:** NBEF is intended eventually to have **one integrated** canonical domain governing measurement/performance/accountability. NBBF measurable-performance and review rules are **not** imported. No such CONTROL is created here. Not CONTROL 01.

**Prerequisite CWC:** A later Human Engineer–authorized CWC must define that integrated domain before such a CONTROL may be drafted. Separate authorization required. Not started.

---

### Decision 10 — Funding

**Question:** Is education funding intended to be a canonical NBEF domain, an external governmental/NBBF relationship, outside NBEF, or deferred?

**Existing authority:** CONTROL 00 §16 excludes funding doctrine from Root. CWC #6: no NBEF funding CONTROL home. NBBF cost/value and recovery are external.

**Unresolved before this CWC:** whether funding is an NBEF domain.

**Choices offered:**

- A. A canonical NBEF domain.
- B. An external governmental/NBBF relationship rather than NBEF education doctrine.
- C. Outside NBEF scope.
- D. Deferred / UNKNOWN.

**Human Engineer answer:** **B**

**Status:** DECIDED

**Consequence:** Education funding is **not** NBEF education doctrine. It is an **external governmental/NBBF relationship**. This does **not** adopt any NBBF funding CONTROL (Decision 11-B: NBBF references only when a particular future CONTROL requires one). No NBEF funding CONTROL is created. No funding system is defined.

**Prerequisite CWC:** None for an NBEF funding CONTROL. Any later named NBBF funding citation requires a CONTROL-specific reference decision under Decision 11-B.

---

### Decision 11 — NBBF references

**Question:** When, if at all, should NBEF consider named NBBF references?

**Existing authority:** CONTROL 00 §15 permits later named NBBF references and adopts none. CWC #3 Decision 2: MAY later; nothing inherited; source and intended NBEF relationship required. CWC #6: NBBF-REF candidate or a CWC; G2 unresolved.

**Unresolved before this CWC:** prerequisite adoption CWC vs per-CONTROL vs none vs deferred.

**Choices offered:**

- A. A prerequisite NBBF named-reference discovery/adoption CWC before substantive subordinate NBEF CONTROLs.
- B. NBBF references considered only when a particular future CONTROL requires one.
- C. No NBBF normative references in NBEF.
- D. Deferred / UNKNOWN.

**Human Engineer answer:** **B**

**Status:** DECIDED

**Consequence:** NBBF references are **not** a prerequisite to all subordinate NBEF CONTROLs. They are considered **only when a particular future CONTROL requires one**. CONTROL 00 still requires any such later reference to identify its authoritative NBBF source and intended NBEF relationship. No NBBF CONTROL is adopted here. NBBF numbering still does not determine NBEF numbering (Decision 14).

**Prerequisite CWC:** None before CONTROL 01 designation. A named-reference CWC occurs only if and when a later CONTROL’s authorizing CWC requires it.

---

### Decision 12 — CURRENT STATE legal / factual packet

**Question:** When should Level 5 legal/factual work (F1–F9) occur?

**Existing authority:** CONTROL 00 §14 requires later work to distinguish CURRENT STATE / NBEF PROPOSED STATE / TRANSITION; forbids embedding a legal survey in Root; legal-factual collection is a later CWC using Level 5 sources designated by the Human Engineer. CWC #2 F1–F9 not collected. CWC #6 candidate LAW home type unresolved.

**Unresolved before this CWC:** before CONTROL 01 vs per-CONTROL vs later annex architecture vs deferred.

**Choices offered:**

- A. A Level 5 source-designation / CURRENT STATE evidence CWC before CONTROL 01.
- B. Legal/factual work performed only when a particular future CONTROL needs it.
- C. A dedicated evidence annex architecture later.
- D. Deferred / UNKNOWN.

**Human Engineer answer:** **B**

**Status:** DECIDED

**Consequence:** No legal survey is conducted in this CWC. Level 5 work is **not** required before CONTROL 01 may later be designated. Legal/factual work is performed **only when a particular future CONTROL needs it**. CONTROL 00 §14 distinction remains Root: any such later CONTROL work SHALL still distinguish CURRENT STATE / NBEF PROPOSED STATE / TRANSITION. Existing law still SHALL NOT automatically define NBEF architecture.

**Prerequisite CWC:** None before CONTROL 01. A Level 5 source-designation CWC occurs only if and when a later CONTROL’s authorizing CWC requires it.

---

### Decision 13 — External system interfaces

**Question:** How should Runtime Republic / CDT / UNBKE / Digital Twin interfaces be treated?

**Existing authority:** CONTROL 00 §15: later CONTROLs MAY define explicit interfaces if separately authorized; Root does not implement or specify them. Decision 5 (CWC #3). CWC #6 candidate IFACE; G5 UNKNOWN.

**Unresolved before this CWC:** reserve until core architecture vs later dedicated interface CONTROL vs external repos only vs deferred.

**Choices offered:**

- A. Reserved until core NBEF architecture exists.
- B. Planned as a later dedicated interface CONTROL.
- C. Defined only in external implementation repositories.
- D. Deferred / UNKNOWN.

**Human Engineer answer:** **B**

**Status:** DECIDED (planning class). **No interface is defined.**

**Consequence:** External system interfaces are **planned as a later dedicated interface CONTROL**. That CONTROL is **not** created here. Not CONTROL 01. Runtime Republic, CDT, UNBKE, and Digital Twin are **not** imported as NBEF doctrine.

**Prerequisite CWC:** A later Human Engineer–authorized CWC may create the interface CONTROL only when separately authorized. Core NBEF subjects (Node, Community Schools definition, etc.) remain undefined; this Decision does not specify that they must exist first. Not started.

---

### Decision 14 — CONTROL numbering

**Question:** Confirm that NBEF CONTROL numbers SHALL represent NBEF’s own authoritative CONTROL structure and SHALL NOT be inherited from NBBF or another framework merely because similar concepts exist there.

**Existing authority:** CWC #6: NBBF CONTROL numbers SHALL NOT be used as NBEF order. CONTROL 00 §2: similarity, useful precedent, and architectural elegance are not authority.

**Unresolved before this CWC:** explicit Human Engineer confirmation.

**Choices offered:** YES or NO (if NO, state the intended numbering rule).

**Human Engineer answer:** **YES**

**Status:** DECIDED

**Consequence:** NBEF CONTROL numbers SHALL represent **NBEF’s own** authoritative CONTROL structure. They SHALL **NOT** be inherited from NBBF or another framework merely because similar concepts exist there. No numbering rule other than this was stated.

**Prerequisite CWC:** None.

---

## 4. Summary table

| Decision | Answer | Status |
|---|---|---|
| 1 CONTROL 01 status | B — keep undesignated until prerequisite discovery or adoption work is completed | DECIDED |
| 2 Community Schools | B — implementation concept requiring later definition | DECIDED |
| 2 follow-up dedicated CONTROL home | YES | DECIDED |
| 3 Organic Community Schools | B — predecessor name for Community Schools | DECIDED |
| 4 Node / Education Node | A — NBEF requires its own independently defined Node concept | DECIDED (requirement only) |
| 4 follow-up foundational CONTROL subject | YES | DECIDED |
| 5 Signal | A — independently defined NBEF Signal | DECIDED (requirement only) |
| 6 Rights/authority | A — parent authority/rights is foundational | DECIDED (intent only) |
| 7 Governance/local control | A — YES | DECIDED (intent only) |
| 8 Curriculum/pedagogy | B — implementation-layer, not centrally defined | DECIDED |
| 9 Measurement/performance/accountability | A — one integrated domain | DECIDED (intent only) |
| 10 Funding | B — external governmental/NBBF relationship, not NBEF education doctrine | DECIDED |
| 11 NBBF references | B — only when a particular future CONTROL requires one | DECIDED |
| 12 CURRENT STATE evidence | B — only when a particular future CONTROL needs it | DECIDED |
| 13 External interfaces | B — planned as a later dedicated interface CONTROL | DECIDED (planning only) |
| 14 CONTROL numbering | YES — NBEF’s own numbers; not inherited from NBBF | DECIDED |

No decision was recorded as UNKNOWN in this CWC. Decision 1-B defers **CONTROL 01 designation**, which is not the same as leaving Decisions 2–14 unanswered.

CWC #2 G1, G2, G4, G5, G8 and F1–F9 **content** remain uncollected. G3 (Organic Community Schools relationship) is **superseded in part** by Decision 3-B as to relationship class only.

---

## 5. Consequence for subordinate CONTROL architecture

Level 1 intent now exists that NBEF will, in later separately authorized work, have:

- a defined Community Schools **implementation** concept with a dedicated CONTROL home;
- Organic Community Schools treated as that concept’s **predecessor name**;
- an independently defined NBEF **Node** concept expected as a **foundational** subordinate CONTROL subject;
- an independently defined NBEF **Signal**;
- a foundational **parent authority/rights** domain;
- **governance or local-control** architecture;
- **one integrated** measurement/performance/accountability domain;
- a later dedicated **external-interface** CONTROL;
- curriculum/pedagogy **not** as central CONTROL subjects;
- funding **not** as NBEF education doctrine.

None of those CONTROLs is created. None is CONTROL 01.

NBBF numbering is not NBEF numbering. NBBF and legal packets are not global prerequisites.

---

## 6. CONTROL 01 designation result

**CONTROL 01 is not designated.**

- Exact subject: **none**
- Intended authoritative home: **none**
- Drafting authorized now: **NO**
- Separate Human Engineer authorization still required to designate and to draft CONTROL 01

---

## 7. Required prerequisite next CWC

Because Decision 1 is **B**, CONTROL 01 remains undesignated until prerequisite discovery or adoption work is completed.

This CWC does **not** designate CONTROL 01 and does **not** start CWC #8.

**Exact next CWC:** not auto-started. The Human Engineer must authorize the next CWC and **name its bounded subject**.

That next CWC SHALL NOT draft CONTROL 01 unless a later CWC first designates CONTROL 01 (Decision 1-B forbids treating any current candidate as CONTROL 01).

Eligible later CWC classes implied by Decisions 2–13, none of which is started here:

1. Community Schools implementation **definition** CWC (Decision 2-B; home intended; definition missing).
2. Independent NBEF **Node** definition/charter CWC (Decision 4-A; foundational CONTROL subject intended; definition missing).
3. Independent NBEF **Signal** definition CWC (Decision 5-A).
4. Parent authority/rights **definition** CWC (Decision 6-A; no substantive rights here).
5. Governance/local-control **definition** CWC (Decision 7-A).
6. Integrated measurement/performance/accountability **definition** CWC (Decision 9-A).
7. External-interface CONTROL **only when separately authorized** (Decision 13-B).

NBBF named-reference CWC and Level 5 legal CWC are **not** required before CONTROL 01 designation (Decisions 11-B, 12-B). They occur only when a particular future CONTROL needs them.

The Human Engineer, not this agent, chooses which of the above is next.

---

## 8. Clause-level authority audit

Every new Level 1 statement in §3 corresponds to an explicit Human Engineer answer recorded in this CWC. None is inferred from essays, NBBF, BlueprintLiberty, or CWC #2 discovery status.

| Level 1 statement | Source |
|---|---|
| CONTROL 01 undesignated until prerequisite discovery or adoption work | Decision 1-B |
| Community Schools is an NBEF implementation concept requiring later definition | Decision 2-B |
| A dedicated Community Schools CONTROL home is intended | Decision 2 follow-up YES |
| Organic Community Schools is a predecessor name for Community Schools | Decision 3-B |
| NBEF requires its own independently defined Node concept | Decision 4-A |
| That Node concept is expected as a foundational subordinate CONTROL subject | Decision 4 follow-up YES |
| NBEF requires an independently defined NBEF Signal | Decision 5-A |
| Parent authority/rights is foundational in NBEF | Decision 6-A |
| NBEF is intended eventually to define governance or local-control architecture | Decision 7-A |
| Curriculum and pedagogy are implementation-layer, not centrally defined | Decision 8-B |
| One integrated measurement/performance/accountability domain is intended | Decision 9-A |
| Funding is an external governmental/NBBF relationship, not NBEF education doctrine | Decision 10-B |
| NBBF references only when a particular future CONTROL requires one | Decision 11-B |
| Legal/factual work only when a particular future CONTROL needs it | Decision 12-B |
| External interfaces planned as a later dedicated interface CONTROL | Decision 13-B |
| NBEF CONTROL numbers are NBEF’s own; not inherited from NBBF or another framework | Decision 14-YES |

No Node, Signal, Community Schools, rights, governance, measurement, funding system, or interface **definition** is claimed as Level 1.

---

## 9. Files

**Created:** `Audit/NBEF-CWC-007-Subordinate-Control-Authority-Decisions.md` (this record)

**Modified:** none

**Not created:** `controls/01_Control.md` or any other numbered CONTROL

**Not modified:** `controls/00_Control.md`; CWC #1–#6 records; Drafting Charter; README files; `Audit/README.md`

---

## 10. What this CWC did not do

- Did not draft CONTROL 01.
- Did not designate a CONTROL 01 subject.
- Did not define Node, Signal, Community Schools, parent rights, governance, measurement, or interfaces.
- Did not import NBBF, AGCL, UNBKE, Constitutional Engineering, Runtime Republic, or BlueprintLiberty doctrine.
- Did not conduct a legal survey.
- Did not begin CWC #8.
