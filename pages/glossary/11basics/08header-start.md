---
layout: glossary
title: Header - Start
group: Basics
last-updated: 31-07-2013
---

##Tag

`<!--WDK:header:start-->`

##Description

This is a required tag that starts the header section of your template.
For more information, please see the [header tutorial](pages/tutorials/08the-header.html).

##Example

```
<!--WDK:header:start-->
<html>
  <head></head>
  <body>
    <!--WDK:header:end-->

      Dynamic page content is automatically inserted here.

    <!--WDK:footer:start-->
    <!--WDK:display:sitefooter-->
  </body>
</html>
<!--WDK:footer:end-->
```