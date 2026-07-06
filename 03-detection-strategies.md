
# 03 — Detection & minimization strategies

1) Strong framing
- Idea: Tell the model its limits and the data cutoff date.
- Example prompt:
"You only have access to information up to January 2026. If you are not sure about a fact, say 'I am not sure'. Give me the 5 main modules of the BTS NDRC program that you know."

2) Ask for confidence
- Idea: Force the model to state its confidence for each claim.
- Example prompt:
"For each claim, give a confidence score from 1 to 10. If confidence < 6, add 'I am not sure'."

3) Require sources
- Idea: Ask the model to provide sources or explicitly say when it cannot.
- Example prompt:
"For each fact you list, provide a source (URL or reference). If you don't have a verifiable source, say 'no verifiable source'."

4) External verification
- Idea: Use Google, Wikipedia, or official databases to confirm claims.
- Example workflow:
  - Ask the model for a short answer.
  - Verify each factual point with a quick web search.
  - Mark points that cannot be verified as 'unconfirmed'.

Combine strategies for best results: for example, use strong framing + ask for confidence + require sources to increase transparency and spot hallucinations faster.

See also: `04-my-test-cases.md` for example runs (framed vs unframed prompts).
