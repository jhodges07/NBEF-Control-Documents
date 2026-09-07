# NBEF-CWC #10 — Node Lifecycle and Operational-State Authority

**Status:** CWC authority/discovery record only. Not a CONTROL. Not CONTROL 01. Not a Node CONTROL.  
**Agent:** NBEF — Control Steward  
**Repository:** `X:\GitHub\NBEF-Control-Documents`  
**Date:** 2026-08-30  
**Starting HEAD:** `73830f9ff401cd56f2bab3384cccaec51c0b53a4` (`main` = `origin/main`)

This document records Human Engineer answers that close remaining Node lifecycle and operational-state gaps identified by CWC #9.

It does **not** draft a Node CONTROL.  
It does **not** designate CONTROL 01.  
It does **not** create any numbered CONTROL.  
It does **not** modify CONTROL 00.  
It does **not** reopen settled CWC #9 recognition or composition decisions.  
It does **not** define Signal, parent authority/rights, governance, measurement, Community Schools, curriculum, funding, or external interfaces.  
It does **not** import NBBF, AGCL, UNBKE, Runtime Republic, CDT, or other-framework lifecycle architecture.  
It does **not** begin CWC #11.

A READY finding authorizes the Human Engineer to authorize a later drafting CWC. It does **not** itself authorize drafting.

---

## 1. Certified starting state

| Item | Required | Observed |
|---|---|---|
| Repository | `X:\GitHub\NBEF-Control-Documents` | `X:/GitHub/NBEF-Control-Documents` |
| Branch | `main` | `main` |
| Local HEAD | `73830f9ff401cd56f2bab3384cccaec51c0b53a4` | match |
| `origin/main` | same SHA | match after `git fetch origin` |
| Remote | NBEF repository | `https://github.com/jhodges07/NBEF-Control-Documents.git` |
| Working tree | CLEAN | CLEAN |
| CWC #9 artifact | present | `Audit/NBEF-CWC-009-Node-Recognition-Composition-Lifecycle-Authority.md` |
| CWC #10 already started | must not | no CWC #10 file at start |
| CONTROL 00 | canonical; unmodified | `controls/00_Control.md` |
| CONTROL 01 / Node CONTROL | do not exist | confirmed |

Starting conditions matched. Work proceeded.

---

## 2. Governing NBEF authority examined

- `controls/00_Control.md`
- `Audit/NBEF-CWC-007-Subordinate-Control-Authority-Decisions.md`
- `Audit/NBEF-CWC-008-Independent-Node-Definition-Authority-Discovery.md`
- `Audit/NBEF-CWC-009-Node-Recognition-Composition-Lifecycle-Authority.md`
- `.cursor/rules/nbef-control-steward.mdc`
- `README.md` and `controls/README.md` where applicable

External frameworks were not treated as normative authority and were not inspected for lifecycle mechanics.

---

## 3. Existing CWC #9 authority preserved

Not re-questioned. Not changed.

**Recognition:** R1 A, R2 A, R3 A, R4 A, R5 A, R6 A.

**Composition:** C1 A, C2 A, C3 A, C4 A, C5 A, C6 A.

