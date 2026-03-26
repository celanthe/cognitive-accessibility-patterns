# Context Restoration

> Software holds your place so your brain doesn't have to.

## Cognitive Mechanism

Working memory has limited capacity and degrades under fatigue, distraction, and interruption. For users with ADHD, dyslexia, or executive dysfunction, re-establishing context after a break can cost more effort than the original task. Context restoration offloads positional memory to the software, making re-entry nearly free.

## The Pattern

Automatically persist the user's position, task state, and navigation context at meaningful intervals. On return, restore exactly where they left off without requiring them to remember, search, or reconstruct their mental model.

Context restoration goes beyond autosave. It preserves not just the content but the user's relationship to the content: where they were reading, what they were working on, which view they had open, what state their task was in.

The restoration should be silent. No "welcome back" modal. No "you were last here on..." banner. Just the screen they left, in the state they left it.

## Evidence

- **EverbloomReader**: Reading position saved per book at the word level. When a reader reopens a book, TTS and word-level highlighting resume from the exact point they stopped. No bookmarking required. No scroll hunting. The reader's place is the software's responsibility, not theirs.

- **Lumentide**: Task list preserves order, energy assessment, and last interaction state. Reopening the app after hours or days shows the same view with the same tasks in the same priority order. Energy is re-assessed from the current time, but task context is unchanged. There is no "start fresh" friction.

## COGA Mapping

- **Objective 5: Help users focus** -- Eliminating re-orientation effort preserves the user's available attention for the actual task.
- **Objective 6: Minimize the user's cognitive load** -- Position memory is offloaded entirely to the software.
- **SC 2.9.1 (proposed): Adapt** -- The interface adapts its state to reduce cognitive load on re-entry.

## Not This

- **Autosave** -- Autosave preserves content. Context restoration preserves the user's mental position within that content. A document can be autosaved while the user still has to scroll through 50 pages to find where they were.
- **Session restoration** -- Browsers restore tabs. That is session restoration, not context restoration. The user still has to figure out what they were doing across those tabs.
- **Bookmarks** -- Bookmarks require the user to decide to save their place. Context restoration requires nothing. The default is remembering.
