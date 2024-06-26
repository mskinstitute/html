# HTML Ordered Lists
The HTML `<ol>` tag defines an ordered list. An ordered list can be numerical or alphabetical.

## Ordered HTML List
An ordered list starts with the `<ol>` tag. Each list item starts with the `<li>` tag.

The list items will be marked with numbers by default:
<ol>
    <li>Coffee</li>
    <li>Tea</li>
    <li>Milk</li>
</ol>

### Example
```html
<ol>
    <li>Coffee</li>
    <li>Tea</li>
    <li>Milk</li>
</ol>
```
## Ordered HTML List - The Type Attribute
The type attribute of the `<ol>` tag, defines the type of the list item marker:

### Type	Description
1. [type="1"](#)
1. [type="A"](#)
1. [type="a"](#)
1. [type="I"](#)
1. [type="i"](#)

### numbers
<ol type="1">
  <li>Coffee</li>
  <li>Tea</li>
  <li>Milk</li>
</ol>

```html
<ol type="1">
  <li>Coffee</li>
  <li>Tea</li>
  <li>Milk</li>
</ol>
```

### uppercase
<ol type="A">
  <li>Coffee</li>
  <li>Tea</li>
  <li>Milk</li>
</ol>

```html
<ol type="A">
  <li>Coffee</li>
  <li>Tea</li>
  <li>Milk</li>
</ol>
```

### lowercase
<ol type="a">
  <li>Coffee</li>
  <li>Tea</li>
  <li>Milk</li>
</ol>

```html
<ol type="a">
  <li>Coffee</li>
  <li>Tea</li>
  <li>Milk</li>
</ol>
```

### uppercase roman numbers:
<ol type="I">
  <li>Coffee</li>
  <li>Tea</li>
  <li>Milk</li>
</ol>


```html
<ol type="I">
  <li>Coffee</li>
  <li>Tea</li>
  <li>Milk</li>
</ol>
```
### Lowercase Roman Numbers:
<ol type="i">
  <li>Coffee</li>
  <li>Tea</li>
  <li>Milk</li>
</ol>

```html
<ol type="i">
  <li>Coffee</li>
  <li>Tea</li>
  <li>Milk</li>
</ol>
```

## Control List Counting

By default, an ordered list will start counting from 1. If you want to start counting from a specified number, you can use the start attribute:

### Example
<ol start="50">
  <li>Apple</li>
  <li>Banana</li>
  <li>Mango</li>
</ol>

```html
<ol start="50">
  <li>Apple</li>
  <li>Banana</li>
  <li>Mango</li>
</ol>
```
<ol type="A" start="6">
  <li>Papaya</li>
  <li>Grapes</li>
</ol>

```html
<ol type="A" start="3">
  <li>Pen</li>
  <li>Pencil</li>
</ol>
```

## Nested HTML Lists
Lists can be nested (list inside list):

### Example
```html
<ol>
  <li>Coffee</li>
  <li>Tea
    <ol>
      <li>Black tea</li>
      <li>Green tea</li>
    </ol>
  </li>
  <li>Milk</li>
</ol>
```
>Note: A list item (`<li>`) can contain a new list, and other HTML elements, like images and links, etc.


# [<<< Back](01_list.md)
