---
category:
  - "[[Podcasts]]"
host:
  - Angela Duckworth
rating: "4"
tags:
  - podcast
  - advice
---
## Episodes

```dataview
table without id
	link(file.link, "Ep. " + string(episode)) as Episode,
	guests as Guest,
	rating as Rating
where
	contains(category,[[Podcast episodes]]) and
	contains(show,this.file.link)
sort episode desc
```