
# 01 — What is an AI hallucination?

Definition
An AI hallucination happens when a model (for example, Claude) generates text that sounds fluent and believable but is partly or completely false. The model does not intend to deceive — it predicts likely words based on patterns it learned during training.

How it works (prediction vs verification)
Large language models are token predictors: at each step they choose the next token that is statistically likely given the prompt and context. They are tuned for plausibility, not for fact-checking against an external database. As a result, answers can sound confident while still being incorrect.

Analogy
Imagine an author who has read thousands of mystery novels. They become excellent at writing plausible crime scenes, but that does not mean they know actual police procedures. They write what "sounds right" based on patterns, not on verified facts.

See also: `02-types-of-hallucinations.md` for the common categories of errors.
