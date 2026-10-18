# Coherent design systems for Arthur

## First step: reuse

Inspect approved project tokens, components and guidelines. Don't introduce a parallel button, font scale, shadow system or radius scheme just because an example looks appealing.

## Design-token layers

- **Foundation**: neutral/accent palettes, typography families, spacing/size scales, shape primitives.
- **Semantic**: text, backgrounds, surfaces, borders, focus, danger, success, disabled states.
- **Component**: button/input/table/dialog values only where semantic/foundation tokens are insufficient.

Use semantic roles rather than color-name assumptions. Verify a new token is actually needed before adding it. Never invent official brand values or imply numbers are approved.

## Component anatomy

For each required component specify purpose, anatomy, variants, size behavior, interaction contract, focus/hover/disabled/loading/error states, text overflow, keyboard access, and responsive rules.

Prefer established interface conventions for task-critical behavior. Visual character should not obscure clickability or comprehension.

## Responsive composition

Define what reflows, collapses, persists and changes order. Preserve semantic reading and keyboard order. Cover dense data, long content, narrow screens, reduced motion and zoom. Don't add mobile-specific features unless authorized.

## Motion

Movement is justified only when it conveys status, relationship, continuity or required brand direction. Provide reduced-motion alternatives when motion is used. Prohibit auto-added parallax, custom cursors, scrolljacking and ornamental transitions.

## Handoff

Give exact approved tokens and unresolved decisions separately. Never mark proposed values as existing system values.
