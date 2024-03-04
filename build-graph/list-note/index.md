---
BC-list-note-field: up
BC-list-note-exclude-index:
---
Test list-notes. Should yield a binary tree going up.
If `BC-list-note-exclude-index` is truthy, then this note shouldn't also link up.

- [[build-graph/list-note/1|1]]
	- [[11]]
		- lines without links shouldn't cause issue
		- [[111]]
		- [[112]]
	- [[12]]
		- [[121]]
		- [[122]]
			- [[1221]]
			- [[1222]]
- [[build-graph/list-note/2|2]]
	- [[21]]
		- [[211]]
		- [[212]]
	- [[22]]
		- [[221]]
		- [[222]]
