# UX pattern library — choose by task

Use when a task involves navigation, forms, filtering, data displays, feedback, complex states, or interaction architecture. Patterns are context-dependent; never claim that one is universally "best".

| Decision | Option A — strengths / costs | Option B — strengths / costs | Decisive questions |
|---|---|---|---|
| Top navigation vs sidebar | Top: efficient for a few primary destinations; limited space | Sidebar: supports many grouped destinations; costs horizontal room | How many destinations, how often switched, what screen sizes? |
| Modal vs dedicated page | Modal: quick bounded action; weak for complex or long flows | Page: handles depth and navigation; increases context transition | Is the action brief and reversible? |
| Drawer vs inline controls | Drawer: keeps canvas available; visibility cost | Inline: discoverable; occupies space | Is the control frequently needed? |
| Table vs cards | Table: supports scanning/compare/sort; dense on mobile | Cards: flexible content and layout; harder multi-field comparison | Is field-by-field comparison core? |
| Persistent filters vs popover | Persistent: fast repeated refinement; uses width | Popover: compact; extra interaction | Number/frequency of filters and available space? |
| Pagination vs infinite scroll | Pagination: clear position and retrieval; explicit action | Infinite scroll: browsing continuity; weak reorientation and footer reachability | Does user browse or return to a precise result? |
| Immediate validation vs submit-time | Immediate: quick guidance if nonintrusive; can distract before enough data | Submit-time: calmer entry; errors appear later | What input type and recovery cost? |

## Non-negotiable design considerations

- **Visibility of system status**: loading, progress, completion, errors and recoverability.
- **Recognition over recall**: labels and options visible when required.
- **Error prevention**: safe defaults only if established, clear constraints and confirmations for destructive actions.
- **Control**: reversible actions, cancel/escape behavior, predictable back navigation where appropriate.
- **Access**: keyboard operation, visible focus, readable labels, contrast, reasonable target sizes.
- **Empty states**: truthful explanation and a task-relevant next step; do not invent data.
- **Content realism**: long labels, localization, no records, many records, unavailable assets.

## Evidence discipline

NN/g heuristics and WAI recommendations are useful guidance, not proof that a precise placement has been tested for a particular user group. Baymard evidence is particularly relevant to e-commerce and should not be generalized to every product. Record uncertainties.
