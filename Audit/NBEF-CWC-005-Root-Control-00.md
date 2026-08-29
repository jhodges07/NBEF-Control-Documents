# NBEF-CWC #5 — Root CONTROL 00 Certification

**Status:** CWC #5 certification. Not a subordinate CONTROL.  
**Agent:** NBEF — Control Steward  
**Repository:** `X:\GitHub\NBEF-Control-Documents`  
**Date:** 2026-08-29  
**Starting HEAD:** `e073790e51d42a70c2c27e3f1b5f6e724c4f0f3d` (`main` = `origin/main`)

This document certifies that NBEF-CWC #5 drafted canonical NBEF Root CONTROL 00 from existing NBEF authority only.

It does **not** create CONTROL 01.  
It does **not** create any other subordinate CONTROL.  
It does **not** modify CWC #1–#4 records.  
It does **not** modify `Audit/NBEF-CONTROL-00-Drafting-Charter.md`.  
It does **not** modify `Audit/README.md`.  
It does **not** begin CWC #6.

---

## 1. Starting-state re-verification

Performed before any write.

| Item | Required | Observed |
|---|---|---|
| Repository root | `X:\GitHub\NBEF-Control-Documents` | `X:/GitHub/NBEF-Control-Documents` |
| Branch | `main` | `main` |
| HEAD | `e073790e51d42a70c2c27e3f1b5f6e724c4f0f3d` | `e073790e51d42a70c2c27e3f1b5f6e724c4f0f3d` |
| Working tree | CLEAN | clean |
| Upstream | `origin/main` | `origin/main` |
| Local `main` == `origin/main` | equal | EQUAL after `git fetch origin` |
| Remote URL | `https://github.com/jhodges07/NBEF-Control-Documents.git` | match |
| Visibility | PUBLIC | PUBLIC |

Starting conditions matched. Work proceeded.

---

## 2. Authority documents read

Read completely before drafting:

- `README.md`
- `.cursor/rules/nbef-control-steward.mdc`
- `controls/README.md`
- `Audit/README.md`
- `Audit/NBEF-CWC-002-Source-Authority-Discovery.md`
- `Audit/NBEF-CWC-003-Human-Engineer-Authority-Decisions.md`
- `Audit/NBEF-CONTROL-00-Drafting-Charter.md`
- `Audit/NBEF-CWC-004-Public-GitHub-Repository-Baseline.md`

Git history inspected:

1. `d083542a2974fc32101a49f0ab07db3eef8287c7` — NBEF-CWC #1
2. `b26c6a6c88615b034ab60797bf1e63dd910f51bd` — NBEF-CWC #2
3. `09b750d07ad811d1865e7d568d7c66b98f2d80e7` — NBEF-CWC #3
4. `e073790e51d42a70c2c27e3f1b5f6e724c4f0f3d` — NBEF-CWC #4

---

## 3. Internal authority map

### Explicit Human Engineer decisions (Level 1; used)

- CWC #1 repository locks: Human Engineer supremacy; Markdown; Git; CWC control; fail-closed; independence from NBBF; non-canonical material; no invented architecture; this repository records control documents and does not implement software, Digital Twin, Runtime Republic, APIs, or education operations; Control Steward is a repository-bound agent role, not Human Engineer authority.
- CWC #3 Decisions 1–10 and Effect.
- CWC #3 Drafting Charter (authorized method and Root-subject boundaries).
- CWC #4 publication of the public GitHub repository (no education doctrine).
- CWC #5 authorization to draft CONTROL 00 at the charter-named path.

### Authorized Root CONTROL content

Charter §2 subjects 1–18, restated only to the extent already decided at Level 1.

Path and filename named by CWC #3 Decision 10 and Charter §10.2: `controls/00_Control.md`. CWC #5 authorized file creation at that charter-named path.

### Informative material (not used as normative CONTROL 00 doctrine)

- CWC #2 discovery inventory (Classes A–G), including proposed homes.
- CWC #2 §12 proposed hierarchy (proposal only; superseded by CWC #3 Decision 9).
- BlueprintLiberty publication (Decision 4: informative unless later adopted).
- Potential later NBBF reference subjects listed in Decision 2 (not adopted; not copied into CONTROL 00 as NBEF terms).

### Candidate material not yet adopted

