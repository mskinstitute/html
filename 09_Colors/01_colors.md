# HTML Colors

HTML colors are specified with predefined color names, or with RGB, HEX, HSL, RGBA, or HSLA values.

## Color Names

In HTML, a color can be specified by using a color name:

- Tomato
- Orange
- DodgerBlue
- MediumSeaGreen
- Gray
- SlateBlue
- Violet
- LightGray

HTML supports 140 standard color names.

## Background Color

You can set the background color for HTML elements:

<h1 style="background-color:DodgerBlue;">MSK Institute</h1>
<p style="background-color:Tomato;">
Lorem ipsum dolor sit amet, consectetuer adipiscing elit, sed diam nonummy nibh euismod tincidunt ut laoreet dolore magna aliquam erat volutpat. Ut wisi enim ad minim veniam, quis nostrud exerci tation ullamcorper suscipit lobortis nisl ut aliquip ex ea commodo consequat.
</p>

### [Example](01_colors.html)
```html
<h1 style="background-color:DodgerBlue;">MSK Institute</h1>
<p style="background-color:Tomato;">Lorem ipsum...</p>
```

## Text Color

You can set the color of text:


<h1 style="color:Tomato;">MSK Institute</h1>
<p style="color:DodgerBlue;">Lorem ipsum dolor sit amet, consectetuer adipiscing elit, sed diam nonummy nibh euismod tincidunt ut laoreet dolore magna aliquam erat volutpat.</p>
<p style="color:MediumSeaGreen;">Ut wisi enim ad minim veniam, quis nostrud exerci tation ullamcorper suscipit lobortis nisl ut aliquip ex ea commodo consequat.</p>

### Example
```html
<h1 style="color:Tomato;">MSK Institute</h1>
<p style="color:DodgerBlue;">Lorem ipsum...</p>
<p style="color:MediumSeaGreen;">Ut wisi enim...</p>
```

## Border Color

You can set the color of borders:

<h1 style="border:2px solid Tomato;">MSK Institute</h1>
<h1 style="border:2px solid DodgerBlue;">MSK Institute</h1>
<h1 style="border:2px solid Violet;">MSK Institute</h1>

### Example
```html
<h1 style="border:2px solid Tomato;">MSK Institute</h1>
<h1 style="border:2px solid DodgerBlue;">MSK Institute</h1>
<h1 style="border:2px solid Violet;">MSK Institute</h1>
```

## Color Values

In HTML, colors can also be specified using RGB values, HEX values, HSL values, RGBA values, and HSLA values.

The following three `<div>` elements have their background color set with RGB, HEX, and HSL values:

<h1 style="background-color:rgb(255, 99, 71);">rgb(255, 99, 71)</h1>
<h1 style="background-color:#ff6347;">#ff6347</h1>
<h1 style="background-color:hsl(9, 100%, 64%);">hsl(9, 100%, 64%)</h1>

The following two `<div>` elements have their background color set with RGBA and HSLA values, which add an Alpha channel to the color (here we have 50% transparency):

<h1 style="background-color:rgba(255, 99, 71, 0.5);">rgba(255, 99, 71, 0.5)</h1>
<h1 style="background-color:hsla(9, 100%, 64%, 0.5);">hsla(9, 100%, 64%, 0.5)</h1>

### Example
```html
<h1 style="background-color:rgb(255, 99, 71);">MSK</h1>
<h1 style="background-color:#ff6347;">MSK</h1>
<h1 style="background-color:hsl(9, 100%, 64%);">MSK</h1>

<h1 style="background-color:rgba(255, 99, 71, 0.5);">MSK</h1>
<h1 style="background-color:hsla(9, 100%, 64%, 0.5);">MSK</h1>
```


# [<<<Back](../08_Comments/comment.md) : [Next>>>](../10_Style_CSS/style_css.md)
