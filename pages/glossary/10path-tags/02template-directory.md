---
layout: glossary
title: Template Directory
group: Path Tags
last-updated: 07-02-2013
---

##Tag

`<!--WDK:path:template-->`

##Description

Use this tag to retreive the full relative url to your template directory.

##Example

In this example we're using the tag to include an external stylesheet named 'style.css', which is located in the same directory as 'index.html'.

```
<link rel="stylesheet" type="text/css" href="<!--WDK:path:template-->style.css" />
```