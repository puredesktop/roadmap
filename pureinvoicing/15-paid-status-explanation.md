# Know what marking an invoice paid does

[GitHub issue #15](https://github.com/puredesktop/pureinvoicing/issues/15) · Open · `roadmap`

## More improvements

15. **Know what marking an invoice paid does.** Clarify next to the manual paid mark that it records payment as reported and does not initiate or verify a bank transaction.
   <!-- contribution: {"id": "paid-status-explanation", "size": "small", "goodFirstIssue": false, "guide": "docs/contributions/paid-status-explanation.md"} -->
   [Small · Implementation brief](https://github.com/puredesktop/pureinvoicing/blob/main/docs/contributions/paid-status-explanation.md)

## Scope

Keep outgoing invoices, one business identity and one ascending number counter. Do not add bookkeeping, tax filing, payment processing or automatic sending.

Size describes scope, not a promised completion time: **Small** = one focused interface change; **Medium** = coordinated interface/state work; **Large** = a feature across several flows, storage or export paths. All items are proposals, not claims that existing features are absent. Check the current code and extend what is there. Maintainers review code and tests before merging.

<!-- puredesktop-roadmap:paid-status-explanation -->
