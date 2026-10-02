# Find missing endpoints before importing edges

[GitHub issue #8](https://github.com/puredesktop/puregraph/issues/8) · Open · `roadmap`

## More improvements

6. **Find missing endpoints before importing edges.** For an edge referencing a missing node, report its row, source and target identifiers in the import preview before applying changes.
   <!-- contribution: {"id": "import-endpoint-diagnostics", "size": "medium", "goodFirstIssue": false, "guide": "docs/contributions/import-endpoint-diagnostics.md"} -->
   [Medium · Implementation brief](https://github.com/puredesktop/puregraph/blob/main/docs/contributions/import-endpoint-diagnostics.md)

## Scope

Keep graph data, existing layouts and encodings, and the current proposal-before-apply workflow.

Size describes scope, not a promised completion time: **Small** = one focused interface change; **Medium** = coordinated interface/state work; **Large** = a feature across several flows, storage or export paths. All items are proposals, not claims that existing features are absent. Check the current code and extend what is there. Maintainers review code and tests before merging.

<!-- puredesktop-roadmap:import-endpoint-diagnostics -->
