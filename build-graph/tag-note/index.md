---
BC-tag-note-tag: "#tag-note"
BC-tag-note-field: right
BC-tag-note-exact:
---
[[build-graph/tag-note/b]] has `#tag-note`, and [[build-graph/tag-note/c]] has `#tag-note/sub`.
If using Obsidian files (not Dataview) AND `BC-tag-note-exact` is truthy, then this file should point `up` to only [[build-graph/tag-note/b]].
However, if `BC-tag-note-exact` is falsey, or using Dataview files, then this note should point up to both [[build-graph/tag-note/b]] and [[build-graph/tag-note/c]] (directly)
