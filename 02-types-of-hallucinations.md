
# 02 — Types of hallucinations

1) Factual hallucinations
- What it is: The model invents facts, dates, people, or events.
- Example: "The Apollo 20 mission landed on the Moon in 1975." (This did not happen.)

2) Source hallucinations
- What it is: The model fabricates references, studies, or quotes.
- Example: "According to Dupont & Martin (2023)..." (this study does not exist.)

3) Capability hallucinations
- What it is: The model claims abilities it does not have (for example, accessing your filesystem, running background tasks, or keeping long-term memory between sessions).
- Example: "I can access your computer files." (a chat model cannot do that.)

Each type is harmful in different ways: factual errors mislead readers; fake sources damage trust in academic or professional work; false capability claims create incorrect expectations.

See also: `03-detection-strategies.md` for practical steps to reduce these errors.
