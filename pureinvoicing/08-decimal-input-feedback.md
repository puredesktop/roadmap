# Correct a price without it becoming zero

[GitHub issue #8](https://github.com/puredesktop/pureinvoicing/issues/8) · Open · `roadmap`

## More improvements

8. **Correct a price without it becoming zero.** Explain malformed quantity or price input next to the field and retain the draft text instead of silently turning it into zero.
   <!-- contribution: {"id": "decimal-input-feedback", "size": "medium", "goodFirstIssue": false, "guide": "docs/contributions/decimal-input-feedback.md"} -->
   [Medium · Implementation brief](https://github.com/puredesktop/pureinvoicing/blob/main/docs/contributions/decimal-input-feedback.md)

## Scope

Keep outgoing invoices, one business identity and one ascending number counter. Do not add bookkeeping, tax filing, payment processing or automatic sending.

Size describes scope, not a promised completion time: **Small** = one focused interface change; **Medium** = coordinated interface/state work; **Large** = a feature across several flows, storage or export paths. All items are proposals, not claims that existing features are absent. Check the current code and extend what is there. Maintainers review code and tests before merging.

<!-- puredesktop-roadmap:decimal-input-feedback -->
