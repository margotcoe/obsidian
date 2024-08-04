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

sort file.name asc
```
```dataview
list
from [[]]
where !contains(file.path, "Templates")
or contains(file.outlinks, "Mountain Goats Associations")
sort file.name asc
```


```dataview
list links
from [[Mountain Goats Associations]]
```
