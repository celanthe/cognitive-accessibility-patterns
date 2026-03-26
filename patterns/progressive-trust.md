# Progressive Trust

> Show the user one thing. When they are ready, show them the next thing.

## Cognitive Mechanism

Cognitive overload occurs when the brain receives more information or options than working memory can process. For neurodivergent users, this threshold is often lower and more variable than for neurotypical users. A full-featured interface on first launch is not empowering -- it is paralyzing.

Progressive trust inverts the typical software model. Instead of showing everything and expecting the user to ignore what they do not need, it starts minimal and expands as the user demonstrates engagement. The software earns the right to show more by proving the user is ready for more.

## The Pattern

Start with a minimal set of features visible to the user. As the user interacts with the software, unlock additional features based on usage milestones. The milestones should be natural byproducts of use, not gamified gates.

Rules:
- Unlocks are based on actions the user would take anyway (adding tasks, completing tasks, logging sessions), not on artificial checkpoints
- New features are announced gently (not modal popups, not celebrations, not tutorials)
- Unlocked features never re-lock
- The user can always access everything through settings if they want to skip progressive disclosure
- No numbering, no progress bars, no "3 of 7 unlocked"

## Evidence

- **Lumentide**: Seven spirits unlock based on natural usage thresholds. Lunara and Cairn (energy reading and task capture) are always visible. Vesper (social battery) unlocks after 3 tasks. Arcana and Citrine (wind-down rituals and start celebration) unlock after the first completed task. Amethyst (pattern analysis) unlocks after 10 tasks, ensuring there is enough data for meaningful patterns. Aquaria (recharge suggestions) unlocks after the first social session. Each unlock is announced via ARIA live region and a brief, dismissible overlay.

## COGA Mapping

- **Objective 6: Minimize the user's cognitive load** -- Fewer visible options means less to process on any given screen.
- **Objective 5: Help users focus** -- The visible feature set matches the user's current engagement level, reducing distraction from features they have not yet needed.
- **Objective 8: Support adaptation and personalization** -- The interface adapts to the user's behavior over time without requiring manual configuration.

## Not This

- **Onboarding tutorials** -- Tutorials explain features upfront and hope the user remembers. Progressive trust shows features when the user is ready for them.
- **Gamified unlocks** -- Gamification ties unlocks to achievements, points, or streaks. Progressive trust ties unlocks to natural usage. There is no score.
- **Feature flags** -- Feature flags are developer-controlled toggles. Progressive trust is user-behavior-controlled disclosure. The user's actions determine what they see, not a deploy configuration.
- **Reduced/simplified modes** -- Simplified modes strip features permanently. Progressive trust adds features over time. The trajectory is toward full capability, not away from it.
