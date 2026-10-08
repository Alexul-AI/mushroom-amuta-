# ONBOARDING — who gets what, in what order

1. **Alexander** pushes this skeleton to the repo (commands in chat). Use the GitHub noreply email for commits.
2. **Claude Code** (first, alone). Open the repo folder, start a session, send:
   "Read CLAUDE.md, STATE.md, BRIEF.md. Do Stage 0 only: propose a ≤10-line plan and the one-page proposal skeleton
   (EN; HE later). No web calls, no pushes. Update STATE.md at the end."
3. **Gemini** (after Stage 0 is approved; Alexander runs it manually). Input: `research/gemini-prompt.md` filled in
   with the query list Claude produced + public PDFs in a Drive folder. Output → `research/inbox/` (git-ignored). See roles below.
4. **Claude Code** verifies inbox items against primary sources → `research/notes/`.
5. **Codex** (only once there is a diff, i.e. end of Stage 3, and only if Alexander approves). It reads `AGENTS.md`
   automatically. Send: "Review the diff of <paths> per AGENTS.md. Findings only."
6. **Humans** (Stage 4): amuta contact and domain experts review the evidence notes and the one-pager.

## Gemini jobs (AI Studio / Drive / long context)
- Bulk triage of public papers: one table row per paper in the fixed schema (CLAUDE.md evidence standard).
- Red-team: give it a verified note; ask for contradicting or newer studies.
- HE/RU/EN terminology glossary and translation second opinion for public material.
- Deep Research runs from `research/gemini-prompt.md`.
- Rules: public documents only (no personal/legal/medical files); check the data-use terms of the product you use;
  its output is UNVERIFIED until Claude confirms each DOI/PMID.
