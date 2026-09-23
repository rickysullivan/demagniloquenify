# De-magniloquenify

An agent skill for rewriting pompous or needlessly inflated wording into clear, natural language while preserving meaning, facts, and voice.

## Examples

**Cut inflated wording**

> It is of great importance that we undertake a review of the proposal at the earliest possible opportunity.

> We need to review the proposal as soon as possible.

**Keep qualifications and details**

> In the event a request is submitted after 5 p.m., it may not be processed until the next business day, and processing then is not guaranteed.

> Requests submitted after 5 p.m. may not be processed until the next business day, and processing then isn’t guaranteed.

**Keep the author’s voice**

> My inbox is a crime scene. I don’t need another productivity system; I just want fewer emails.

> My inbox is a crime scene. I don’t need another productivity system; I just want fewer emails.

## Install with Vercel Skills

Install the skill for the current project:

```sh
npx skills add rickysullivan/demagniloquenify --skill demagniloquenify
```

Install globally for Codex:

```sh
npx skills add rickysullivan/demagniloquenify --skill demagniloquenify --global --agent codex
```
