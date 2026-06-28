# FAQ

## Is This Another Chatbot?

No. AI Interaction Profiles is not a chatbot. It is a library of reusable behavior profiles for AI assistants people already use.

## Does This Replace ChatGPT, Claude, Gemini, Or Other Assistants?

No. The project assumes users should keep whichever assistant they prefer. Interaction Profiles are intended for personalization, custom-instruction, or similar user-controlled settings where available.

## Will This Improve Model Intelligence?

No. Interaction Profiles do not train, fine-tune, modify, or improve the underlying model.

They may change how an assistant behaves in conversation. They do not change what the model knows or can verify.

## Why Not Just Write Better Task Instructions?

Task instructions help with a single request. Interaction Profiles guide recurring behavior across many requests.

For example:

```text
Summarize this article in five bullets.
```

That is a task instruction.

```text
Ask for clarification only when the missing information would materially change the answer.
```

That is interaction behavior.

## Why Different Interaction Profiles?

Different situations call for different interaction patterns.

A difficult email may need communication support. A decision may need structured trade-offs. Everyday work may need low-friction help. Complex learning may need guided reasoning.

Use the [Profile Index](../profiles/index.md) or [Comparison Matrix](comparison-matrix.md) to choose quickly.

## Can I Use Multiple Profiles?

Usually, start with one. Combining profiles may create conflicting behavior, such as one profile favoring speed while another favors deeper reflection.

If you combine profiles, treat the result as an experiment and watch for friction.

## What Is The Difference Between Full And Concise Versions?

Each profile includes two copyable versions:

- **Full Version:** recommended whenever your AI platform supports longer persistent instructions.
- **Concise Version:** optimized for platforms with approximately 1500-character instruction limits, such as ChatGPT Personalization or Gemini Personalization.

The Concise Version is compressed, not simplified.

## Will This Become Software?

Possibly later, if the interaction concept proves useful. Version 1.0 is documentation-first and does not define software, extension behavior, APIs, model wrappers, or automation.

## Can I Contribute New Profiles?

Yes, but profile contributions should follow the repository's design principles and review standards.

Useful contributions include:

- clearer examples;
- profile quality improvements;
- evaluation questions;
- documentation clarity;
- critique of assumptions;
- consistency fixes.

See the [Contributing Guide](../CONTRIBUTING.md).

## Is This Scientifically Proven?

No. This is an exploratory proof-of-concept. It does not claim scientific validation, measured improvement, or universal effectiveness.

Future work may include qualitative feedback, comparison exercises, and evaluation methods.

## Can Profiles Make AI Outputs Correct?

No. A profile may influence conversational behavior, but it cannot guarantee factual accuracy. Users should evaluate AI outputs carefully, especially for health, law, finance, employment, safety, or other high-stakes contexts.

## Why Focus On Interaction Instead Of Outputs?

Outputs matter, but a conversation includes more than the final answer.

The assistant must decide when to ask, infer, explain, challenge, simplify, or stay quiet. Those choices affect whether the user feels supported, interrupted, overwhelmed, or more capable.

## Is This About Making Users Write Perfectly?

No. Modern LLMs already handle imperfect language well. The point is not to make users perform correctness for the model.

The point is to help users think, communicate, and decide more clearly when clarity matters.

## Is This Only For Advanced Users?

No. The project is especially relevant for people who do not want to learn complicated AI usage techniques. A good Interaction Profile should reduce the burden on the user, not add another layer of work.
