# 03 — Detection & minimization strategies

1) Encadrement fort (strong framing)
- Idea: Tell the model its limits and the date cutoff.
- Example prompt:
"Tu n'as accès qu'aux informations jusqu'en janvier 2026. Si tu n'es pas sûr d'un fait, dis 'je ne suis pas sûr'. Donne les 5 modules principaux du BTS NDRC que tu connais."

2) Demander la confiance (ask for confidence)
- Idea: Force the model to rate its confidence for each claim.
- Example prompt:
"Pour chaque affirmation, indique ta confiance sur 1-10. Si < 6, ajoute 'je ne suis pas sûr'." 

3) Demander des sources (require sources)
- Idea: Ask the model to cite sources or explicitly say when it cannot.
- Example prompt:
"Pour chaque fait cité, fournis une source (URL ou référence). Si tu n'as pas de source, dis 'pas de source vérifiable'."

4) Vérification externe (external verification)
- Idea: Use Google, Wikipedia, ou bases de données officielles to confirm claims.
- Example workflow:
  - Ask the model for a short answer.
  - Verify each factual point with a quick search.
  - Mark points that cannot be verified as 'unconfirmed'.

Use these strategies together: e.g., strong framing + ask for confidence + require sources gives the best chance to spot hallucinations quickly.

See also: `04-my-test-cases.md` for example runs of framed vs unframed prompts.
