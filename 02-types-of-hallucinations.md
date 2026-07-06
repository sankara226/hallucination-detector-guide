# 02 — Types of hallucinations

1) Hallucinations factuelles (factual)
- What it is: The model invents facts, dates, people, or events.
- Example: "Le projet Apollo 20 a aluni en 1975." (This never happened.)

2) Hallucinations de sources (sources)
- What it is: The model fabricates references, papers, or quotes.
- Example: "Selon l'étude de Dupont & Martin (2023)..." (the study does not exist.)

3) Hallucinations de capacités (capabilities)
- What it is: The model claims abilities it does not have (access to files, background running tasks, permanent memory).
- Example: "Je peux accéder à ton système de fichiers." (a chat model cannot do that.)

Each type is dangerous in different contexts: factual errors mislead readers, false sources break trust in research, and false capability claims cause incorrect expectations.

See also: `03-detection-strategies.md` for ways to reduce these.
