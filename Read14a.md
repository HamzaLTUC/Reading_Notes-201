## Transforms :
The transform property allows us to visually manipulate an element by skewing, rotating, translating, or scaling:

### Values
`scale()`: \
Affects the size of the element. This also applies to the font-size, padding, height, and width of an element, too. It’s also a a shorthand function for the scaleX and scaleY functions.

`skewX()` and `skewY()`:
 Tilts an element to the left or right, like turning a rectangle into a parallelogram. `skew()` is a shorthand that combines `skewX()` and `skewY()` by accepting both values.

`translate()`: 
Moves an element sideways or up and down.
rotate(): Rotates the element clockwise from its current position.

`rotate()`:
  transformation that rotates an element around a fixed point on the 2D plane, without deforming it. Its result is a `<transform-function> `data type.

`perspective():`
 Doesn’t affect the element itself, but affects the transforms of descendent elements’ 3D transforms, allowing them all to have a consistent depth perspective.


## Transitions & Animations

*Transition* :\
alter the appearance and behavior of an element whenever a state change occurs, such as when it is hovered over, focused on, active, or targeted.

#### *There are four transition related properties in total, including:*

1.transition-property.\
used to define what property, or properties, you want to apply a transition effect to.

2.transition-duration\
 used to define the duration of a specified transition. That is, the length of time it will take for the targeted element to transition between two defined states.

3.transition-timing function \
is used to define a function that describes how a transition will proceed over its duration, allowing a transition to change speed during its course.

4.transition-delay\
used to define a length of time to delay the start of a transition.


Some of attractive properites we can use on hover  :\
1.Fade in \
2. Change color\
3. Grow & Shrink\
4. Rotate elements\
5. Square to circle\
6. 3D shadow \
7. Swing\
8. Inset border 

#### The Prefixes
Major browsers use the following prefixes:

-webkit- Chrome, Safari, newer versions of Opera, almost all iOS browsers.\
-moz- Firefox.\
-o- Old versions of Opera.\
-ms- Microsoft Edge and Internet Explorer.