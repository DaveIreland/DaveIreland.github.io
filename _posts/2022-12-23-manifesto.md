---
title: Manifesto
date: 2022-12-23 12:38:54 
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

## Some links to resources needed to get this far with Jekyll:
 
 * [Homelab - YouTube](https://www.youtube.com/watch?v=F8iOU1ci19Q)
 * [Homelab - associated documentation](//https://docs.technotim.live/posts/jekyll-docs-site/)
 * [Snippets in Visual Studio Code](https://code.visualstudio.com/docs/editor/userdefinedsnippets#_create-your-own-snippets)
 * [VS Code snippets to generate Markdown front matter](https://dev.to/ceceliacreates/use-vs-code-snippets-to-generate-markdown-front-matter-fpc)
 * [Jekyll Chirpy Theme](https://chirpy.cotes.page/)

## Other resources consulted

 * [Docker Cheat Sheet](https://docs.docker.com/get-started/docker_cheatsheet.pdf)