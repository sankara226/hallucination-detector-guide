# 01 — What is an AI hallucination?

Definition
An AI hallucination is when a model like Claude writes something that looks fluent and believable but is partially or completely false. The model is not "lying" — it is predicting the next words based on patterns it learned.

How it works (prediction vs verification)
Large language models generate text by predicting tokens that statistically follow previous tokens. They are optimized for plausibility, not for checking facts against a database. That means a reply can be very confident-sounding while still being wrong.

A simple analogy
Think of a writer who has read thousands of travel blogs. They can write a convincing city guide that sounds correct, but they might invent a museum or a street because it "fits" the pattern of what a city description looks like. The writer is good at style and plausibility, not at real-time fact-checking.

See also: `02-types-of-hallucinations.md` for common categories.
