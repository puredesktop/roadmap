# Retry saving the current canvas

[GitHub issue #12](https://github.com/puredesktop/purewhiteboard/issues/12) · Open · `roadmap`

## More improvements

11. **Retry saving the current canvas.** Expose an explicit retry after a package write failure and keep the current canvas snapshot intact until it succeeds.
   <!-- contribution: {"id": "save-retry-action", "size": "medium", "goodFirstIssue": false, "guide": "docs/contributions/save-retry-action.md"} -->
   [Medium · Implementation brief](https://github.com/puredesktop/purewhiteboard/blob/main/docs/contributions/save-retry-action.md)

## Scope

Keep Excalidraw as the drawing surface, editable .whiteboard packages and the existing app-agent integration.

Size describes scope, not a promised completion time: **Small** = one focused interface change; **Medium** = coordinated interface/state work; **Large** = a feature across several flows, storage or export paths. All items are proposals, not claims that existing features are absent. Check the current code and extend what is there. Maintainers review code and tests before merging.

<!-- puredesktop-roadmap:save-retry-action -->
