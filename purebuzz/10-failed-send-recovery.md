# Retry a failed message deliberately

[GitHub issue #11](https://github.com/puredesktop/purebuzz/issues/11) · Open · `roadmap`

## More improvements

10. **Retry a failed message deliberately.** Keep failed message text available with an explicit retry action and a clear pending state; never resend automatically after an ambiguous acknowledgement.
   <!-- contribution: {"id": "failed-send-recovery", "size": "medium", "goodFirstIssue": false, "guide": "docs/contributions/failed-send-recovery.md"} -->
   [Medium · Implementation brief](https://github.com/puredesktop/purebuzz/blob/main/docs/contributions/failed-send-recovery.md)

## Scope

Keep relay-based team messaging over the existing Buzz/Nostr protocol, with current membership and approval boundaries.

Size describes scope, not a promised completion time: **Small** = one focused interface change; **Medium** = coordinated interface/state work; **Large** = a feature across several flows, storage or export paths. All items are proposals, not claims that existing features are absent. Check the current code and extend what is there. Maintainers review code and tests before merging.

<!-- puredesktop-roadmap:failed-send-recovery -->
