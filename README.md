# modernui
Modernui is a css3 framework that makes it easier and faster to develop webapps. It was inspired by the Windows phone.
## How to use / geting startet
Just look in the demo.html file to get startet with the full version, or look in the demo-for-minified.html to get startet with the minified version.
To embed the full version, add this thing in your head section:
```html
<link rel="stylesheet" href="./css/modernui.css">
```

To embed the minified version, just linking the file like that:

```html
<link rel="stylesheet" href="./css/modernui.min.css">
```
## A few words about the versions
Some classes are missing in the minified version. These are the following:

### text-floating
- adds floating effect to the text

### tile-shadow
- adds an shadow to the boxes

### color2
- the second color for the boxes

## Docs
Here are the docs:
### classes
embed it with class="CLASSNAME"
- phone
- -    a class for testing it on phones, not in the minified version
- text-floating
- -    a class for a floating effect, not in the minified version; only for WebKit browsers (like chrome, firefox, or internet explorer 10+)
- tile
 - -   adds a box for the element, mor information below
### tile class docs
Syntax:
```html
<section class="tile attribute1 attribute2 attribute3 ...">
```
Attributes:
- x{X}
- -  width of an element; replace {X} with 1,2 or 4
- y{Y}
- -  height of an element; replace {Y} with 1 or 2
- tile-shadow
- -  adds an shadow to the tile; doesnt exist in the minified version
- color2
- -  an other color for the tile; doesnt exist in the minified version
