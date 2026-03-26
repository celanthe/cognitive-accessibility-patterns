# Energy-Matched Suggestions

> Show the user what they can do right now, not everything they should do eventually.

## Cognitive Mechanism

Executive function governs task initiation, prioritization, and switching. For users with ADHD or executive dysfunction, a full task list is not a tool -- it is a wall. The problem is not knowing what to do. The problem is matching available energy to an appropriate task. Energy varies by time of day, social exertion, sleep, and season. Software that reads energy state and filters accordingly removes the executive function bottleneck at the point of highest friction: starting.

## The Pattern

Assess the user's current energy level through a combination of temporal signals (time of day, day of week) and direct input (manual energy override). Use that assessment to filter, sort, or surface tasks that match the user's current capacity.

Low energy gets low-effort tasks. High energy gets tasks that require sustained focus. The full list still exists, but the default view is filtered to what is realistic right now.

Never hide tasks permanently. Never remove options. The filter is a lens, not a gate.

## Evidence

- **Lumentide**: Lunara (the Energy Tide Reader spirit) assesses energy from time of day and offers a manual override slider. TaskSuggestions filters the user's task list to show only tasks whose energy tag matches the current assessment. A user at low tide sees rest tasks and small wins. A user at high tide sees deep work. The same task list, two different views, zero decision overhead.

## COGA Mapping

- **Objective 5: Help users focus** -- Reducing the visible option set to energy-appropriate tasks removes decision paralysis.
- **Objective 6: Minimize the user's cognitive load** -- The user does not have to scan, evaluate, and filter their own list. The software does it.
- **Objective 2: Help users find what they need** -- Tasks they can actually do right now are surfaced. Tasks they cannot handle are present but not prominent.

## Not This

- **Priority sorting** -- Priority systems rank tasks by importance. Energy matching ranks tasks by capacity. A high-priority task at low energy is still the wrong suggestion.
- **Hiding tasks** -- Energy matching filters the view. It does not delete, archive, or suppress. The user can always see everything if they choose to.
- **Gamified productivity** -- Energy matching is not a reward system. There are no streaks, no points for completing suggested tasks, no guilt for ignoring them. The suggestion is an offer, not an assignment.
