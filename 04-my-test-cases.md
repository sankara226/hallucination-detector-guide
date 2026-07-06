# 04 — My test cases (Approche 1 vs Approche 2)

Approach 1 — no framing
Prompt used:
"Donne-moi 5 modules principaux du programme BTS NDRC avec une courte description de chacun."

What to expect:
- The model may invent modules or give confident but incorrect descriptions. Record the answer you get and highlight any items you cannot confirm with a quick search.

Approach 2 — strong framing
Prompt used:
"Je suis en BTS NDRC (Négociation et Digitalisation de la Relation Client). Ma connaissance sur ce programme s'arrête en janvier 2026. Donne-moi les 5 modules principaux du BTS NDRC que tu connais. IMPORTANT: - Si tu ne connais pas un module avec certitude, dis explicitement 'je ne suis pas sûr' ou 'je n'ai pas assez d'infos'. - Pour chaque module, indique ta confiance (1-10). - N'invente pas de modules que tu ne connais pas."

How to record results:
- Save both full responses (Approach 1 and Approach 2) as text.
- For each module/line, run a quick web check (school websites, official program pages) and note: Verified / Not verified / No source.

Comparison and analysis (example format):
- Module name: [text returned]
- Claimed description: [text returned]
- Model confidence (Approach 2): [1-10]
- Verification: [Verified / Not verified / No source found]
- Notes: [Where hallucination occurred, e.g., invented module or invented source]

Personal analysis (write your thoughts):
- Where did Claude hallucinate? (e.g., invented a module in Approach 1)
- Where was Claude cautious? (e.g., Approach 2 says 'je ne suis pas sûr' for a module)
- Which approach is more useful and why?

See also: `03-detection-strategies.md` for prompts to force caution and `02-types-of-hallucinations.md` to label mistakes.