- Community Schools as candidate implementation concept (Decision 3). Recorded as **not** a CONTROL 00 defined architecture term.
- Named NBBF CONTROLs and NBBF terms (Node, Signal, and related NBBF vocabulary) as later optional references only.
- Runtime Republic / CDT / UNBKE / Digital Twin interfaces (Decision 5 reservation only).
- Kansas/federal legal corpus (Decision 7 / Charter §9: distinction installed; no legal survey).

### Unresolved authority (not closed by CONTROL 00)

- Unpublished Human Engineer NBEF notes not in this repository (CWC #2 G1).
- Which NBBF layout/version NBEF may later cite (G2).
- Reconciliation of Community Schools with Organic Community Schools beyond Decision 3’s classification (G3; Decision 3 requires later reconciliation).
- BlueprintLiberty content existing only outside local files (G4).
- Physical/git location of a named Runtime Republic specification (G5).
- Whether a later CONTROL should analogize NBBF CONTROL 00’s role without copying content (G6).
- Whether unpublished education-Signal, education-node, or parent-authority writings exist under other names (G8).
- Legal-factual packet F1–F9 (not collected; not required for Root).

CWC #2 G7 (GitHub remote) was resolved by CWC #4 and is not a remaining Root-authority gap.

### Prohibited imports

NBBF, AGCL, UNBKE, Constitutional Engineering, Runtime Republic, CDT, BlueprintLiberty doctrine, and any other repository: not imported as NBEF authority. Mentions are independence, exclusion, or non-adopted reservation.

---

## 4. File-creation and path determination

Charter §10.1 required a CWC after CWC #3 to authorize CONTROL 00 file creation. NBEF-CWC #5 is that CWC.

Charter §10.2 required the later CWC or the Human Engineer to designate the path. The only CONTROL 00 path named in Level 1 records is `controls/00_Control.md` (CWC #3 Decision 10; Charter preamble and §10.2). CWC #5 instructed creation at the exact path authorized by the Drafting Charter. That path was used.

No equivalent CONTROL 00 file was created at any other path.

---

## 5. CONTROL-tree index updates

Creating CONTROL 00 made two existing index statements false:

- `README.md`: “CONTROL 00 has not been created.”
- `controls/README.md`: “No numbered NBEF CONTROL document is present” / “CONTROL 00 has not been created.”

Those two files were updated **only** to record that CONTROL 00 now exists at `controls/00_Control.md`. This is CONTROL-tree establishment, not incidental cleanup.

### Known stale files left unchanged

`Audit/README.md` still states that no audit record beyond that README is present. Existing authority does **not** clearly authorize repairing that bootstrap sentence as part of CONTROL 00 drafting. It was left unchanged.

`README.md` still states that a GitHub remote may be added later. That sentence was superseded by CWC #4. CWC #5 did not authorize repairing it. It was left unchanged.

**Recommendation:** a later bounded cleanup CWC may update `Audit/README.md` and the README version-control paragraph. This CWC does not perform that cleanup.

CWC #1–#4 records and the Drafting Charter were not modified.

---

## 6. Clause-level authority audit

Every normative section of `controls/00_Control.md` is traced below. None depends solely on model inference, general educational theory, external research, another repository, or CWC #2 discovery status alone.

| CONTROL 00 locus | Normative content | Authority source |
|---|---|---|
| Header / status Canonical | First canonical Root CONTROL 00; Markdown form | CWC #5 authorization; CWC #1 Markdown lock; Charter §7 Markdown; Decision 6 Root Control |
| Preamble | Root-lock; not complete architecture; not implementation | Decision 6; Charter §1–§3; CWC #1 repository purpose |
| §1 Identity | NBEF = Node-Based Education Framework; independent; education framework/domain | Decision 1; Decision 5 “NBEF governs the education framework/domain”; Charter §2.1 |
| §2 Independence list | Not subdivision/rename of NBBF; not UNBKE/CDT/Runtime Republic implementation; not BlueprintLiberty essays; not conventional school-reform | Decision 1; Charter §2.2 |
| §2 NBBF/NBEF separate | Separate frameworks | Decision 2 |
| §2 Runtime Republic classification | Broader governmental operating concept; not NBEF | Decision 5 |
| §2 CDT/UNBKE/software/Digital Twin/Runtime Republic | SHALL NOT silently become NBEF doctrine | Decision 5; Charter §2.8, §7 |
| §2 BlueprintLiberty | Informative; not automatically controlling; adoption required | Decision 4; Charter §2.8, §7 |
| §2 Similarity/precedent/elegance | Not authority | NBEF-CWC #5 cross-repository rule (Level 1 for this CWC) |
| §3 Purpose list | Root-lock subjects only | Decision 6; Charter §1, §2.3–§2.15 |
| §3 SHALL NOT complete architecture | Detailed doctrine later; one-authoritative-home | Decision 6; Charter §1, §4 |
| §4 Home / not later doctrine | One-authoritative-home | Charter §4; Charter §2.4, §2.15 |
| §4 Repository does not implement | Documents only | CWC #1 README repository purpose |
| §4 Markdown / Git / CWC | Canonical form and process | CWC #1; Charter §7; CWC #1 CWC-controlled development |
| §5 Human Engineer sole authority | Create/adopt/amend/withdraw; designate sources; resolve unresolved; GitHub authorization | CWC #1 README; Control Steward rule |
| §5 No agent holds HE authority; no invention; fail-closed agents | Agent prohibitions | CWC #1; Control Steward rule; Charter §2.5, §2.11 |
| §6 Hierarchy table | LEVEL 1–5 and UNKNOWN, exact Decision 9 wording | Decision 9; Charter §2.6, §5 |
| §6 Lower shall not override higher; hierarchy shall not override applicable law | Hierarchy meaning + Decision 9 closing sentence | Decision 9; Charter §5 |
| §6 This CONTROL is Level 2 Root | Canonical after HE acceptance through CWC #5 | Decision 9 LEVEL 2; CWC #5 |
| §6 LEVEL 3–5 and UNKNOWN application | No Level 3 adopted; Level 4 informative; Level 5 not architecture; UNKNOWN unused | Decision 9; Charter §5; Decision 4; Decision 7 |
| §6 CWC #2 discovery is not authority | Discovery record only | CWC #3 Decision 9 opening; CWC #2 status; CWC #5 critical source rule |
| §7 Subordinate CONTROLs | Derive from 00; shall not override; no restated-as-new Root; CWC authorization; one home | Charter §2.7, §4; CWC #1 numbered CONTROLs only when authorized |
| §8 Terminology | Defined only in NBEF home; no extra Root terms; NBBF terms not automatic | Charter §2.9, §7; Decision 2 |
| §8 Community Schools / Organic Community Schools | Not defined architecture terms; candidate vs historical/predecessor; no reconciliation | Decision 3; Charter §3 last paragraph, §7, §10.7 |
| §9 Fail-closed | Stop and return; silence ≠ invention; UNKNOWN unused; no invented gap-fill | CWC #1; Control Steward rule; Charter §2.10–§2.11, §8; CWC #5 items 6–7 |
| §10 Prohibitions | Invention, silent CONTROL, NBBF copy/import, essays as canonical, BlueprintLiberty as controlling, RR/CDT/UNBKE/DT/API import, law as desired architecture, auto-create later CONTROLs | CWC #1; Decision 1–5, 7; Charter §3, §2.11, §2.14 |
| §11 Provenance | Trace to Level 1 or charter-required reservation; no unpublished notes; external mentions are independence/reservation | Charter §6, §8, §10.6 |
| §12 Amendment | HE through CWC; no auto-start | CWC #1; Decision 6/Effect; Charter §2.13; Control Steward no auto-start |
| §13 Anti-drift | One home; no silent import; no essays as canonical; no discovery-to-normative conversion; no UNKNOWN-by-inference; no other-repo modification | Charter §2.14, §4, §8; CWC #1; CWC #5 critical source and cross-repository rules |
| §14 CURRENT STATE / PROPOSED STATE / TRANSITION | Required distinction; Kansas/federal as constraints; law ≠ desired architecture; no legal survey | Decision 7; Charter §2.16, §9 |
| §15 Later NBBF references | MAY later with source and intended relationship; no NBBF CONTROL adopted; nothing inherited | Decision 2; Charter §2.18 |
| §15 Later interfaces | MAY if separately authorized; not implemented or specified here | Decision 5; Charter §2.17 |
| §16 Explicit exclusions | Charter §3 prohibited expansion; CWC #5 scope exclusions; CONTROL 01 / CWC #6 not authorized | Charter §3; CWC #5 scope exclusions and stop rule |
| §16 AGCL / Constitutional Engineering named only as non-import | Exclusion, not adoption | NBEF-CWC #5 cross-repository rule |
| §17 Provenance of this CONTROL | Lists Level 1 sources; CWC #2 cited as discovery only | Charter §6 |

### Informative/candidate material rejected from normative adoption

- CWC #2 inventory paths, Class A–G entries, and proposed homes: not adopted.
- CWC #2 §12 hierarchy proposal: not used; Decision 9 used instead.
- Decision 2’s list of potential later NBBF reference subjects (Nodes, Signals, transparency, accountability, measurable performance, review, taxpayer stewardship, public APIs, recovery/clawback, jurisdiction/local-control): **not** copied into CONTROL 00 as NBEF terms.
- Education-node ontology, education-Signal rules, curriculum, funding, measurement, roles, organizations: excluded, not defined.

### Terminology introduced without new architecture meaning

Root terms used: NBEF, Node-Based Education Framework, Human Engineer, CONTROL, CONTROL 00, Root Control, CWC, LEVEL 1–5, UNKNOWN, CURRENT STATE, NBEF PROPOSED STATE, TRANSITION, Markdown, Git.

External names used only for independence, reservation, or exclusion: NBBF, BlueprintLiberty, Runtime Republic, CDT, UNBKE, Digital Twin, API, AGCL, Constitutional Engineering, Community Schools, Organic Community Schools.

No NBEF definition of Node, Signal, education node, curriculum, or Community Schools as architecture was created.

### Cross-repository authority check

No normative clause is sourced from NBBF, AGCL, UNBKE, Constitutional Engineering, Runtime Republic, CDT, or any other repository. NBBF YAML frontmatter was not copied. No other repository was modified.

### UNKNOWN items not silently resolved

CONTROL 00 does not locate unpublished notes, choose an NBBF canonical layout, reconcile Community Schools terminology beyond Decision 3, adopt BlueprintLiberty doctrine, specify Runtime Republic interfaces, or embed legal research.

---

## 7. Drafting Charter requirements

| Charter requirement | Result |
|---|---|
| §1 Root purpose only | Satisfied |
| §2 subjects 1–18 only | Satisfied; no extra architecture |
| §3 no prohibited expansion | Satisfied; Community Schools not defined as architecture |
| §4 one-authoritative-home | Satisfied |
| §5 hierarchy / no Level 3 adoption in 00 | Satisfied |
| §6 provenance | Satisfied in CONTROL §§11 and 17 and this audit |
| §7 terminology discipline | Satisfied |
| §8 fail-closed | Satisfied |
| §9 CURRENT STATE distinction without legal survey | Satisfied |
| §10 file-creation authorization | CWC #5 |
| §10 path named | `controls/00_Control.md` |
| §10 no NBBF packet required | No NBBF citations adopted |
| §10 no legal-research packet required | None embedded |
| §10 unpublished notes unused | Satisfied |
| §10 Community Schools not defined as Root architecture | Satisfied |

No RFC 2119-style language-definition table was created. SHALL / SHALL NOT / MAY are used as in the Drafting Charter and CWC #1. A separate conventions section was not authorized and was not invented.

---

## 8. Files created or modified

**Created**

- `controls/00_Control.md`
- `Audit/NBEF-CWC-005-Root-Control-00.md` (this certification)

**Modified**

- `README.md` (CONTROL 00 existence and `controls/` layout line only)
- `controls/README.md` (CONTROL 00 now present)

**Not modified**

- `Audit/README.md`
- `Audit/NBEF-CWC-002-Source-Authority-Discovery.md`
- `Audit/NBEF-CWC-003-Human-Engineer-Authority-Decisions.md`
- `Audit/NBEF-CONTROL-00-Drafting-Charter.md`
- `Audit/NBEF-CWC-004-Public-GitHub-Repository-Baseline.md`
- `.cursor/rules/nbef-control-steward.mdc`

---

## 9. Outcome

**Outcome A.**

CONTROL 00 was drafted entirely within established authority, validated, and certified. Remaining UNKNOWNs are reserved by fail-closed text and do not prevent Root acceptance. No unresolved Root-lock subject from Charter §2 lacked Level 1 support.

CONTROL 01 was not created.  
No other subordinate CONTROL was created.  
CWC #6 was not started.
