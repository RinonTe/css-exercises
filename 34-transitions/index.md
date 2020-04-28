# CSS exercise 34: Transitions

Transitions offer us the simplest form of animation in CSS.

The word *transition* means to 'change from one state to another'. In CSS, these transitions occur per element, per property.

1. The first state is the initial state, or how the element was to begin with.
1. The second state, or target state, is what the element will become.

Transitions take care of all the intermediate stages between those two states.

OK, so let's hunker down and learn more about transitions!

1. The `transition` property is a 'shorthand property'. What other properties are included in this shorthand property?
*These are the properties: transition-property, transition-duration, transition-timing-function, and transition-delay.*
1. What is the difference between a timing function, delay, and duration?
*duration sets the length of time a transition animation should take to complete, and function is how the values are calculated for CSS properties being affected by a transition effect, and delay specifies the duration to wait before starting the transition*
1. What CSS properties are *animatable* using transitions?
-moz-outline-radius
-moz-outline-radius-bottomleft
-moz-outline-radius-bottomright
-moz-outline-radius-topleft
-moz-outline-radius-topright
-webkit-line-clamp
-webkit-text-fill-color
-webkit-text-stroke
-webkit-text-stroke-color
all.
backdrop-filter
background
background-color
background-position
background-size
block-size
border
border-block-end
border-block-end-color
border-block-end-width
border-block-start
border-block-start-color
border-block-start-width
border-bottom
border-bottom-color
border-bottom-left-radius
border-bottom-right-radius
border-bottom-width
border-color
border-end-end-radius
border-end-start-radius
border-image-outset
border-image-slice
border-image-width
border-inline-end
border-inline-end-color
border-inline-end-width
border-inline-start
border-inline-start-color
border-inline-start-width
border-left
border-left-color
border-left-width
border-radius
border-right
border-right-color
border-right-width
border-start-end-radius
border-start-start-radius
border-top
border-top-color
border-top-left-radius
border-top-right-radius
border-top-width
border-width
bottom
box-shadow
caret-color
clip
clip-path
color
column-count
column-gap
column-rule
column-rule-color
column-rule-width
column-width
columns
filter
flex
flex-basis
flex-grow
flex-shrink
font
font-size
font-size-adjust
font-stretch
font-variation-settings
font-weight
gap
grid-column-gap
grid-gap
grid-row-gap
grid-template-columns
grid-template-rows
height
inline-size
inset
inset-block
inset-block-end
inset-block-start
inset-inline
inset-inline-end
inset-inline-start
left
letter-spacing
line-clamp
line-height
margin
margin-block-end
margin-block-start
margin-bottom
margin-inline-end
margin-inline-start
margin-left
margin-right
margin-top
mask
mask-border
mask-position
mask-size
max-block-size
max-height
max-inline-size
max-lines
max-width
min-block-size
min-height
min-inline-size
min-width
object-position
offset
offset-anchor
offset-distance
offset-path
offset-position
offset-rotate
opacity
order
outline
outline-color
outline-offset
outline-width
padding
padding-block-end
padding-block-start
padding-bottom
padding-inline-end
padding-inline-start
padding-left
padding-right
padding-top
perspective
perspective-origin
right
rotate
row-gap
scale
scroll-margin
scroll-margin-block
scroll-margin-block-end
scroll-margin-block-start
scroll-margin-bottom
scroll-margin-inline
scroll-margin-inline-end
scroll-margin-inline-start
scroll-margin-left
scroll-margin-right
scroll-margin-top
scroll-padding
scroll-padding-block
scroll-padding-block-end
scroll-padding-block-start
scroll-padding-bottom
scroll-padding-inline
scroll-padding-inline-end
scroll-padding-inline-start
scroll-padding-left
scroll-padding-right
scroll-padding-top
scroll-snap-coordinate
scroll-snap-destination
scrollbar-color
shape-image-threshold
shape-margin
shape-outside
tab-size
text-decoration
text-decoration-color
text-decoration-thickness
text-emphasis
text-emphasis-color
text-indent
text-shadow
text-underline-offset
top
transform
transform-origin
translate
vertical-align
visibility
width
word-spacing
z-index*

1. Can we select more than one property to transition at a time? If so, how?
1. How can we set or define the desired transition state, using CSS?
1. Do we need transitions? What makes them useful?
1. At what point can transitions become a problem?
1. Transitions don't work reliably with the `auto` keyword being one of the end states. Why is that?
1. How can we stagger transitions? i.e. make a number of child elements all start at different times?
