# Retry saving without losing the timeline

[GitHub issue #21](https://github.com/puredesktop/puregantt/issues/21) · Open · `roadmap`

## More improvements

20. **Retry saving without losing the timeline.** Keep an unsaved timeline visible after a write error, show the document name and provide an explicit retry without discarding edits.
   <!-- contribution: {"id": "save-failure-continuity", "size": "medium", "goodFirstIssue": false, "guide": "docs/contributions/save-failure-continuity.md"} -->
   [Medium · Implementation brief](https://github.com/puredesktop/puregantt/blob/main/docs/contributions/save-failure-continuity.md)

## Scope

Keep the task timeline, existing phases, owners, progress and dependency model; avoid introducing a new scheduling system.

Size describes scope, not a promised completion time: **Small** = one focused interface change; **Medium** = coordinated interface/state work; **Large** = a feature across several flows, storage or export paths. All items are proposals, not claims that existing features are absent. Check the current code and extend what is there. Maintainers review code and tests before merging. Attribution is your choice.

<!-- puredesktop-roadmap:save-failure-continuity -->
