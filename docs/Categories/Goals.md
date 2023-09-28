---
tags:
  - categories
---
Author Newsletter
```dataview
table without id
	file.link as Goal,
	duedate as due,
	progress as progress,
	recur as recur
where
	contains(category,this.file.link) and
	!contains(file.name, "Template")
sort last desc
```

