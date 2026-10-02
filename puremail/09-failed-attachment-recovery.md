# Retry a failed attachment without losing the message

[GitHub issue #16](https://github.com/puredesktop/puremail/issues/16) · Open · `roadmap`

## More improvements

9. **Retry a failed attachment without losing the message.** Name the attachment that failed, preserve the message draft and let the user remove or retry that attachment explicitly.
   <!-- contribution: {"id": "failed-attachment-recovery", "size": "medium", "goodFirstIssue": false, "guide": "docs/contributions/failed-attachment-recovery.md"} -->
   [Medium · Implementation brief](https://github.com/puredesktop/puremail/blob/main/docs/contributions/failed-attachment-recovery.md)

## Scope

Keep account-backed mail, threaded reading, drafts, work tracking and existing send approval. Provider expansion remains separate.

Size describes scope, not a promised completion time: **Small** = one focused interface change; **Medium** = coordinated interface/state work; **Large** = a feature across several flows, storage or export paths. All items are proposals, not claims that existing features are absent. Check the current code and extend what is there. Maintainers review code and tests before merging.

<!-- puredesktop-roadmap:failed-attachment-recovery -->
