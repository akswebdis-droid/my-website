# REDESIGN — controlled improvement of an existing interface

## Trigger and principle

A request to redesign a website, page, workflow, app, or component. **Preserve what works and change only what is authorized.** Redesign does not imply rebuilding the whole product.

## Inputs and protected assets

1. Identify exact requested screens/flows and stated problems.
2. Inspect existing UI evidence, project files, styles, components, supplied screenshots/Figma refs, and approved requirements when available.
3. Record **protected invariants**: functionality, content, URLs/navigation contracts, accessibility behaviors, business logic, data shapes, existing brand tokens unless change is authorized.
4. Record known constraints: platforms, breakpoints, performance, maintainability, deadlines if stated.
5. If existing UI or the objective is unavailable, ask for the essential missing input instead of inventing the current state.

## Diagnose within design scope

Describe the design problem in terms of task performance, information structure, legibility, density, hierarchy, component affordances, or visual coherence. This is **design analysis to propose a redesign**, not an independent final QA audit.

Do not pretend to have observed a screenshot, behavior, or usability test that has not been supplied or inspected.

## Compare and decide

- Start with the smallest viable change.
- Compare "targeted refinement" against "structural redesign" only when both are actually plausible.
- For substantial decisions, compare 2–3 materially different options via \`decision-making.md\`.
- Show impact and risks to usability, visual consistency, development cost, and existing flows.
- Propose important design hypotheses for approval; do not silently change major navigation, interaction contracts, or brand character.
- When no option significantly dominates, present trade-offs and ask the owner to choose.

## Execution rules

- Keep unaffected areas, functions, content, and code unchanged.
- Reuse existing components and tokens first.
- Make a mapping: **existing element → proposed change → reason → risk → approval status**.
- Specify typography, geometry, responsive layouts, behavior and state transitions precisely.
- If implementation is requested and approvals are in place, implement only the authorized subset in the existing stack.
- Do not add decorative motion, new sections, marketing claims or extra dependencies without a reason and authorization.

## Deliverable

1. Scope and confirmed facts.
2. Preserved invariants.
3. Problems supported by available evidence.
4. Compared alternatives (when a material decision is open).
5. Recommended change set with approval markers.
6. Detailed before/after interaction and visual specifications.
7. Open questions and handoff notes.

Final visual acceptance, independent screenshot audits, and regression sign-off belong to the separate QA skill.
