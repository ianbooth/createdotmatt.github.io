---
layout: glossary
title: Menu Text Colour
group: Customisation
last-updated: 08-03-2013
---

##Tag

`<!--WDK:display:menutxt-->`

##Description

Return `#<HEX>`
Use this tag to return a hex value of the menu text colour as specified on the "Colours" section on your Create "Design" screen.

##Example

In this example we're using the tag to set the `<a>` link colour of a menu using CSS set in the `<head>`.

```
<head>
  <style type="text/css">
    #menu {
      background-color:<!--WDK:display:menubg-->;
    }
    #menu a {
      color:<!--WDK:display:menutxt-->;
    }
  </style>
</head>

<body>
  <div id="menu">
    <ul>
      <li><a href="URL">Menu Text</a></li>
    </ul>
  </div>
</body>
```