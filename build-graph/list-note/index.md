---
BC-list-note-field: up
BC-list-note-exclude-index: false
BC-list-note-neighbour-field: next
---
Test list-notes. Should yield a binary tree going up.
If `BC-list-note-exclude-index` is truthy, then this note shouldn't also link up.

- [[build-graph/list-note/1|1]]
	- [[11]]
		- lines without links shouldn't cause issue
		- [[111]]
			- [[1111  long file name that makes the grid overflow alot with extra words]]
		- [[112]]
	- [[12]]
		- [[121]]
		- [[122]]
- [[build-graph/list-note/2|2]]
	- [[21]]
		- [[211]]
		- [[212]]
	- [[22]]
		- [[221]]
		- [[222]]

```breadcrumbs
field-groups: [ups]
```

```breadcrumbs
type: mermaid
fields: [up, down]
merge-fields: true
mermaid-direction: TB
show-attributes: [field]
```

