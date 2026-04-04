# Human-Rhythm Design

**Cognitive + Temporal + Emotional**

Most software for neurodivergent people is neurotypical software with accessibility bolted on. The Human-Rhythm Design Framework builds from the other direction, starting with how AuDHD, dyspraxic, and dyscalculic brains actually experience time, memory, attention, transitions, and grief.

Each project is both a real tool and a research artifact. Together they map a design space that mainstream UX does not have vocabulary for: task management that celebrates starting over finishing, reading tools that sync to how dyslexic brains process speech, grief software that treats shutdown as a legitimate user state rather than an error to recover from.

The framework has five dimensions. Each project lives in one of them.

---

## Dimensions

### Memory

Working memory is limited, fragile, and the first thing to go under load. Context doesn't stick. It decays. Software should hold position, state, and continuity so the user never has to reconstruct where they were.

**Project:** [EverbloomReader](https://github.com/celanthe/everbloom) -- Reading app for dyslexic readers with word-level TTS sync

### Attention

Focus isn't a toggle; it fluctuates, fragments, and sometimes just leaves. Expecting sustained concentration is a design choice, not a given. Software should offer alternative modalities and recover gracefully when attention drifts. Because it will.

**Project:** [Pattern Library](https://github.com/celanthe/cognitive-accessibility-patterns) -- Design patterns for cognitive accessibility, COGA-mapped

### Time

Capacity shifts by the hour, the season, the weight of everything else on the stack. The brain doesn't experience duration on a clock. It runs on energy, rhythm, and social load. Software should read that state and adapt instead of pretending every moment is the same.

**Project:** [Lumentide](https://github.com/celanthe/tidewater-cove) -- Task management for executive dysfunction with energy reading and metacognition

### Transitions

Grief, shutdown, overwhelm. These aren't edge cases. They're real user states that most software either ignores or tries to rush past. Software should hold space for them without demanding resolution.

**Project:** [Foghorn](https://github.com/celanthe/foghorn) -- Weather-based grief rituals for ambiguous loss

### Voice

When every agent sounds identical, the brain stops trying to tell them apart. Speaker differentiation is a trust mechanism. We assign credibility partly by recognizing who's talking. Software should give each voice a distinct identity so the user can track source without reading labels.

**Project:** [Clarion](https://github.com/celanthe/clarion) -- Self-hosted TTS proxy giving AI agents distinct voices

---

## Principles

1. **Design for the body, not the ideal user.** Real brains forget, fatigue, grieve, and get interrupted. Start there.
2. **The moment is a valid unit of experience.** Not everything needs to accumulate into progress.
3. **Dignity in the defaults.** Never clinical. Never infantilizing. Beautiful by default.
4. **No data collection without meaningful consent.** If someone cannot consent, the answer is no, not "implied consent."
5. **Accessibility is the design, not a layer on top.** WCAG is the floor, not the ceiling. COGA is the standard for cognitive accessibility.
6. **Name hard things honestly.** Grief, disability, exhaustion, shutdown. If the framework cannot say these words, it cannot design for the people who live them.

---

## Methodology

Projects in the framework use [Investiture](https://github.com/celanthe/investiture) for project doctrine and structured research. Each project maintains:

- **VECTOR.md** -- Project identity, audience, constraints, design principles
- **CLAUDE.md** -- Contributor onboarding
- **ARCHITECTURE.md** -- Technical specification
- **/vector/** -- Research artifacts (interviews, personas, assumptions, decisions)

---

## License

MIT
