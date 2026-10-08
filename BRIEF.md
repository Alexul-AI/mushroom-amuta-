# BRIEF.md — initial project brief (v0.1, 2026-10-08)

Read on demand. Keep STATE.md as the live status; this file changes rarely.

## 1. Idea
Volunteer technical contribution to an Israeli amuta in the medicinal-mushroom space (default: the Israeli
wild mushroom association). Focus on an honest, evidence-graded knowledge layer plus a small useful tool.
Separate cautious research track: PTSD and MS (literature + Israeli trials only; no advice).

Assumptions to confirm with Alexander: (a) we support an EXISTING amuta, not found a new one;
(b) volunteer, low budget, low time; (c) repo is PUBLIC by Alexander's decision (no personal data in it, ever); outbound contact/promotion needs his approval.

## 2. Boundary: functional mushrooms vs psilocybin
| | Functional / medicinal mushrooms | Psilocybin mushrooms |
|---|---|---|
| Examples | reishi, lion's mane, turkey tail, cordyceps, chaga, shiitake, maitake | Psilocybe spp. (psilocybin/psilocin) |
| Status in Israel | food/supplement-type context; health claims are regulated → verify with MoH | psilocybin/psilocin controlled (Dangerous Drugs Ordinance); medical use only inside MoH-approved trials |
| Evidence | mostly in vitro/animal/small human; MS & PTSD evidence thin | active Phase 2 research incl. PTSD; not an approved treatment in Israel |
| Our role | evidence mapping, education, tools | literature/registry summary ONLY. No cultivation, sourcing, dosing, retreats, promotion |
| Legal grey zone | wild-harvest rules (nature reserves) → verify | whole-mushroom possession reportedly not explicitly listed vs extracts listed — secondary source, contested → lawyer, do not assert |

## 3. Verified snapshot (secondary sources — re-verify against primary before use)
- Psilocybin in Israel: trials-only (aggregator, "verified Aug 2026"). Israeli trials exist, e.g. TiPAP for PTSD at Tel Aviv Sourasky
  (clinicaltrials.gov NCT07737054), Apex Labs SUMMIT-90 sites at TAU/Be'er Yaakov (MoH-approved, 2025), OCD trial in Be'er Sheva (NCT04882839).
- MDMA for PTSD: MoH compassionate-use approval in 2019 is historical; do NOT present as current open access.
  Current activity runs through trials.
- Ketamine/esketamine: the only legally prescribed psychedelic-class option (esketamine registered 2020, MoH circular 5/2024).
- Medical cannabis: MoH is proposing tighter rules incl. caution for PTSD (committee recommendations) — status of implementation unverified.
- MS + medicinal mushrooms: reviews call Hericium erinaceus promising preclinically with few clinical trials; no solid MS clinical evidence found.
TODO for Claude: confirm each item at gov.il / MoH / ClinicalTrials.gov / Knesset; date-stamp in `docs/legal-map.md`.

## 4. Stages (each ends at a gate; Alexander approves before the next)
**Stage 0 — Alignment (before the association congress, 24 Dec 2026, Savyon).** One-page proposal in Hebrew+EN:
what we offer, what we will NOT do (psilocybin, medical advice), who reviews. No outreach without OK.
Exit: Alexander picks one MVP; one named contact in the amuta. Cost: low.

**Stage 1 — Legal & scope map.** `docs/legal-map.md` (functional-mushroom claims, wild harvest, psilocybin line,
amuta compliance, privacy). Primary sources only. Flag questions for a lawyer. Exit: Alexander reads the 1-page summary. Cost: med.

**Stage 2 — Evidence base.** Fixed note schema (see CLAUDE.md). Start narrow: 5 species × {general, PTSD, MS}.
Gemini collects candidates → Claude verifies → notes. Exit: ≥30 verified notes + gap list. Cost: med (use Gemini for bulk).

**Stage 3 — MVP (pick one, decide at Stage 0):**
- A. *Evidence Atlas*: static bilingual site (Markdown+JSON → static pages), each claim with E-level and source.
- B. *Israeli Trial Tracker*: small script pulling ClinicalTrials.gov (Israel; PTSD/MS; mushroom-derived & psychedelic trials) into a table; weekly refresh.
- C. *Amuta toolkit*: member/event/data tooling the association actually asks for.
Default recommendation: B → A (cheapest, most defensible, reusable). Exit: working private demo. Cost: med.

**Stage 4 — Expert review.** Codex review (only if approved) + human domain experts via the amuta. Exit: written feedback applied.

**Stage 5 — Promotion decision.** Repo is already public; this gate is about presenting/promoting under the amuta's name (site, newsletter, talks). Claims/legal check first.

## 5. Open questions for Alexander
1. Which amuta exactly and who is the contact? (default: wild mushroom association)
2. Hours per week available? (drives MVP size)
3. Languages for first deliverable: HE / RU / EN?
4. Preferred MVP: A, B, or C?

## 6. Risks
Medical/legal overclaiming · drifting into psychedelic promotion · hallucinated citations · token burn ·
over-committing on a volunteer basis · privacy leaks. Mitigations are in CLAUDE.md.
