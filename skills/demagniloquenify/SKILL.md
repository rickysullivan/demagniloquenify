---
name: demagniloquenify
description: Rewrite text to remove pompous, grandiloquent, or needlessly inflated wording while preserving its meaning, facts, tone, and useful detail. Use when asked to “de-magniloquenify” text or make it less pompous and more direct.
---

# De-magniloquenify

Rewrite the supplied text so it says the same thing in clear, natural language.

## Method

1. Identify inflated diction, ceremonial phrasing, needless abstraction, repetition, and sentences that take too long to reach their point.
2. Replace those parts with familiar, precise words and direct sentence structure.
3. Preserve the author's meaning, facts, intent, and appropriate voice. Keep humor, warmth, emphasis, and technical terms when they are doing useful work.
4. Keep all meaningful qualifications and distinctions. Do not simplify away uncertainty, legal or technical nuance, or important context.
5. Preserve the format and approximate level of detail unless the user asks for a different format or length.

Return the revised text by itself by default. Add a brief note only when a phrase is ambiguous enough that changing it could alter the meaning; in that case, retain the ambiguity or flag it rather than guessing.

## Guardrails

- Do not turn every sentence into terse, flat prose. Clear does not mean stripped of personality.
- Do not add claims, explanations, examples, or stylistic flourishes that were not in the source.
- Do not merely shorten text if its main problem is pompous wording; make the wording more natural while keeping useful content.
- If no text is supplied, ask the user to provide it.

## Invocation

“De-magniloquenify this: `$ARGUMENTS`”
