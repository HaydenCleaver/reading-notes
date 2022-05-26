# Class 5 Reading Notes

### CSS (Cascading Style Sheets)

CSS is a language for styling how documents are presented to users.

Documents are usually text files structured using a markup language (such as HTML)

CSS can be used to for anything ranging from color and font size, to altering the layout of text areas.

***

### CSS Syntax

```
h1 {
    color: red;
    font-size: 5em;
}
```
In this case `h1` is the selector, `color` is the property, and `red` is the value.

### Ways to Insert CSS

1. External: Pulled from a .css document.
2. Internal: Defined inside the `<style>` element, which is in the `<head>` section of an HTML page.
3. Inline: Style attribute is added directly to an element.

Generally, the last read style will be the one that is applied. However, there is a hierarchy based upon the method used.

1. Inline style*
2. External and internal (whichever is read last)
3. Browser default

*do things referenced with id or class take precedent regardless of where they're located?

***

[Return to Table of Contents](https://haydencleaver.github.io/reading-notes/)