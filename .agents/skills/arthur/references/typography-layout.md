# Typography, composition and pixel-accurate specifications

Use to convert an approved visual direction into measurable, implementable geometry.

## Typography decisions

- Assign roles: display, h1–h6, body, compact/body secondary, caption, numeric data, interactive labels.
- Specify font family **only if available/approved**, fallbacks, weight, size, line-height, tracking where relevant, casing and text-wrap rules.
- Consider Cyrillic/Latin glyph support, readability, numeral alignment, punctuation, hyphenation and localization.
- Avoid decorative tiny labels, weak contrast and random font mixing.
- Check headline line breaks with *real* text. Do not fabricate missing copy or images.
- Choose line lengths appropriate to reading contexts; do not enforce a single magic character count everywhere.

## Composition decisions

- Identify principal information/action first; set scale and prominence from task priority.
- Select a justified structure (one-column editorial, multi-column, split, dense data grid, etc.).
- Define content max-width, columns, gutters, vertical rhythm, alignment anchors, section separation, and text/image relationships.
- Decide where asymmetry serves hierarchy; avoid forced decoration.
- Separate mobile recomposition from simple desktop shrinking.

## Precision contract

A pixel-perfect intent requires an **approved target** (specified values, approved mockup or verified screenshot). Record:
- Reference viewport and behavior at other widths.
- Container geometry, padding, gaps, alignment and component dimensions.
- Type rendering assumptions, assets and crop/fit rules.
- Border widths, corner radii, icon bounding boxes, optical offsets.
- Interactive, focus, empty, loading and error states.
- Responsive rules and overflow behavior.

Where the target doesn't specify a measurement, mark any proposed value as a design choice, not as a fact taken from the reference. Never claim browser fidelity or independent final QA unless a dedicated check has actually occurred.
