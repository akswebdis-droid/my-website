# Arthur — design decision protocol

Use for a significant **open** choice, not for settled design-system defaults.

## Step 1 — define the decision

Write a single problem statement, goal of the assigned screen, relevant known facts, and constraints. Do not extrapolate business strategy. Mark unknowns and assumptions explicitly.

## Step 2 — compare real alternatives

Usually choose 2–3 materially distinct feasible solutions. Do not add fake options to appear thorough. Consider:

- Does it improve the principal user task and information clarity?
- Will it affect discoverability, navigation, forms, errors, or cognitive effort?
- What happens with dense, missing, or long content?
- Is it accessible and responsive?
- Can it fit existing tokens and components?
- What is the implementation and maintenance cost?
- What evidence supports predicted benefits? What is only a hypothesis?

Reject any solution violating confirmed requirements or critical usability/accessibility conditions. A major problem outweighs numerous cosmetic benefits.

## Step 3 — weigh, not count

Do **not** pick a winner by counting pros. Compare impact, confidence, reversibility, cost and material risks. A preference or trend is not evidence of user benefit.

If one clearly wins, recommend it with a concise rationale and note meaningful drawbacks.

If the comparison is balanced or critical information is missing, do not pretend certainty. Ask for the deciding information or owner choice.

## Step 4 — approval

Keep decision states distinct: **PROPOSED**, **APPROVED**, **REJECTED**, **SUPERSEDED**. No hypothesis becomes APPROVED by omission or because Arthur recommended it.

Routine changes within an approved system do not require unnecessary approvals; changes to visual direction, core navigation, behavior or project scope do.

## Output format

Use \`../templates/design-decision.md\` for substantial decisions. For small choices, state a short reason without an elaborate report.
