# Class 14

## CSS Transforms

1. What does a CSS transform allow the developer to do to an element?
* Lets us alter size, position and element in 2d or 3d space.
2. Provide an example of a transform and how you could see that being used on a website.
* Scale; it could be used on more important elements to draw the user's focus towards that area.

### 2D

**Rotate:** Rotates the element clockwise/counterclockwise.  (Hover box will rotate 360 degrees horizontally?)

**Scale:** Can alter the height and width of an element.  Can also specify `scaleY` or `scaleX` to alter one at time.

**Translate:** Pushes/pulls an element in a certain direction without disrupting flow of the document. Can also be designated with 'X' or 'Y' for more control.

...More added later

## CSS Transitions and Animations

1. What does a CSS transition allow the developer to do to an element?
* It allows us to morph some aspect of an element such as color, font, or spacing.  Things that can be incrementally changed.

2. How does a CSS animation differ from a CSS transition?
* Animations are required when more movements than one are required from an element.

### Transitions

**Transitional Property**: These determine what will be altered about an element. Examples include background, borders, font, padding, height, width, and more.

## Animations

**Animations Keyframes**: `@keyframes` is used to set the multiple points an element will transition.

It includes the animation name, properties, and breakpoints that need to be animated.

`@keyframes slide {
  0% {
    left: 0;
    top: 0;
  }
  50% {
    left: 244px;
    top: 100px;
  }
  100% {
    left: 488px;
    top: 0;
  }
}`

Source: [https://learn.shayhowe.com/advanced-html-css/transitions-animations/](https://learn.shayhowe.com/advanced-html-css/transitions-animations/)

... more later

1. What are some benefits to using CSS transitions on websites?
* Most of them seem to be designed around grabbing attention towards that element.  I think it also lends an air of modern design/professionalism to the site.

2. How this topic fit in with your long-term goals?
* I think that these are the kinds of tools that we really need to make our websites *look* like we're not just amateurs that picked up some html in our off-time.

### Things I want to know more about

I definitely need to run through the rest of the Transforms/Transitions/Animations properties and declarations so that I'm more familiar with what I can do.