**Lifecycle (CWC #9):**

- L1 — Recognition, modification, suspension, restoration, termination, replacement
- L2 B — Activation is distinct from recognition and remains to be defined later (definition supplied in this CWC, not by reopening L2)
- L3 A — Modification does not by itself create a new Node; identity continues unless recognition is withdrawn or superseded
- L4 A — Termination ends recognition (not altered)
- L5 B — Replacement, succession, merger, and division are later Node CONTROL subjects; mechanics remain undefined

CWC #9 L1/L5 tension on succession, merger, and division is addressed in this CWC by explicit SU1, MG1, and DV1 answers. Those answers do **not** add those events to the L1 selected list. They confirm them as **later Node CONTROL subjects** with mechanics **not defined in this CWC**.

---

## 4. Human Engineer questions presented

A1 meaning of activation; A2 recognition prerequisite; A3 whether every recognized Node must become active; A4 who may activate; A5 kind of activation act.

OS1 minimum operational distinctions.

S1 meaning/effect of suspension; S2 actor and record; S3 expiry.

RR1 restoration vs reactivation; RR2 prerequisites and identity; RR3 operational destination after that act (follow-up required by RR1-A + OS1-A).

T1 actor/record/effective point; T2 historical persistence; T3 post-termination identity.

RP1 replacement versus modification.

SU1 succession; MG1 merger; DV1 division.

H1 history/lineage minimum.

CL1 composition/lifecycle interaction.

Settled CWC #7, #8, and #9 recognition/composition questions were not re-asked.

---

## 5. Human Engineer answers received

Recorded without expansion.

| ID | Answer | Status |
|---|---|---|
| A1 | **A.** Activation is an operational state of an already recognized Node; it is not a new Node identity | DECIDED |
| A2 | **A.** Recognition is a prerequisite; a Node cannot be active unless it is recognized | DECIDED |
| A3 | **A.** NO — a recognized Node need not ever become active | DECIDED |
| A4 | **A.** Same recognizer class as R1 | DECIDED |
| A5 | **A.** Declarative: an explicit NBEF act, recorded like recognition (R3-A / R6-A) | DECIDED |
| OS1 | **A.** YES — minimum distinctions: recognized-not-active; active; suspended; terminated (terminated means recognition has ended per L4-A) | DECIDED |
| S1 | **A.** Suspension does NOT end recognition; a suspended Node is not active while suspended | DECIDED |
| S2 | **A.** Same recognizer class as R1; SHALL be recorded in this repository through the CWC/CONTROL process | DECIDED |
| S3 | **A.** Suspension does not expire by itself; restoration/reactivation is a separate act | DECIDED |
| RR1 | **A.** Restoration and reactivation are the same lifecycle act | DECIDED |
| RR2 | **A.** Requires current recognition that has not been terminated; prior identity is preserved; no new recognition act | DECIDED |
| RR3 | **A.** After restoration/reactivation, the Node is active | DECIDED |
| T1 | **A.** Same recognizer class as R1; SHALL be recorded in this repository; effective when that authorized act is recorded | DECIDED |
| T2 | **A.** Historical record of the terminated Node SHALL persist; historical existence is not current recognition | DECIDED |
| T3 | **A.** A terminated Node cannot be restored; any later Node requires a new recognition act (not restoration) | DECIDED |
| RP1 | **A.** Replacement recognizes a different Node; it is not modification of the same Node (L3-A). The prior Node’s recognition ends by termination or as part of the authorized replacement act | DECIDED (disjunction preserved; not reduced) |
| SU1 | **A.** YES — succession is a later Node CONTROL subject; lineage mechanics are not defined in this CWC | DECIDED |
| MG1 | **A.** YES — merger is a later Node CONTROL subject; mechanics are not defined in this CWC | DECIDED |
| DV1 | **A.** YES — division is a later Node CONTROL subject; mechanics are not defined in this CWC | DECIDED |
| H1 | **A.** Authorized lifecycle acts SHALL be recorded; the historical record is not current recognition | DECIDED |
| CL1 | **A.** Parent termination does NOT by itself terminate subordinates. Parent replacement does NOT by itself terminate subordinates. Moving a Node between parents is composition change only (C6-A). | DECIDED |

No conflict with CONTROL 00, CWC #7–#9 recognition/composition, L3-A, or L4-A was identified. Amendment authority was not required.

---

## 6. Newly established Level 1 authority (CWC #10)

Distinct from CWC #9. Not a CONTROL.

### Activation

1. Activation is an **operational state** of an already recognized Node. It is **not** a new Node identity.
2. Recognition is a **prerequisite**. A Node cannot be active unless it is recognized.
3. A recognized Node **need not ever** become active.
4. Who may activate: the **same recognizer class as R1**.
5. Activation is a **declarative** explicit NBEF act, recorded like recognition.

### Operational distinctions

6. NBEF requires these minimum operational distinctions: **recognized-not-active**; **active**; **suspended**; **terminated**. Terminated means recognition has ended (L4-A). This is not a software state machine.

### Suspension

7. Suspension does **not** end recognition. A suspended Node is **not active** while suspended.
8. Who may suspend, and record: **same recognizer class as R1**; SHALL be recorded in this repository through the CWC/CONTROL process.
9. Suspension does **not** expire by itself. Restoration/reactivation is a separate act.

### Restoration / reactivation

10. Restoration and reactivation are the **same** lifecycle act.
11. That act requires current recognition that has **not** been terminated; prior identity is preserved; **no** new recognition act.
12. After that act, the Node is **active**.

### Termination mechanics (L4-A unchanged)

13. Who may terminate, record, and effective point: **same recognizer class as R1**; SHALL be recorded in this repository; effective when that authorized act is recorded.
14. Historical record of the terminated Node SHALL persist. Historical existence is **not** current recognition.
15. A terminated Node **cannot** be restored. Any later Node requires a **new recognition act**, not restoration.

### Replacement (L3-A preserved)

16. Replacement recognizes a **different** Node. It is **not** modification of the same Node. The prior Node’s recognition ends by termination or as part of the authorized replacement act.

### Succession, merger, division

17. Succession is a **later Node CONTROL subject**. Lineage mechanics are **not** defined in this CWC.
18. Merger is a **later Node CONTROL subject**. Mechanics are **not** defined in this CWC.
19. Division is a **later Node CONTROL subject**. Mechanics are **not** defined in this CWC.

These three are **not** added to CWC #9 L1. They resolve L5-B as later subjects without defining mechanics here.

### History / lineage

20. Authorized lifecycle acts SHALL be recorded. The historical record is **not** current recognition.

### Composition / lifecycle interaction (C6-A preserved)

21. Parent termination does **not** by itself terminate subordinates.
22. Parent replacement does **not** by itself terminate subordinates.
23. Moving a Node between parents is **composition change only**.

No Node is recognized, activated, suspended, restored, terminated, or replaced by this CWC.

---

## 7. Remaining UNKNOWNs

- Mechanics of **succession**, **merger**, and **division** (later Node CONTROL subjects; not defined here).
- Which of the two RP1 endings applies in a given replacement (termination vs as part of the replacement act) is not further specified; the selected disjunction stands.
- Later CONTROL that may authorize a recognizer other than Human Engineer-through-CWC (CWC #9 R1-A “until”).
- Signal participation; measurement participation; Community Schools definition; parent-rights substance; governance architecture; funding; interfaces (unchanged later domains).

---

## 8. Later-CONTROL boundaries preserved

| Domain | Boundary preserved |
|---|---|
| Parent authority/rights | Constrains Nodes; not Node identity; not defined here |
| Governance/local control | Later CONTROL; Node is not a governance system |
| Signal | Deferred; composition does not inherit Signal |
| Measurement/performance/accountability | Deferred; composition does not inherit accountability |
| Funding | Not Node identity |
| External interfaces | Later dedicated interface CONTROL |
| Community Schools | Implementation using Nodes; not defined here |

CWC #10 identifies no new doctrine for those domains.

---

## 9. Readiness assessment

| Surface | Result |
|---|---|
| Node recognition authority | **READY** (CWC #9; unchanged) |
| Node composition authority | **READY** (CWC #9; unchanged) |
| Node lifecycle authority | **READY** for a later drafting CWC to state the CWC #9–#10 lifecycle locks and to reserve succession/merger/division |
| Node operational-state authority | **READY** |
| Node CONTROL drafting readiness | **READY** (does **not** authorize drafting) |
| CONTROL 01 designation | **UNDESIGNATED** |

**READY** means sufficient authority exists for the Human Engineer to authorize a later Node CONTROL drafting CWC. This CWC does **not** start that CWC. Foundational Node status does **not** make the Node CONTROL CONTROL 01.

---

## 10. Files

**Created:** `Audit/NBEF-CWC-010-Node-Lifecycle-Operational-State-Authority.md` (this record)

**Modified:** none

**Not created:** `controls/01_Control.md` or any other numbered CONTROL

**Not modified:** `controls/00_Control.md`; CWC #1–#9 records; Drafting Charter; README files; `Audit/README.md`; Control Steward rule; any other repository
