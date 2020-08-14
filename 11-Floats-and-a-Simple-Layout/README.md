# CSS Float and a Simple Layout

Generally `float` is a css property that floats element to left or right on the page. Understanding float and it's usage at the beginner stage can be confusing.

An important thing to be noticed:

> The float CSS property places an element on the left or right side of its container, allowing text and inline elements to wrap around it. The element is removed from the normal flow of the page, though still remaining a part of the flow (in contrast to absolute positioning).
> [Reference](https://developer.mozilla.org/en-US/docs/Web/CSS/float#:~:text=The%20float%20CSS%20property%20places,in%20contrast%20to%20absolute%20positioning)

#### Few ways to fix the problem

 - Use `overflow: hidden;` on the parent element.
 - If any other element is down below the floated element, use `clear: both;`
