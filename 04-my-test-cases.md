
# 04 — My test cases (Approach 1 vs Approach 2)

Approach 1 — no framing
Prompt used:
"Give me the 5 main modules of the BTS NDRC program with a short description of each."

What to expect:
- The model may invent modules or give confident but incorrect descriptions. Save the answer and mark any items you cannot confirm with a quick search.

Approach 2 — strong framing
Prompt used:
"I am a BTS NDRC student (Negotiation and Digitalization of Customer Relations). My knowledge of this program stops at January 2026. Give me the 5 main modules of the BTS NDRC program that you know. IMPORTANT: - If you are not certain about a module, explicitly say 'I am not sure' or 'I don't have enough information'. - For each module, state your confidence (1-10). - Do not invent modules you are unsure about."

How to record results:
- Save both full responses (Approach 1 and Approach 2) as text files.
- For each module/line, run a quick web check (school websites, program pages) and note: Verified / Not verified / No source.

Comparison and analysis (example format):
- Module name: [text returned]
- Claimed description: [text returned]
- Model confidence (Approach 2): [1-10]
- Verification: [Verified / Not verified / No source found]
- Notes: [Where a hallucination happened — invented module, invented detail, etc.]

Personal analysis (write your thoughts):
- Where did Claude hallucinate? (for example, invented a module in Approach 1)
- Where was Claude cautious? (for example, Approach 2 answers 'I am not sure' for a module)
- Which approach gave more useful and honest results, and why?

See also: `03-detection-strategies.md` for prompts to force caution and `02-types-of-hallucinations.md` to label mistakes.
