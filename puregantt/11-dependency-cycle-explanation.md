# See which tasks form a dependency cycle

[GitHub issue #12](https://github.com/puredesktop/puregantt/issues/12) · Open · `roadmap`

## More improvements

11. **See which tasks form a dependency cycle.** When a link would create a cycle, name the tasks in the detected cycle rather than showing only a generic rejection.
   <!-- contribution: {"id": "dependency-cycle-explanation", "size": "medium", "goodFirstIssue": false, "guide": "docs/contributions/dependency-cycle-explanation.md"} -->
   [Medium · Implementation brief](https://github.com/puredesktop/puregantt/blob/main/docs/contributions/dependency-cycle-explanation.md)

## Scope

Keep the task timeline, existing phases, owners, progress and dependency model; avoid introducing a new scheduling system.

Size describes scope, not a promised completion time: **Small** = one focused interface change; **Medium** = coordinated interface/state work; **Large** = a feature across several flows, storage or export paths. All items are proposals, not claims that existing features are absent. Check the current code and extend what is there. Maintainers review code and tests before merging.

<!-- puredesktop-roadmap:dependency-cycle-explanation -->
