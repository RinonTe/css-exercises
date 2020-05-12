# CSS exercise 40: Shadows

There are two types of shadows:

1. Box Shadows, or the shadows that run around or inside a box
1. Text Shadwos, or the ghostly shadow outlines of text.

Let's do some research on these shadows…

1. `box-shadow` and `text-shadow` have very similar value syntax. Where do they differ?: we cannot use the inset and thickness keywords with the `text-shadow` whereas `box-shadow` does.
1. If I wanted to create a hard-edge shadow, one that looks like a solid border, what combination of values would I need to use? It would be better to use  the blur and thickness value.
1. Is it possible to create a shadow on a circular element? What about a polygon? The only possible way to do so is to use border-radius.
1. Is it possible to create multiple shadows on the same element?  Multiple shadows can be made using the same code that is used for making single shadow. To make these multiple shadows, we just need to define multiple shadow value and seperate them with a comma.
