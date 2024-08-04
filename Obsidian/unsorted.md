---
tags: 
Links:
---
- - -
no outgoing links (no home)
```dataview
table
from ""
where length(file.outlinks) = 0 and !contains(file.path, "Templates")
sort file.name asc
```

no incoming links (no data source)




- - -
`=this.file.ctime`