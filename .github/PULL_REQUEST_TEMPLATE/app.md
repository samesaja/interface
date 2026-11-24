## Summary

<!-- What changed and why? See AGENTS.md and CONTRIBUTING.md for the repository's quality and completeness rules. -->

## Root cause & sibling analysis

<!-- Required for bug fixes and behavioural changes (AGENTS.md §3 / CONTRIBUTING.md "Fixing issues properly"):
  1. Root cause: Why was the bad state reachable at all? (Fixing a symptom or adding a superficial guard without addressing the underlying cause is not sufficient.)
  2. Sibling instances: Did you search the codebase for other occurrences of the same bug class? List any sibling files updated here or link the follow-up issue.
-->

- **Root cause:**
- **Sibling instances checked:**
- [ ] Root cause identified and fixed rather than suppressing the symptom ([`AGENTS.md` §3](../../AGENTS.md#3-fix-issues-completely))
- [ ] Searched for sibling instances of the same bug class across the codebase and addressed or documented them

## Regression coverage

<!-- Name the regression test(s) that fail before this change and pass after. If a regression test is genuinely not applicable, explain why below. -->

- **Regression test(s) added/updated (or reason not applicable):**
- [ ] Added a regression test that fails before the fix and passes after, or documented why a regression test is not applicable ([`AGENTS.md` §3](../../AGENTS.md#3-fix-issues-completely))
- [ ] No checks, lint rules, type checks, coverage thresholds, or tests were disabled, skipped (`.skip` / `.only`), or weakened (`eslint-disable`, `@ts-ignore`, `@ts-expect-error`) to obtain a green build ([`AGENTS.md` §2](../../AGENTS.md#2-never-weaken-a-check-to-make-it-pass))

## Verification

<!-- Every command in the commit gate (AGENTS.md §1) must be run and pass locally before opening a PR. -->

- [ ] `bun lint`
- [ ] `bun typecheck`
- [ ] `bun run check:tokens`
- [ ] `bun run check:content`
- [ ] `bun run test`
- [ ] `bun run test:coverage`
- [ ] `bun run build`
- [ ] UI checked at 360px and desktop widths
- [ ] Keyboard and screen-reader behavior checked

## Accessibility

<!-- Describe focus, keyboard, ARIA, and touch-target verification. -->

## Related issues

Closes #
