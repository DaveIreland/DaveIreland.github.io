---
title: Manifesto
date: 2022-12-23, 12:02:57
categories: [dummy]
tags: [info]
---

# Manifesto for Project

Some remarks about what is being developed.

Needed to create this VSCode snippet for the front matter in this file:

```json
"post frontmatter": {
		"prefix": "postFrontmatter",
		"body": [
		  "---",
		  "title: $1",
		  "date: $CURRENT_YEAR-$CURRENT_MONTH-$CURRENT_DATE $CURRENT_HOUR:$CURRENT_MINUTE:$CURRENT_SECOND",
		  "update: $2",
		  "categories: [$3]",
		  "tags: [$4]",
		  "---"
		],
		"description": "post frontmatter"
	  }

```