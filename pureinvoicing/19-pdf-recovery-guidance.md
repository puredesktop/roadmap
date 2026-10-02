# Recover a missing issued PDF

[GitHub issue #19](https://github.com/puredesktop/pureinvoicing/issues/19) · Open · `roadmap`

## More improvements

19. **Recover a missing issued PDF.** If an issued invoice lacks its retained PDF, distinguish that state from an unissued draft and point to the existing recovery or reissue action.
   <!-- contribution: {"id": "pdf-recovery-guidance", "size": "medium", "goodFirstIssue": false, "guide": "docs/contributions/pdf-recovery-guidance.md"} -->
   [Medium · Implementation brief](https://github.com/puredesktop/pureinvoicing/blob/main/docs/contributions/pdf-recovery-guidance.md)

## Scope

Keep outgoing invoices, one business identity and one ascending number counter. Do not add bookkeeping, tax filing, payment processing or automatic sending.

Size describes scope, not a promised completion time: **Small** = one focused interface change; **Medium** = coordinated interface/state work; **Large** = a feature across several flows, storage or export paths. All items are proposals, not claims that existing features are absent. Check the current code and extend what is there. Maintainers review code and tests before merging. Attribution is your choice.

<!-- puredesktop-roadmap:pdf-recovery-guidance -->
