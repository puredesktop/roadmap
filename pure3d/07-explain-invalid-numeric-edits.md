# Correct an invalid transform without losing it

[GitHub issue #8](https://github.com/puredesktop/pure3d/issues/8) · Open · `roadmap`

## More improvements

7. **Correct an invalid transform without losing it.** Keep an invalid transform draft visible with a nearby explanation instead of silently discarding it; identify non-finite values and non-positive scales before committing.
   <!-- contribution: {"id": "explain-invalid-numeric-edits", "size": "small", "goodFirstIssue": false, "guide": "docs/contributions/explain-invalid-numeric-edits.md"} -->
   [Small · Implementation brief](https://github.com/puredesktop/pure3d/blob/main/docs/contributions/explain-invalid-numeric-edits.md)

## Scope

Keep the scene, inspector and animation timeline workflow, the existing scene model and supported interchange formats.

Size describes scope, not a promised completion time: **Small** = one focused interface change; **Medium** = coordinated interface/state work; **Large** = a feature across several flows, storage or export paths. All items are proposals, not claims that existing features are absent. Check the current code and extend what is there. Maintainers review code and tests before merging.

<!-- puredesktop-roadmap:explain-invalid-numeric-edits -->
