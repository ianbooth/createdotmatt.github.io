---
layout: glossary
title: Footer - Start
group: Basics
last-updated: 31-07-2013
---

##Tag

`<!--WDK:footer:start-->`

##Description

This is a required tag that starts the footer section of your template. Create's dynamic content is loaded between `<!--WDK:header:end-->` and `<!--WDK:footer:start-->`. 
For more information, please see the footer tutorial here.

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