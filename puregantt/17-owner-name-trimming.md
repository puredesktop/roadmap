# Avoid duplicate owner names caused by spaces

[GitHub issue #18](https://github.com/puredesktop/puregantt/issues/18) · Open · `roadmap`

## More improvements

17. **Avoid duplicate owner names caused by spaces.** Trim accidental leading and trailing spaces when committing owner names so visually identical owners do not create separate filter entries.
   <!-- contribution: {"id": "owner-name-trimming", "size": "small", "goodFirstIssue": false, "guide": "docs/contributions/owner-name-trimming.md"} -->
   [Small · Implementation brief](https://github.com/puredesktop/puregantt/blob/main/docs/contributions/owner-name-trimming.md)

## Scope

Keep the task timeline, existing phases, owners, progress and dependency model; avoid introducing a new scheduling system.

Size describes scope, not a promised completion time: **Small** = one focused interface change; **Medium** = coordinated interface/state work; **Large** = a feature across several flows, storage or export paths. All items are proposals, not claims that existing features are absent. Check the current code and extend what is there. Maintainers review code and tests before merging.

<!-- puredesktop-roadmap:owner-name-trimming -->
