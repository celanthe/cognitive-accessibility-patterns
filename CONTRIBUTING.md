# Contributing

## Proposing a Pattern

Every pattern in this library must meet three criteria:

1. **Named cognitive mechanism.** What is happening in the brain? Cite the process (working memory, executive function, attention regulation, emotional processing, dual coding). If you cannot name the mechanism, the pattern is not ready.

2. **Shipping evidence.** At least one real product must implement this pattern. "I think this would work" is not evidence. "This app does it and here is what users experience" is evidence. The product does not need to be yours, but you need to describe the implementation concretely.

3. **COGA mapping.** How does this pattern relate to W3C Cognitive Accessibility guidance? Does it satisfy an existing objective or success criterion? Does it address an identified gap? If there is no COGA connection, explain why the pattern still belongs in a cognitive accessibility library.

## Pattern Format

Use the [pattern template](schema/pattern-template.md). All sections are required except Implementation Notes.

## Submitting

1. Fork the repository
2. Create a new file in `patterns/` using kebab-case naming
3. Follow the template structure
4. Open a pull request with a brief summary of the pattern and its evidence

## What Does Not Belong Here

- Patterns without evidence from a real product
- General UX best practices (those belong in other pattern libraries)
- WCAG-testable patterns (if WCAG already covers it with a success criterion and sufficient techniques, it does not need to be here)
- Patterns that require specific technologies (the pattern is the interaction design, not the implementation)

## Style

- Write plainly. No jargon without definition.
- Use dashes instead of em-dashes.
- Be direct. "This pattern does X" not "This pattern aims to facilitate X."
- The "Not This" section is as important as "The Pattern" section. Clear boundaries prevent scope creep.
