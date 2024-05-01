---
BC-regex-note-field: up
BC-regex-note-regex: /regex-note/(\d|Test)
BC-regex-note-flags: i
---
Should match both `1` and `test`. Even though `Test` is title case, the `i` flag should still let it match.