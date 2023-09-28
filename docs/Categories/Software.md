- [ ] todo: build software query
```dataview
table without id
	file.link as Software,
	language as Language,
	rating as Rating
where
	contains(category, this.file.link) and
	!contains(file.name, "Template")
sort last desc
```

