# Read the same phase names everywhere

[GitHub issue #10](https://github.com/puredesktop/puregantt/issues/10) · Open · `roadmap`

## More improvements

9. **Read the same phase names everywhere.** Use the same readable phase names in the task row, phase picker and summary so internal keys never leak into one view.
   <!-- contribution: {"id": "phase-label-consistency", "size": "small", "goodFirstIssue": false, "guide": "docs/contributions/phase-label-consistency.md"} -->
   [Small · Implementation brief](https://github.com/puredesktop/puregantt/blob/main/docs/contributions/phase-label-consistency.md)

## Scope

Keep the task timeline, existing phases, owners, progress and dependency model; avoid introducing a new scheduling system.

Size describes scope, not a promised completion time: **Small** = one focused interface change; **Medium** = coordinated interface/state work; **Large** = a feature across several flows, storage or export paths. All items are proposals, not claims that existing features are absent. Check the current code and extend what is there. Maintainers review code and tests before merging.

<!-- puredesktop-roadmap:phase-label-consistency -->
