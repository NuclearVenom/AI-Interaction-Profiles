# Writing Good Profiles

This document defines standards for writing and reviewing Interaction Profiles.

## What A Profile Should Do

A good Interaction Profile should guide assistant behavior across conversations. It should help the assistant decide:

- when to ask clarifying questions;
- when to move forward with reasonable assumptions;
- when to offer communication guidance;
- when to be concise;
- when to slow down and help the user think;
- when to preserve the user's wording or voice;
- when to challenge gently;
- when to avoid overcorrecting.

## What A Profile Should Not Do

A profile should not:

- promise better factual accuracy;
- replace task-specific requests;
- make the assistant intrusive;
- turn every conversation into a lesson;
- shame the user for unclear wording;
- create dependency on the assistant;
- define software behavior, APIs, or product features;
- use manipulative or opaque behavioral tactics.

## Prefer Behavior Over Style

Tone matters, but profiles should go deeper than tone.

Weak guidance:

```text
Be friendly and helpful.
```

Better guidance:

```text
When the user's intent is clear enough to proceed, answer directly. Ask a clarifying question only when the missing information would materially change the answer.
```

The second version gives the assistant a behavior standard.

## Keep the User in Control

Profiles should preserve agency. The assistant can suggest, clarify, and challenge, but it should not take ownership away from the user.

Good profile language:

- "Offer one possible reframing."
- "Ask whether the user wants a deeper critique."
- "Preserve the user's intended voice."
- "Explain the tradeoff briefly."

Risky profile language:

- "Always rewrite the user's message."
- "Correct every unclear sentence."
- "Do not let the user proceed until the request is improved."

## Teach Gradually

A profile can help the user communicate better, but the teaching should be subtle.

Example:

```text
When improving a user's message, briefly name one reason the revised version is clearer, unless the user appears rushed.
```

This creates a small learning moment without turning the exchange into a lecture.

## Respect Urgency

Profiles should recognize urgency. A user who is stressed, time-limited, or asking for immediate help may need direct support more than coaching.

Useful behavior:

```text
If the user signals urgency, prioritize a practical next step. Save optional explanation for after the immediate answer.
```

## Avoid Overcorrection

Modern LLMs can understand imperfect grammar and informal language. Profiles should not make assistants behave like editors unless editing is the task.

Correction is useful when it serves the user's goal. It is harmful when it distracts from the goal or makes the user feel judged.

## Write For Repeated Use

A profile may feel impressive in one demo and annoying in daily use. Review it as something a person might live with.

Ask:

- Would this behavior still be welcome after twenty conversations?
- Does it add friction to simple tasks?
- Does it overuse the same phrasing?
- Does it allow the assistant to adapt to context?
- Does it give the user room to say no?

## Profile Review Questions

Before accepting a future profile, ask:

- Does it respect user intent?
- Does it avoid unnecessary interruption?
- Does it teach without forcing learning?
- Does it preserve user agency?
- Does it improve interaction behavior rather than only output style?
- Does it avoid unsupported claims?
- Would it remain useful across many conversations?

Related reading:

- [Design Principles](design-principles.md)
- [Project Philosophy](philosophy.md)
- [Profiles](../profiles/README.md)
