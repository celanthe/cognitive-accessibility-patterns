# Human-Rhythm Design

**Cognitive + Temporal + Emotional**

Most software for neurodivergent people is neurotypical software with accessibility bolted on. The Human-Rhythm Design Framework builds from the other direction, starting with how AuDHD, dyspraxic, and dyscalculic brains actually experience time, memory, attention, transitions, and grief.

Each project is both a real tool and a research artifact. Together they map a design space that mainstream UX does not have vocabulary for.

---

## The Framework

Five dimensions. Each project lives in one of them.

| Dimension | What it means | Project |
|-----------|--------------|---------|
| **Memory** | Working memory is fragile and the first thing to go under load. Software should hold position, state, and continuity. | [EverbloomReader](https://github.com/celanthe/everbloom) |
| **Attention** | Focus fluctuates, fragments, and sometimes just leaves. Software should offer alternative modalities and recover gracefully. | Pattern Library (this repo) |
| **Time** | Capacity shifts by the hour, the season, the weight of everything else. Software should read that state and adapt. | [Lumentide](https://github.com/celanthe/tidewater-cove) |
| **Transitions** | Grief, shutdown, overwhelm. Real user states that most software ignores. Software should hold space without demanding resolution. | [Foghorn](https://github.com/celanthe/foghorn) |
| **Voice** | When every agent sounds identical, the brain stops differentiating. Software should give each voice a distinct identity. | [Clarion](https://github.com/celanthe/clarion) |

Read the full framework definition, dimensions, and principles in [framework/README.md](framework/README.md).

---

## The Pattern Library

Design patterns for cognitive accessibility, extracted from shipping software. Every pattern documents a specific interaction design that supports users with ADHD, dyslexia, executive dysfunction, grief, or other cognitive and emotional states that mainstream UX does not design for.

WCAG tells you what to test. This tells you what to build.

Every pattern in this library is grounded in a real product. No hypotheticals. No "consider doing this." These patterns exist in software that people use.

### Patterns

| Pattern | Mechanism | Source Projects |
|---------|-----------|----------------|
| [Context Restoration](patterns/context-restoration.md) | Working memory offloading | EverbloomReader, Lumentide |
| [Energy-Matched Suggestions](patterns/energy-matched-suggestions.md) | Executive function support | Lumentide |
| [Parallel Input Channels](patterns/parallel-input-channels.md) | Dual-coding reinforcement | EverbloomReader |
| [Ritual-Based Transitions](patterns/ritual-based-transitions.md) | Emotional processing containers | Foghorn |
| [Progressive Trust](patterns/progressive-trust.md) | Cognitive load management | Lumentide |
| [Metacognition Through Use](patterns/metacognition-through-use.md) | Self-pattern recognition | Lumentide |
| [Voice Identity Differentiation](patterns/voice-identity-differentiation.md) | Auditory selective attention | Clarion |

### How Patterns Are Structured

Each pattern follows a [consistent schema](schema/pattern-template.md):

- **Cognitive Mechanism** -- what is happening in the brain
- **The Pattern** -- what the software does
- **Evidence** -- which shipping projects implement it
- **COGA Mapping** -- how it relates to W3C cognitive accessibility criteria
- **Not This** -- what the pattern is not (prevents scope creep)

### Why This Exists

The W3C Cognitive Accessibility (COGA) task force has identified significant gaps in accessibility guidance for cognitive and emotional states. WCAG provides testable success criteria, but testability requires that someone first figures out what to build. That work has largely not happened.

This library fills the gap between "cognitive accessibility matters" and "here is a concrete pattern you can implement."

---

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md) for how to propose a new pattern. The short version: every pattern needs a cognitive mechanism, at least one shipping project as evidence, and a COGA mapping.

## License

MIT
