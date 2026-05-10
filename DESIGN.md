# The unreasonable effectiveness of HTML — examples

## Mission
Create implementation-ready, token-driven UI guidance for The unreasonable effectiveness of HTML — examples that is optimized for consistency, accessibility, and fast delivery across content site.

## Brand
- Product/brand: The unreasonable effectiveness of HTML — examples
- URL: https://thariqs.github.io/html-effectiveness/
- Audience: developers and technical teams
- Product surface: content site

## Style Foundations
- Visual style: structured, tokenized, content-first
- Main font style: `font.family.primary=system-ui`, `font.family.stack=system-ui, -apple-system, Segoe UI, Roboto, Helvetica, Arial, sans-serif`, `font.size.base=16px`, `font.weight.base=400`, `font.lineHeight.base=24.8px`
- Typography scale: `font.size.xs=12.5px`, `font.size.sm=13px`, `font.size.md=14.5px`, `font.size.lg=16px`, `font.size.xl=16.5px`, `font.size.2xl=27px`, `font.size.3xl=62px`
- Color palette: `color.text.primary=#141413`, `color.text.secondary=#3d3d3a`, `color.text.tertiary=#d97757`, `color.text.inverse=#87867f`, `color.surface.base=#000000`, `color.surface.muted=#ffffff`, `color.surface.raised=#faf9f5`, `color.border.default=#d1cfc5`
- Spacing scale: `space.1=7px`, `space.2=8px`, `space.3=12px`, `space.4=14px`, `space.5=22px`, `space.6=24px`, `space.7=26px`, `space.8=36px`
- Radius/shadow/motion tokens: `radius.xs=14px`, `radius.sm=999px` | `motion.duration.instant=120ms`, `motion.duration.fast=150ms`

## Accessibility
- Target: WCAG 2.2 AA
- Keyboard-first interactions required.
- Focus-visible rules required.
- Contrast constraints required.

## Writing Tone
Concise, confident, implementation-focused.

## Rules: Do
- Use semantic tokens, not raw hex values, in component guidance.
- Every component must define states for default, hover, focus-visible, active, disabled, loading, and error.
- Component behavior should specify responsive and edge-case handling.
- Interactive components must document keyboard, pointer, and touch behavior.
- Accessibility acceptance criteria must be testable in implementation.

## Rules: Don't
- Do not allow low-contrast text or hidden focus indicators.
- Do not introduce one-off spacing or typography exceptions.
- Do not use ambiguous labels or non-descriptive actions.
- Do not ship component guidance without explicit state rules.

## Guideline Authoring Workflow
1. Restate design intent in one sentence.
2. Define foundations and semantic tokens.
3. Define component anatomy, variants, interactions, and state behavior.
4. Add accessibility acceptance criteria with pass/fail checks.
5. Add anti-patterns, migration notes, and edge-case handling.
6. End with a QA checklist.

## Required Output Structure
- Context and goals.
- Design tokens and foundations.
- Component-level rules (anatomy, variants, states, responsive behavior).
- Accessibility requirements and testable acceptance criteria.
- Content and tone standards with examples.
- Anti-patterns and prohibited implementations.
- QA checklist.

## Component Rule Expectations
- Include keyboard, pointer, and touch behavior.
- Include spacing and typography token requirements.
- Include long-content, overflow, and empty-state handling.
- Include known page component density: links (30), cards (20), navigation (2).

- Extraction diagnostics: Audience and product surface inference confidence is low; verify generated brand context.

## Quality Gates
- Every non-negotiable rule must use "must".
- Every recommendation should use "should".
- Every accessibility rule must be testable in implementation.
- Teams should prefer system consistency over local visual exceptions.
