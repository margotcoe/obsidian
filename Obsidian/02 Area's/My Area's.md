---
tags:
  - area
Links:
  - "[[My Area's]]"
---
- - -
```dataview
list
from [[]]
where !contains(file.path, "Templates")
where !contains(file.path, "My Area's")
sort file.name asc
```
## Related Projects

```dataview
table Status, Date
from [[]] and #project 
```