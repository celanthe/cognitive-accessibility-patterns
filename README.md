# Cognitive Accessibility Pattern Library

WCAG tells you what to test. This tells you what to build.

---

## What This Is

Design patterns for cognitive accessibility, extracted from shipping software. Each pattern documents a specific interaction design that supports users with ADHD, dyslexia, executive dysfunction, grief, or other cognitive and emotional states that mainstream UX does not design for.

Every pattern in this library is grounded in a real product. No hypotheticals. No "consider doing this." These patterns exist in software that people use.

## Why This Exists

The W3C Cognitive Accessibility (COGA) task force has identified significant gaps in accessibility guidance for cognitive and emotional states. WCAG provides testable success criteria, but testability requires that someone first figures out what to build. That work has largely not happened.

This library fills the gap between "cognitive accessibility matters" and "here is a concrete pattern you can implement."

## Patterns

| Pattern | Mechanism | Source Projects |
|---------|-----------|----------------|
| [Context Restoration](patterns/context-restoration.md) | Working memory offloading | EverbloomReader, Lumentide |
| [Energy-Matched Suggestions](patterns/energy-matched-suggestions.md) | Executive function support | Lumentide |
| [Parallel Input Channels](patterns/parallel-input-channels.md) | Dual-coding reinforcement | EverbloomReader |
| [Ritual-Based Transitions](patterns/ritual-based-transitions.md) | Emotional processing containers | Foghorn |
| [Progressive Trust](patterns/progressive-trust.md) | Cognitive load management | Lumentide |
| [Metacognition Through Use](patterns/metacognition-through-use.md) | Self-pattern recognition | Lumentide |

## How Patterns Are Structured

Each pattern follows a [consistent schema](schema/pattern-template.md):

- **Cognitive Mechanism** -- what is happening in the brain
- **The Pattern** -- what the software does
- **Evidence** -- which shipping projects implement it
- **COGA Mapping** -- how it relates to W3C cognitive accessibility criteria
- **Not This** -- what the pattern is not (prevents scope creep)

## Framework

These patterns are part of [Human-Rhythm Design](https://github.com/celanthe/human-rhythm-design), a framework for building software around cognitive, temporal, and emotional patterns. The framework has four dimensions (Memory, Attention, Time, Transitions) and each pattern maps to one or more of them.

## Source Projects

- **[EverbloomReader](https://everbloomreader.com)** -- Reading app for dyslexic readers. Word-level TTS synchronization, OpenDyslexic font, position memory.
- **[Lumentide](https://lumentide.vercel.app)** -- Task management for executive dysfunction. Energy reading, social battery tracking, metacognitive pattern analysis.
- **[Foghorn](https://github.com/celanthe/foghorn)** -- Weather-based grief rituals for ambiguous loss.
- **[Clarion](https://github.com/celanthe/clarion)** -- Self-hosted TTS proxy giving AI agents distinct voices.

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md) for how to propose a new pattern. The short version: every pattern needs a cognitive mechanism, at least one shipping project as evidence, and a COGA mapping.

## License

MIT
