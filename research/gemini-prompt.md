# Gemini research prompt (run manually; paste output into research/inbox/ as UNVERIFIED)

Use Deep Research / long-context mode. Fill the <> fields. Never include personal or health data about any person.

---
You are an independent literature researcher. Topic: <species or question>, in the context of <general | PTSD | MS>.

Rules:
- Primary sources only (PubMed, journals, ClinicalTrials.gov, gov.il/MoH). No blogs, shops, or forums as evidence.
- Every item needs a DOI or PMID or registry ID. If you cannot give one, do not list the item.
- Do NOT invent or "complete" references. If unsure, say "uncertain".
- Separate: in vitro / animal / human. For human: design, n, population, preparation (fruiting body / mycelium on grain / extract), outcome, limitations, funding.
- Do not give medical advice, dosing, or recommendations. Do not cover psilocybin cultivation, sourcing, or use; for psychedelic trials list only registry/publication facts.
- Include Israeli context (trials, MoH statements, Israeli researchers) when relevant.

Output: a table with columns
ID | year | species | preparation | study type | n | population | outcome | limitations | evidence level (E0–E4) | link
Then: 5 lines "what is NOT known", and 3 lines "claims commonly made online that this evidence does not support".
Max 1,200 words.
---
