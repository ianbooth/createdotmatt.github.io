---
layout: glossary
title: Page File Name Is
group: Conditional
last-updated: 31-07-2013
---


##Tag

`<!--WDK:if:pageFilenameIs:value-->`

##Description

This conditonal tag checks to see if the page filename is the specified value.

For more information, [please see the tutorial on conditional tags here.](/pages/tutorials/12conditional-tags.html)

Pseudo Equivalent: 
`if ( pageFilename == value ) {`

##Example

In the following example we're checking to see if we're on a page named contact, and then including a div for a map.

```
<!--WDK:if:pageFilenameIs:contact-->
	<div id="map"></div>
<!--WDK:endif-->
```

It is also worth noting that you can use a list of comma separated items.

`<!--WDK:if:pageFilenameIs:contact,home,about-->`