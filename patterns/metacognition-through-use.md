# Metacognition Through Use

> The software teaches you your own patterns by showing them to you over time.

## Cognitive Mechanism

Metacognition is the ability to notice, understand, and regulate your own cognitive processes. For users with ADHD or executive dysfunction, metacognitive awareness is often impaired: they know they struggle with time, energy, and task initiation, but they cannot reliably observe their own patterns in real time. Tips, articles, and coaching tell people what patterns to look for. This does not work for brains that cannot self-monitor consistently.

Metacognition through use takes a different approach. Instead of teaching the user about their patterns, the software accumulates data from natural interactions and surfaces the patterns visually. The user does not need to self-observe. They just use the software. Over time, the software shows them what it has learned about them.

## The Pattern

Collect behavioral data passively through normal app usage (task completion times, energy levels, session patterns, social battery drain). Over a meaningful time period, analyze the accumulated data and present the user with visual summaries of their own patterns.

Key requirements:
- Data collection is passive. The user is never asked to log, journal, or reflect for the purpose of pattern analysis.
- Patterns are shown, not prescribed. "You tend to complete more tasks in the morning" is observation. "Try doing hard tasks in the morning" is prescription. Show the first. Never do the second.
- A minimum data threshold must be met before patterns are shown. Premature pattern analysis with insufficient data is worse than no analysis.
- All data stays local. Pattern analysis that requires sending behavioral data to a server is a privacy violation for this population.
- Patterns update over time. Early patterns may be revised as more data accumulates. The software should communicate confidence gently ("emerging pattern" vs "consistent pattern").

## Evidence

- **Lumentide**: Amethyst (the My Patterns spirit) unlocks after 10 tasks, ensuring a minimum data threshold. It analyzes task completion times, energy levels at completion, and session frequency to surface patterns like peak productivity windows, energy rhythms across the week, and task-type preferences by energy state. The user never fills out a metacognition worksheet. They add tasks, complete them, and Amethyst learns. After enough use, the user opens Amethyst and sees their own rhythms mapped out.

## COGA Mapping

- **Objective 8: Support adaptation and personalization** -- The interface learns from the user and personalizes its insights without requiring configuration.
- **COGA Task Force gap**: Metacognitive support is referenced in COGA research as a need but has no corresponding success criteria or design guidance. This pattern is a concrete implementation of that identified gap.

## Not This

- **Analytics dashboards** -- Dashboards show metrics. Metacognition through use shows personal patterns with cognitive context. "You completed 12 tasks this week" is analytics. "Your energy peaks around 10am on weekdays" is metacognition.
- **Personality quizzes or assessments** -- Assessments ask the user to describe themselves. Metacognition through use observes behavior and reflects it back. The user does not need to have the vocabulary for their patterns -- the software provides it.
- **AI coaching** -- Coaching interprets patterns and offers advice. Metacognition through use shows patterns without interpretation. The user draws their own conclusions. The software is a mirror, not a coach.
- **Habit trackers** -- Habit trackers measure adherence to user-defined goals. Metacognition through use has no goals. It reveals what is already happening, not what should be happening.
