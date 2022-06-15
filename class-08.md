# Class 08

This reading provides one more tool for us to control the way that we want to present information to a user.  In this module it will be potentially useful for enhancing the visual experience of the homepage, and we may be able to use it for our data table on the sales page.

## Flexbox

Flexboxes allow you to utilize boxes which will automatically break on to a new line if there isn't enough room.

> * They can display as a row, or a column.
> * They respect the writing mode of the document.
> * They are single line by default, but can be asked to wrap onto multiple lines.
> * Items in the layout can be visually reordered, away from their order in the DOM.
> * Space can be distributed inside the items, so they become bigger and smaller according to the space available in their parent.
> * Space can be distributed around the items and flex lines in a wrapped layout, using the Box Alignment properties.
> * The items themselves can be aligned on the cross axis.

Source : [https://web.dev/learn/css/flexbox/](https://web.dev/learn/css/flexbox/)

### Main Axis and Cross Axis

Your main axis is determined by the `flex-direction`. If you have it set to `row` then that will be your main axis, but if it's set to `column` then that will be your current main axis.

The cross axis runs in whichever way the flex-direction does not.

Flex items move as a group when they're on the main axis, but can be moved individually or as a group on the corss axis.

## Layout

### Display

`display` lets us change whether or not a box acts as an inline object or block object.

This property will extend to any of its child elements as well.

You can also set it to `flex` to make something a block and change its children to flex items.

### More Flexbox and Grid

## Things I want to know about

CSS seems pretty simple so far, it's just more of a process of understanding what types of tools that you have and learning how you can apply them in different ways.

I think I just need to play around with it and maybe read more into a few of the things that `flex` can do.