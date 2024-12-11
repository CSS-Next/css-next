# CSS4

## Align

| Property                                                                            | Description                                                                                                        |
|-------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------|
| [align-content](https://developer.mozilla.org/en-US/docs/Web/CSS/align-content)     | Aligns flex container's lines within the flex container when there is extra space on the cross-axis                |
| [align-items](https://developer.mozilla.org/en-US/docs/Web/CSS/align-items)         | Sets the align-self value on all direct children as a group                                                        |
| [align-self](https://developer.mozilla.org/en-US/docs/Web/CSS/align-self)           | Overrides a grid or flex item's align-items value                                                                  |
| [gap](https://developer.mozilla.org/en-US/docs/Web/CSS/gap)                         | Sets the gaps (gutters) between rows and columns                                                                   |
| [justify-content](https://developer.mozilla.org/en-US/docs/Web/CSS/justify-content) | Defines how the browser distributes space between and around content items along the main-axis of a flex container |
| [justify-items](https://developer.mozilla.org/en-US/docs/Web/CSS/justify-items)     | Defines the default justify-self for all items of the box                                                          |
| [justify-self](https://developer.mozilla.org/en-US/docs/Web/CSS/justify-self)       | Sets the way a box is justified inside its alignment container along the appropriate axis                          |
| [order](https://developer.mozilla.org/en-US/docs/Web/CSS/order)                     | Sets the order to lay out an item in a flex or grid container                                                      |
| [place-content](https://developer.mozilla.org/en-US/docs/Web/CSS/place-content)     | Sets both the align-content and justify-content properties in a single declaration                                 |
| [place-items](https://developer.mozilla.org/en-US/docs/Web/CSS/place-items)         | Sets both the align-items and justify-items properties in a single declaration                                     |
| [place-self](https://developer.mozilla.org/en-US/docs/Web/CSS/place-self)           | Sets both the align-self and justify-self properties in a single declaration                                       |
| [row-gap](https://developer.mozilla.org/en-US/docs/Web/CSS/row-gap)                 | Sets the size of the gap between an element's grid rows                                                            |

## Animation

| Property                                                                        | Description                                                                          |
|---------------------------------------------------------------------------------|--------------------------------------------------------------------------------------|
| Animate grid tracks                                                             | CSS feature for animating grid track sizes                                           |
| [offset](https://developer.mozilla.org/en-US/docs/Web/CSS/offset)               | Shorthand for animating an element along a defined path                              |
| [ray()](https://developer.mozilla.org/en-US/docs/Web/CSS/ray)                   | Defines a ray function for use with the offset-path property                         |
| [transform-box](https://developer.mozilla.org/en-US/docs/Web/CSS/transform-box) | Defines the layout box to which the transform and transform-origin properties relate |
| [will-change](https://developer.mozilla.org/en-US/docs/Web/CSS/will-change)     | Hints to browsers how an element is expected to change                               |

## At-rules

| Property                                                                                    | Description                                                         |
|---------------------------------------------------------------------------------------------|---------------------------------------------------------------------|
| [@forced-colors](https://developer.mozilla.org/en-US/docs/Web/CSS/@media/forced-colors)     | Detects whether the user agent has limited the color palette        |
| @media range-syntax                                                                         | Allows for more flexible media query ranges                         |
| [@supports](https://developer.mozilla.org/en-US/docs/Web/CSS/@supports)                     | Tests if the browser supports a particular CSS feature              |
| [forced-color-adjust](https://developer.mozilla.org/en-US/docs/Web/CSS/forced-color-adjust) | Allows authors to opt particular elements out of forced colors mode |

## Blend Modes

| Property                                                                | Description                                                   |
|-------------------------------------------------------------------------|---------------------------------------------------------------|
| [isolation](https://developer.mozilla.org/en-US/docs/Web/CSS/isolation) | Defines whether an element must create a new stacking context |

## Clipping, shapes & masking

| Property                                                                                        | Description                                                                 |
|-------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------|
| [circle()](https://developer.mozilla.org/en-US/docs/Web/CSS/basic-shape/circle)                 | Defines a circle as a basic shape                                           |
| [clip-path](https://developer.mozilla.org/en-US/docs/Web/CSS/clip-path)                         | Creates a clipping region that sets what part of an element should be shown |
| [ellipse()](https://developer.mozilla.org/en-US/docs/Web/CSS/basic-shape/ellipse)               | Defines an ellipse as a basic shape                                         |
| [mask-mode](https://developer.mozilla.org/en-US/docs/Web/CSS/mask-mode)                         | Specifies how the mask layer image is interpreted                           |
| [shape-image-threshold](https://developer.mozilla.org/en-US/docs/Web/CSS/shape-image-threshold) | Defines the alpha channel threshold used to extract a shape from an image   |
| [shape-margin](https://developer.mozilla.org/en-US/docs/Web/CSS/shape-margin)                   | Adds a margin to a shape-outside                                            |
| [shape-outside](https://developer.mozilla.org/en-US/docs/Web/CSS/shape-outside)                 | Defines a shape around which adjacent inline content should wrap            |

## Contain

| Property                                                            | Description                                                                                                       |
|---------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------|
| [contain](https://developer.mozilla.org/en-US/docs/Web/CSS/contain) | Indicates that an element and its contents are, as much as possible, independent of the rest of the document tree |

## Counter

| Property                                                                                              | Description                                                          |
|-------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------|
| [@counter-style](https://developer.mozilla.org/en-US/docs/Web/CSS/@counter-style)                     | Defines a custom counter style                                       |
| [counter-set](https://developer.mozilla.org/en-US/docs/Web/CSS/counter-set)                           | Sets a CSS counter to a given value                                  |
| [fallback (@counter-style)](https://developer.mozilla.org/en-US/docs/Web/CSS/@counter-style/fallback) | Specifies a fallback counter style                                   |
| [suffix (@counter-style)](https://developer.mozilla.org/en-US/docs/Web/CSS/@counter-style/suffix)     | Specifies content that comes after the marker value                  |
| [symbols (@counter-style)](https://developer.mozilla.org/en-US/docs/Web/CSS/@counter-style/symbols)   | Specifies the symbols used by the marker                             |
| [symbols()](https://developer.mozilla.org/en-US/docs/Web/CSS/symbols)                                 | Allows defining a custom counter style inline                        |
| [system (@counter-style)](https://developer.mozilla.org/en-US/docs/Web/CSS/@counter-style/system)     | Defines the algorithm used to construct the counter's representation |

## Flex

| Property                                                                          | Description                                                                           |
|-----------------------------------------------------------------------------------|---------------------------------------------------------------------------------------|
| [flex](https://developer.mozilla.org/en-US/docs/Web/CSS/flex)                     | Shorthand property for flex-grow, flex-shrink, and flex-basis                         |
| flex_value#fr                                                                     | Specifies a flexible length                                                           |
| [flex-basis](https://developer.mozilla.org/en-US/docs/Web/CSS/flex-basis)         | Specifies the initial main size of a flex item                                        |
| [flex-direction](https://developer.mozilla.org/en-US/docs/Web/CSS/flex-direction) | Specifies how flex items are placed in the flex container                             |
| [flex-flow](https://developer.mozilla.org/en-US/docs/Web/CSS/flex-flow)           | Shorthand property for flex-direction and flex-wrap                                   |
| [flex-grow](https://developer.mozilla.org/en-US/docs/Web/CSS/flex-grow)           | Specifies how much a flex item will grow relative to the rest of the flex items       |
| [flex-shrink](https://developer.mozilla.org/en-US/docs/Web/CSS/flex-shrink)       | Specifies how much a flex item will shrink relative to the rest of the flex items     |
| [flex-wrap](https://developer.mozilla.org/en-US/docs/Web/CSS/flex-wrap)           | Specifies whether flex items are forced onto one line or can wrap onto multiple lines |

## Functions

| Property                                                                               | Description                                                                     |
|----------------------------------------------------------------------------------------|---------------------------------------------------------------------------------|
| [clamp()](https://developer.mozilla.org/en-US/docs/Web/CSS/clamp)                      | Clamps a value between an upper and lower bound                                 |
| [env()](https://developer.mozilla.org/en-US/docs/Web/CSS/env)                          | Inserts the value of a user agent-defined environment variable                  |
| [fit-content](https://developer.mozilla.org/en-US/docs/Web/CSS/fit-content)            | Sets the size of a box to fit its content                                       |
| [fit-content()](https://developer.mozilla.org/en-US/docs/Web/CSS/fit-content_function) | Clamps a given size to an available size                                        |
| [max()](https://developer.mozilla.org/en-US/docs/Web/CSS/max)                          | Returns the largest of a list of values                                         |
| [min()](https://developer.mozilla.org/en-US/docs/Web/CSS/min)                          | Returns the smallest of a list of values                                        |
| [minmax()](https://developer.mozilla.org/en-US/docs/Web/CSS/minmax)                    | Defines a size range greater than or equal to min and less than or equal to max |
| [repeat()](https://developer.mozilla.org/en-US/docs/Web/CSS/repeat)                    | Represents a repeated fragment of the track list                                |
| [var(), --*](https://developer.mozilla.org/en-US/docs/Web/CSS/var)                     | Inserts the value of a custom property                                          |

## Gradient

| Property                                                                                     | Description              |
|----------------------------------------------------------------------------------------------|--------------------------|
| [conic-gradient()](https://developer.mozilla.org/en-US/docs/Web/CSS/gradient/conic-gradient) | Creates a conic gradient |

## Grid

| Property                                                                                        | Description                                                                      |
|-------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------|
| [grid](https://developer.mozilla.org/en-US/docs/Web/CSS/grid)                                   | Shorthand property for defining grid columns, rows, and areas                    |
| [grid-area](https://developer.mozilla.org/en-US/docs/Web/CSS/grid-area)                         | Specifies a grid item's size and location within a grid                          |
| [grid-auto-columns](https://developer.mozilla.org/en-US/docs/Web/CSS/grid-auto-columns)         | Specifies the size of implicitly-created grid columns                            |
| [grid-auto-flow](https://developer.mozilla.org/en-US/docs/Web/CSS/grid-auto-flow)               | Controls how the auto-placement algorithm works                                  |
| [grid-auto-rows](https://developer.mozilla.org/en-US/docs/Web/CSS/grid-auto-rows)               | Specifies the size of implicitly-created grid rows                               |
| [grid-column](https://developer.mozilla.org/en-US/docs/Web/CSS/grid-column)                     | Shorthand for grid-column-start and grid-column-end                              |
| [grid-column-end](https://developer.mozilla.org/en-US/docs/Web/CSS/grid-column-end)             | Specifies where a grid item ends                                                 |
| [grid-column-start](https://developer.mozilla.org/en-US/docs/Web/CSS/grid-column-start)         | Specifies where a grid item begins                                               |
| [grid-row](https://developer.mozilla.org/en-US/docs/Web/CSS/grid-row)                           | Shorthand for grid-row-start and grid-row-end                                    |
| [grid-row-end](https://developer.mozilla.org/en-US/docs/Web/CSS/grid-row-end)                   | Specifies where a grid item ends                                                 |
| [grid-row-start](https://developer.mozilla.org/en-US/docs/Web/CSS/grid-row-start)               | Specifies where a grid item begins                                               |
| [grid-template](https://developer.mozilla.org/en-US/docs/Web/CSS/grid-template)                 | Shorthand for grid-template-rows, grid-template-columns, and grid-template-areas |
| [grid-template-areas](https://developer.mozilla.org/en-US/docs/Web/CSS/grid-template-areas)     | Specifies named grid areas                                                       |
| [grid-template-columns](https://developer.mozilla.org/en-US/docs/Web/CSS/grid-template-columns) | Defines the columns of the grid                                                  |
| [grid-template-rows](https://developer.mozilla.org/en-US/docs/Web/CSS/grid-template-rows)       | Defines the rows of the grid                                                     |
| [Subgrid](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_grid_layout/Subgrid)             | Allows a grid item to create its own grid tracks that align to its parent grid   |

## Image / Video

| Property                                                                                | Description                                                                    |
|-----------------------------------------------------------------------------------------|--------------------------------------------------------------------------------|
| [aspect-ratio](https://developer.mozilla.org/en-US/docs/Web/CSS/aspect-ratio)           | Sets a preferred aspect ratio for the box                                      |
| [cross-fade()](https://developer.mozilla.org/en-US/docs/Web/CSS/cross-fade)             | Blends two or more images at a defined transparency                            |
| [image-orientation](https://developer.mozilla.org/en-US/docs/Web/CSS/image-orientation) | Specifies a layout-independent rotation to be applied to an image              |
| [image-resolution](https://developer.mozilla.org/en-US/docs/Web/CSS/image-resolution)   | Specifies the intrinsic resolution of all raster images used in/on the element |
| [image-set()](https://developer.mozilla.org/en-US/docs/Web/CSS/image/image-set)         | Allows the author to provide multiple resolutions of an image                  |

## Logical Properties

| Property                                                                                                  | Description                                                                                                |
|-----------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------|
| [block-size](https://developer.mozilla.org/en-US/docs/Web/CSS/block-size)                                 | Defines the horizontal or vertical size of an element's block                                              |
| [border-block](https://developer.mozilla.org/en-US/docs/Web/CSS/border-block)                             | Shorthand property for border-block-width, border-block-style, and border-block-color                      |
| [border-block-color](https://developer.mozilla.org/en-US/docs/Web/CSS/border-block-color)                 | Defines the color of the logical block borders                                                             |
| [border-block-end](https://developer.mozilla.org/en-US/docs/Web/CSS/border-block-end)                     | Shorthand property for border-block-end-width, border-block-end-style, and border-block-end-color          |
| [border-block-end-color](https://developer.mozilla.org/en-US/docs/Web/CSS/border-block-end-color)         | Defines the color of the logical block-end border                                                          |
| [border-block-end-style](https://developer.mozilla.org/en-US/docs/Web/CSS/border-block-end-style)         | Defines the style of the logical block-end border                                                          |
| [border-block-end-width](https://developer.mozilla.org/en-US/docs/Web/CSS/border-block-end-width)         | Defines the width of the logical block-end border                                                          |
| [border-block-start](https://developer.mozilla.org/en-US/docs/Web/CSS/border-block-start)                 | Shorthand property for border-block-start-width, border-block-start-style, and border-block-start-color    |
| [border-block-start-color](https://developer.mozilla.org/en-US/docs/Web/CSS/border-block-start-color)     | Defines the color of the logical block-start border                                                        |
| [border-block-start-style](https://developer.mozilla.org/en-US/docs/Web/CSS/border-block-start-style)     | Defines the style of the logical block-start border                                                        |
| [border-block-start-width](https://developer.mozilla.org/en-US/docs/Web/CSS/border-block-start-width)     | Defines the width of the logical block-start border                                                        |
| [border-block-style](https://developer.mozilla.org/en-US/docs/Web/CSS/border-block-style)                 | Defines the style of the logical block borders                                                             |
| [border-block-width](https://developer.mozilla.org/en-US/docs/Web/CSS/border-block-width)                 | Defines the width of the logical block borders                                                             |
| [border-end-end-radius](https://developer.mozilla.org/en-US/docs/Web/CSS/border-end-end-radius)           | Defines the logical border radius of the end-end corner                                                    |
| [border-end-start-radius](https://developer.mozilla.org/en-US/docs/Web/CSS/border-end-start-radius)       | Defines the logical border radius of the end-start corner                                                  |
| [border-inline](https://developer.mozilla.org/en-US/docs/Web/CSS/border-inline)                           | Shorthand property for border-inline-width, border-inline-style, and border-inline-color                   |
| [border-inline-color](https://developer.mozilla.org/en-US/docs/Web/CSS/border-inline-color)               | Defines the color of the logical inline borders                                                            |
| [border-inline-end](https://developer.mozilla.org/en-US/docs/Web/CSS/border-inline-end)                   | Shorthand property for border-inline-end-width, border-inline-end-style, and border-inline-end-color       |
| [border-inline-end-color](https://developer.mozilla.org/en-US/docs/Web/CSS/border-inline-end-color)       | Defines the color of the logical inline-end border                                                         |
| [border-inline-end-style](https://developer.mozilla.org/en-US/docs/Web/CSS/border-inline-end-style)       | Defines the style of the logical inline-end border                                                         |
| [border-inline-end-width](https://developer.mozilla.org/en-US/docs/Web/CSS/border-inline-end-width)       | Defines the width of the logical inline-end border                                                         |
| [border-inline-start](https://developer.mozilla.org/en-US/docs/Web/CSS/border-inline-start)               | Shorthand property for border-inline-start-width, border-inline-start-style, and border-inline-start-color |
| [border-inline-start-color](https://developer.mozilla.org/en-US/docs/Web/CSS/border-inline-start-color)   | Defines the color of the logical inline-start border                                                       |
| [border-inline-start-style](https://developer.mozilla.org/en-US/docs/Web/CSS/border-inline-start-style)   | Defines the style of the logical inline-start border                                                       |
| [border-inline-start-width](https://developer.mozilla.org/en-US/docs/Web/CSS/border-inline-start-width)   | Defines the width of the logical inline-start border                                                       |
| [border-inline-style](https://developer.mozilla.org/en-US/docs/Web/CSS/border-inline-style)               | Defines the style of the logical inline borders                                                            |
| [border-inline-width](https://developer.mozilla.org/en-US/docs/Web/CSS/border-inline-width)               | Defines the width of the logical inline borders                                                            |
| [border-start-end-radius](https://developer.mozilla.org/en-US/docs/Web/CSS/border-start-end-radius)       | Defines the logical border radius of the start-end corner                                                  |
| [border-start-start-radius](https://developer.mozilla.org/en-US/docs/Web/CSS/border-start-start-radius)   | Defines the logical border radius of the start-start corner                                                |
| [float](https://developer.mozilla.org/en-US/docs/Web/CSS/float)                                           | Places an element on the left or right side of its container (start / end values)                          |
| [inline-size](https://developer.mozilla.org/en-US/docs/Web/CSS/inline-size)                               | Defines the horizontal or vertical size of an element's block, depending on its writing mode               |
| [margin-block](https://developer.mozilla.org/en-US/docs/Web/CSS/margin-block)                             | Shorthand property for margin-block-start and margin-block-end                                             |
| [margin-block-end](https://developer.mozilla.org/en-US/docs/Web/CSS/margin-block-end)                     | Defines the logical block end margin of an element                                                         |
| [margin-block-start](https://developer.mozilla.org/en-US/docs/Web/CSS/margin-block-start)                 | Defines the logical block start margin of an element                                                       |
| [margin-inline](https://developer.mozilla.org/en-US/docs/Web/CSS/margin-inline)                           | Shorthand property for margin-inline-start and margin-inline-end                                           |
| [margin-inline-end](https://developer.mozilla.org/en-US/docs/Web/CSS/margin-inline-end)                   | Defines the logical inline end margin of an element                                                        |
| [margin-inline-start](https://developer.mozilla.org/en-US/docs/Web/CSS/margin-inline-start)               | Defines the logical inline start margin of an element                                                      |
| [max-block-size](https://developer.mozilla.org/en-US/docs/Web/CSS/max-block-size)                         | Defines the maximum horizontal or vertical size of an element's block, depending on its writing mode       |
| [max-inline-size](https://developer.mozilla.org/en-US/docs/Web/CSS/max-inline-size)                       | Defines the maximum horizontal or vertical size of an element's block, depending on its writing mode       |
| [min-block-size](https://developer.mozilla.org/en-US/docs/Web/CSS/min-block-size)                         | Defines the minimum horizontal or vertical size of an element's block, depending on its writing mode       |
| [min-inline-size](https://developer.mozilla.org/en-US/docs/Web/CSS/min-inline-size)                       | Defines the minimum horizontal or vertical size of an element's block, depending on its writing mode       |
| [overflow-block](https://developer.mozilla.org/en-US/docs/Web/CSS/overflow-block)                         | Specifies how to handle content that overflows the block axis of the element's box                         |
| [overflow-inline](https://developer.mozilla.org/en-US/docs/Web/CSS/overflow-inline)                       | Specifies how to handle content that overflows the inline axis of the element's box                        |
| [overscroll-behavior-block](https://developer.mozilla.org/en-US/docs/Web/CSS/overscroll-behavior-block)   | Specifies the browser's behavior when the block direction boundary of a scrolling area is reached          |
| [overscroll-behavior-inline](https://developer.mozilla.org/en-US/docs/Web/CSS/overscroll-behavior-inline) | Specifies the browser's behavior when the inline direction boundary of a scrolling area is reached         |
| [padding-block](https://developer.mozilla.org/en-US/docs/Web/CSS/padding-block)                           | Shorthand property for padding-block-start and padding-block-end                                           |
| [padding-block-end](https://developer.mozilla.org/en-US/docs/Web/CSS/padding-block-end)                   | Defines the padding of the logical block end of an element                                                 |
| [padding-block-start](https://developer.mozilla.org/en-US/docs/Web/CSS/padding-block-start)               | Defines the padding of the logical block start of an element                                               |
| [padding-inline](https://developer.mozilla.org/en-US/docs/Web/CSS/padding-inline)                         | Shorthand property for padding-inline-start and padding-inline-end                                         |
| [padding-inline-end](https://developer.mozilla.org/en-US/docs/Web/CSS/padding-inline-end)                 | Defines the padding of the logical inline end of an element                                                |
| [padding-inline-start](https://developer.mozilla.org/en-US/docs/Web/CSS/padding-inline-start)             | Defines the padding of the logical inline start of an element                                              |
| [text-align](https://developer.mozilla.org/en-US/docs/Web/CSS/text-align)                                 | Specifies the horizontal alignment of text (start / end values)                                            |
| [writing-mode](https://developer.mozilla.org/en-US/docs/Web/CSS/writing-mode)                             | Defines whether lines of text are laid out horizontally or vertically                                      |

## Misc

| Property                                                                      | Description                                                                                                                            |
|-------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------|
| [all](https://developer.mozilla.org/en-US/docs/Web/CSS/all)                   | Resets all properties (except unicode-bidi and direction)                                                                              |
| caret                                                                         | Specifies the appearance of the text input cursor                                                                                      |
| [caret-color](https://developer.mozilla.org/en-US/docs/Web/CSS/caret-color)   | Specifies the color of the text input cursor                                                                                           |
| caret-shape                                                                   | Specifies the shape of the text input cursor                                                                                           |
| [touch-action](https://developer.mozilla.org/en-US/docs/Web/CSS/touch-action) | Specifies how a given region can be manipulated by a touchscreen user                                                                  |
| [unset](https://developer.mozilla.org/en-US/docs/Web/CSS/unset)               | Resets a property to its inherited value if it inherits, or to its initial value if not                                                |
| [user-select](https://developer.mozilla.org/en-US/docs/Web/CSS/user-select)   | Controls whether the user can select text                                                                                              |
| [revert](https://developer.mozilla.org/en-US/docs/Web/CSS/revert)             | Reverts the cascaded value of the property from its current value to the value the property would have had if no changes had been made |

## Print

| Property                                                                                            | Description                                                                            |
|-----------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------|
| [page-orientation (@page)](https://developer.mozilla.org/en-US/docs/Web/CSS/@page/page-orientation) | Specifies the orientation of the page box                                              |
| [print-color-adjust](https://developer.mozilla.org/en-US/docs/Web/CSS/print-color-adjust)           | Specifies how user agents should optimize the presentation of the element when printed |

## Pseudo-classes

| Property                                                                          | Description                                                                                                                              |
|-----------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------|
| [:current](https://developer.mozilla.org/en-US/docs/Web/CSS/:current)             | Represents the element or ancestor of the element that is currently being displayed                                                      |
| [:defined](https://developer.mozilla.org/en-US/docs/Web/CSS/:defined)             | Matches any element that has been defined, including built-in elements and custom elements                                               |
| [:dir](https://developer.mozilla.org/en-US/docs/Web/CSS/:dir)                     | Matches elements based on the directionality of the text contained in them                                                               |
| [:focus-visible](https://developer.mozilla.org/en-US/docs/Web/CSS/:focus-visible) | Matches when an element receives focus and the user agent determines via heuristics that the focus should be made evident on the element |
| [:focus-within](https://developer.mozilla.org/en-US/docs/Web/CSS/:focus-within)   | Matches an element if the element or any of its descendants are focused                                                                  |
| [:fullscreen](https://developer.mozilla.org/en-US/docs/Web/CSS/:fullscreen)       | Matches every element which is currently in full-screen mode                                                                             |
| [:future](https://developer.mozilla.org/en-US/docs/Web/CSS/:future)               | Represents any element that is defined to occur entirely after a :current element                                                        |
| [:host-context()](https://developer.mozilla.org/en-US/docs/Web/CSS/:host-context) | Matches a shadow host when it or any of its ancestors matches the given selector                                                         |
| [:host()](https://developer.mozilla.org/en-US/docs/Web/CSS/:host_function)        | Matches the shadow host of a shadow DOM containing the CSS it is used inside                                                             |
| [:paused](https://developer.mozilla.org/en-US/docs/Web/CSS/:paused)               | Represents a media element that is capable of playing when that element is paused                                                        |
| [:playing](https://developer.mozilla.org/en-US/docs/Web/CSS/:playing)             | Represents a media element that is capable of playing when that element is playing                                                       |
| [:user-invalid](https://developer.mozilla.org/en-US/docs/Web/CSS/:user-invalid)   | Represents an element with incorrect input, but only after the user has interacted with it                                               |
| [:user-valid](https://developer.mozilla.org/en-US/docs/Web/CSS/:user-valid)       | Represents an element with correct input, but only after the user has interacted with it                                                 |

## Pseudo-elements

| Property                                                                      | Description                                                                                                          |
|-------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------|
| [::backdrop](https://developer.mozilla.org/en-US/docs/Web/CSS/::backdrop)     | A box the size of the viewport which is rendered immediately beneath any element being presented in full-screen mode |
| [::cue](https://developer.mozilla.org/en-US/docs/Web/CSS/::cue)               | Matches WebVTT cues within a selected element                                                                        |
| [::cue-region](https://developer.mozilla.org/en-US/docs/Web/CSS/::cue-region) | Matches WebVTT cue regions within a selected element                                                                 |
| [::part](https://developer.mozilla.org/en-US/docs/Web/CSS/::part)             | Represents any element within a shadow tree that has a matching part attribute                                       |
| [::slotted](https://developer.mozilla.org/en-US/docs/Web/CSS/::slotted)       | Matches any content that is inserted into a slot                                                                     |

## Relative units

| Property                                                                                                       | Description                                                                                       |
|----------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------|
| [length#vb](https://developer.mozilla.org/en-US/docs/Web/CSS/length#relative_length_units_based_on_viewport)   | 1% of the size of the initial containing block in the direction of the root element's block axis  |
| [length#vh](https://developer.mozilla.org/en-US/docs/Web/CSS/length#relative_length_units_based_on_viewport)   | 1% of the viewport's height                                                                       |
| [length#vi](https://developer.mozilla.org/en-US/docs/Web/CSS/length#relative_length_units_based_on_viewport)   | 1% of the size of the initial containing block in the direction of the root element's inline axis |
| [length#vmax](https://developer.mozilla.org/en-US/docs/Web/CSS/length#relative_length_units_based_on_viewport) | 1% of the viewport's larger dimension                                                             |
| [length#vmin](https://developer.mozilla.org/en-US/docs/Web/CSS/length#relative_length_units_based_on_viewport) | 1% of the viewport's smaller dimension                                                            |
| [length#vw](https://developer.mozilla.org/en-US/docs/Web/CSS/length#relative_length_units_based_on_viewport)   | 1% of the viewport's width                                                                        |

## Scroll

| Property                                                                                                    | Description                                                                                                     |
|-------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------|
| [overflow-anchor](https://developer.mozilla.org/en-US/docs/Web/CSS/overflow-anchor)                         | Specifies whether the browser should move the content to avoid the viewport                                     |
| [overscroll-behavior](https://developer.mozilla.org/en-US/docs/Web/CSS/overscroll-behavior)                 | Sets what a browser does when reaching the boundary of a scrolling area                                         |
| [overscroll-behavior-x](https://developer.mozilla.org/en-US/docs/Web/CSS/overscroll-behavior-x)             | Sets the browser's behavior when the horizontal boundary of a scrolling area is reached                         |
| [overscroll-behavior-y](https://developer.mozilla.org/en-US/docs/Web/CSS/overscroll-behavior-y)             | Sets the browser's behavior when the vertical boundary of a scrolling area is reached                           |
| [scroll-behavior](https://developer.mozilla.org/en-US/docs/Web/CSS/scroll-behavior)                         | Specifies the scrolling behavior for a scrolling box                                                            |
| [scroll-margin](https://developer.mozilla.org/en-US/docs/Web/CSS/scroll-margin)                             | Shorthand property for scroll-margin-top, scroll-margin-right, scroll-margin-bottom, and scroll-margin-left     |
| [scroll-margin-block](https://developer.mozilla.org/en-US/docs/Web/CSS/scroll-margin-block)                 | Shorthand property for scroll-margin-block-start and scroll-margin-block-end                                    |
| [scroll-margin-block-end](https://developer.mozilla.org/en-US/docs/Web/CSS/scroll-margin-block-end)         | Defines the margin of the scroll snap area at the end of the block dimension                                    |
| [scroll-margin-block-start](https://developer.mozilla.org/en-US/docs/Web/CSS/scroll-margin-block-start)     | Defines the margin of the scroll snap area at the start of the block dimension                                  |
| [scroll-margin-bottom](https://developer.mozilla.org/en-US/docs/Web/CSS/scroll-margin-bottom)               | Defines the bottom margin of the scroll snap area                                                               |
| [scroll-margin-inline](https://developer.mozilla.org/en-US/docs/Web/CSS/scroll-margin-inline)               | Shorthand property for scroll-margin-inline-start and scroll-margin-inline-end                                  |
| [scroll-margin-inline-end](https://developer.mozilla.org/en-US/docs/Web/CSS/scroll-margin-inline-end)       | Defines the margin of the scroll snap area at the end of the inline dimension                                   |
| [scroll-margin-inline-start](https://developer.mozilla.org/en-US/docs/Web/CSS/scroll-margin-inline-start)   | Defines the margin of the scroll snap area at the start of the inline dimension                                 |
| [scroll-margin-left](https://developer.mozilla.org/en-US/docs/Web/CSS/scroll-margin-left)                   | Defines the left margin of the scroll snap area                                                                 |
| [scroll-margin-right](https://developer.mozilla.org/en-US/docs/Web/CSS/scroll-margin-right)                 | Defines the right margin of the scroll snap area                                                                |
| [scroll-margin-top](https://developer.mozilla.org/en-US/docs/Web/CSS/scroll-margin-top)                     | Defines the top margin of the scroll snap area                                                                  |
| [scroll-padding](https://developer.mozilla.org/en-US/docs/Web/CSS/scroll-padding)                           | Shorthand property for scroll-padding-top, scroll-padding-right, scroll-padding-bottom, and scroll-padding-left |
| [scroll-padding-block](https://developer.mozilla.org/en-US/docs/Web/CSS/scroll-padding-block)               | Shorthand property for scroll-padding-block-start and scroll-padding-block-end                                  |
| [scroll-padding-block-end](https://developer.mozilla.org/en-US/docs/Web/CSS/scroll-padding-block-end)       | Defines the padding of the scroll snap area at the end of the block dimension                                   |
| [scroll-padding-block-start](https://developer.mozilla.org/en-US/docs/Web/CSS/scroll-padding-block-start)   | Defines the padding of the scroll snap area at the start of the block dimension                                 |
| [scroll-padding-bottom](https://developer.mozilla.org/en-US/docs/Web/CSS/scroll-padding-bottom)             | Defines the bottom padding of the scroll snap area                                                              |
| [scroll-padding-inline](https://developer.mozilla.org/en-US/docs/Web/CSS/scroll-padding-inline)             | Shorthand property for scroll-padding-inline-start and scroll-padding-inline-end                                |
| [scroll-padding-inline-end](https://developer.mozilla.org/en-US/docs/Web/CSS/scroll-padding-inline-end)     | Defines the padding of the scroll snap area at the end of the inline dimension                                  |
| [scroll-padding-inline-start](https://developer.mozilla.org/en-US/docs/Web/CSS/scroll-padding-inline-start) | Defines the padding of the scroll snap area at the start of the inline dimension                                |
| [scroll-padding-left](https://developer.mozilla.org/en-US/docs/Web/CSS/scroll-padding-left)                 | Defines the left padding of the scroll snap area                                                                |
| [scroll-padding-right](https://developer.mozilla.org/en-US/docs/Web/CSS/scroll-padding-right)               | Defines the right padding of the scroll snap area                                                               |
| [scroll-padding-top](https://developer.mozilla.org/en-US/docs/Web/CSS/scroll-padding-top)                   | Defines the top padding of the scroll snap area                                                                 |
| [scroll-snap-align](https://developer.mozilla.org/en-US/docs/Web/CSS/scroll-snap-align)                     | Specifies the box's snap position as an alignment of its snap area                                              |
| [scroll-snap-stop](https://developer.mozilla.org/en-US/docs/Web/CSS/scroll-snap-stop)                       | Defines whether the scroll container is allowed to "pass over" possible snap positions                          |
| [scroll-snap-type](https://developer.mozilla.org/en-US/docs/Web/CSS/scroll-snap-type)                       | Sets how strictly snap points are enforced on the scroll container                                              |

## Typography

| Property                                                                                                                  | Description                                                                                                 |
|---------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------|
| @annotation                                                                                                               | Specifies the glyph annotation for the selected font                                                        |
| @character-variant                                                                                                        | Specifies the character variant for the selected font                                                       |
| [@font-feature-values](https://developer.mozilla.org/en-US/docs/Web/CSS/@font-feature-values)                             | Allows authors to use a common name in font-variant-alternate for feature activated differently in OpenType |
| [@font-palette-values](https://developer.mozilla.org/en-US/docs/Web/CSS/@font-palette-values)                             | Defines a palette of colors for a color font                                                                |
| @ornaments                                                                                                                | Specifies ornaments for the selected font                                                                   |
| @styleset                                                                                                                 | Specifies a stylistic set for the selected font                                                             |
| @stylistic                                                                                                                | Specifies a stylistic alternate for the selected font                                                       |
| @swash                                                                                                                    | Specifies a swash alternate for the selected font                                                           |
| [-webkit-line-clamp](https://developer.mozilla.org/en-US/docs/Web/CSS/-webkit-line-clamp)                                 | Allows limiting of the contents of a block container to the specified number of lines                       |
| annotation()                                                                                                              | Enables an annotation on the selected font                                                                  |
| [base-palette (@font-palette-values)](https://developer.mozilla.org/en-US/docs/Web/CSS/@font-palette-values/base-palette) | Specifies the base palette for a color font                                                                 |
| character-variant()                                                                                                       | Enables specific character variants in the selected font                                                    |
| [local()](https://developer.mozilla.org/en-US/docs/Web/CSS/@font-face)                                                    | Specifies a locally-installed font to use                                                                   |
| [font-family (@font-palette-values)](https://developer.mozilla.org/en-US/docs/Web/CSS/@font-palette-values)               | Specifies the font family for a color font palette                                                          |
| [font-optical-sizing](https://developer.mozilla.org/en-US/docs/Web/CSS/font-optical-sizing)                               | Controls whether the browser automatically adjusts font outlines to optimize legibility                     |
| [font-palette](https://developer.mozilla.org/en-US/docs/Web/CSS/font-palette)                                             | Allows selection of a font palette defined by @font-palette-values                                          |
| [font-synthesis](https://developer.mozilla.org/en-US/docs/Web/CSS/font-synthesis)                                         | Controls which missing typefaces can be synthesized by the browser                                          |
| [font-synthesis-small-caps](https://developer.mozilla.org/en-US/docs/Web/CSS/font-synthesis-small-caps)                   | Controls whether small-caps can be synthesized when not present in a font                                   |
| [font-synthesis-style](https://developer.mozilla.org/en-US/docs/Web/CSS/font-synthesis-style)                             | Controls whether italic styles can be synthesized when not present in a font                                |
| [font-synthesis-weight](https://developer.mozilla.org/en-US/docs/Web/CSS/font-synthesis-weight)                           | Controls whether bold styles can be synthesized when not present in a font                                  |
| [font-variant](https://developer.mozilla.org/en-US/docs/Web/CSS/font-variant)                                             | Shorthand for various font variant properties                                                               |
| [font-variant (@font-face)](https://developer.mozilla.org/en-US/docs/Web/CSS/@font-face)                                  | Specifies font variant for @font-face rule                                                                  |
| [font-variant-alternates](https://developer.mozilla.org/en-US/docs/Web/CSS/font-variant-alternates)                       | Controls the usage of alternate glyphs for a font                                                           |
| [font-variant-caps](https://developer.mozilla.org/en-US/docs/Web/CSS/font-variant-caps)                                   | Controls the usage of alternate glyphs for capital letters                                                  |
| [font-variant-east-asian](https://developer.mozilla.org/en-US/docs/Web/CSS/font-variant-east-asian)                       | Controls the usage of alternate glyphs for East Asian scripts                                               |
| [font-variant-emoji](https://developer.mozilla.org/en-US/docs/Web/CSS/font-variant-emoji)                                 | Controls which emoji presentation form to use                                                               |
| [font-variant-ligatures](https://developer.mozilla.org/en-US/docs/Web/CSS/font-variant-ligatures)                         | Controls which ligatures and contextual forms are used                                                      |
| [font-variant-numeric](https://developer.mozilla.org/en-US/docs/Web/CSS/font-variant-numeric)                             | Controls the usage of alternate glyphs for numbers, fractions, and ordinal markers                          |
| [font-variant-position](https://developer.mozilla.org/en-US/docs/Web/CSS/font-variant-position)                           | Controls the usage of alternate glyphs for subscript and superscript                                        |
| [font-variation-settings](https://developer.mozilla.org/en-US/docs/Web/CSS/font-variation-settings)                       | Provides low-level control over variable font characteristics                                               |
| [font-variation-settings (@font-face)](https://developer.mozilla.org/en-US/docs/Web/CSS/@font-face)                       | Specifies font variation settings for @font-face rule                                                       |
| [hanging-punctuation](https://developer.mozilla.org/en-US/docs/Web/CSS/hanging-punctuation)                               | Specifies whether punctuation marks should hang outside the line box                                        |
| [hyphens](https://developer.mozilla.org/en-US/docs/Web/CSS/hyphens)                                                       | Specifies how words should be hyphenated                                                                    |
| [line-gap-override (@font-face)](https://developer.mozilla.org/en-US/docs/Web/CSS/@font-face)                             | Specifies line gap metric override for @font-face rule                                                      |
| styleset()                                                                                                                | Enables a stylistic set of glyphs                                                                           |
| stylistic()                                                                                                               | Enables a stylistic alternate                                                                               |
| swash()                                                                                                                   | Enables a swash alternate                                                                                   |
| [text-combine-upright](https://developer.mozilla.org/en-US/docs/Web/CSS/text-combine-upright)                             | Sets the combination of characters into the space of a single character                                     |
| [text-decoration-color](https://developer.mozilla.org/en-US/docs/Web/CSS/text-decoration-color)                           | Specifies the color of text decorations                                                                     |
| [text-decoration-line](https://developer.mozilla.org/en-US/docs/Web/CSS/text-decoration-line)                             | Specifies the type of text decoration                                                                       |
| [text-decoration-skip](https://developer.mozilla.org/en-US/docs/Web/CSS/text-decoration-skip)                             | Specifies what parts of an element's content any text decoration affecting the element must skip over       |
| [text-decoration-skip-ink](https://developer.mozilla.org/en-US/docs/Web/CSS/text-decoration-skip-ink)                     | Specifies how overlines and underlines are drawn when they pass over glyph ascenders and descenders         |
| [text-decoration-style](https://developer.mozilla.org/en-US/docs/Web/CSS/text-decoration-style)                           | Specifies the style of text decoration                                                                      |
| [text-decoration-thickness](https://developer.mozilla.org/en-US/docs/Web/CSS/text-decoration-thickness)                   | Specifies the thickness of text decoration                                                                  |
| [text-emphasis](https://developer.mozilla.org/en-US/docs/Web/CSS/text-emphasis)                                           | Shorthand for text-emphasis-style and text-emphasis-color                                                   |
| [text-emphasis-color](https://developer.mozilla.org/en-US/docs/Web/CSS/text-emphasis-color)                               | Specifies the color of text emphasis marks                                                                  |
| [text-emphasis-position](https://developer.mozilla.org/en-US/docs/Web/CSS/text-emphasis-position)                         | Specifies the position of text emphasis marks                                                               |
| [text-emphasis-style](https://developer.mozilla.org/en-US/docs/Web/CSS/text-emphasis-style)                               | Specifies the appearance of text emphasis marks                                                             |
| [text-orientation](https://developer.mozilla.org/en-US/docs/Web/CSS/text-orientation)                                     | Specifies the orientation of text in a line                                                                 |
| [text-underline-offset](https://developer.mozilla.org/en-US/docs/Web/CSS/text-underline-offset)                           | Specifies the offset of underlines                                                                          |
| [text-underline-position](https://developer.mozilla.org/en-US/docs/Web/CSS/text-underline-position)                       | Specifies the position of underlines                                                                        |
| ornaments()                                                                                                               | Enables ornaments in the selected font                                                                      |

# CSS5

## Animation

| Property                                                                                        | Description                                                           |
|-------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------|
| [animation-composition](https://developer.mozilla.org/en-US/docs/Web/CSS/animation-composition) | Specifies how an animation's keyframes are combined                   |
| [offset-anchor](https://developer.mozilla.org/en-US/docs/Web/CSS/offset-anchor)                 | Specifies the anchor point of the element for the offset-path         |
| [offset-distance](https://developer.mozilla.org/en-US/docs/Web/CSS/offset-distance)             | Specifies the position along an offset-path                           |
| [offset-path](https://developer.mozilla.org/en-US/docs/Web/CSS/offset-path)                     | Specifies a motion path for an element to follow                      |
| [offset-position](https://developer.mozilla.org/en-US/docs/Web/CSS/offset-position)             | Specifies the initial position of the element along the offset-path   |
| [offset-rotate](https://developer.mozilla.org/en-US/docs/Web/CSS/offset-rotate)                 | Specifies how an element is rotated as it moves along the offset-path |

## At-rules

| Property                                                                                                                        | Description                                                             |
|---------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------|
| @custom-media                                                                                                                   | Defines custom media queries                                            |
| [@layer](https://developer.mozilla.org/en-US/docs/Web/CSS/@layer)                                                               | Declares a cascade layer                                                |
| [@scope](https://developer.mozilla.org/en-US/docs/Web/CSS/@scope)                                                               | Allows scoping of styles to a specific part of the document             |
| [@scope :scope](https://developer.mozilla.org/en-US/docs/Web/CSS/:scope)                                                        | Represents the elements that are within the scope of the @scope at-rule |
| [@starting-style](https://developer.mozilla.org/en-US/docs/Web/CSS/@starting-style)                                             | Defines the starting styles for a transition                            |
| [@supports selector()](https://developer.mozilla.org/en-US/docs/Web/CSS/@supports)                                              | Tests if the browser supports a particular CSS selector                 |
| [override-colors (@font-palette-values)](https://developer.mozilla.org/en-US/docs/Web/CSS/@font-palette-values/override-colors) | Overrides specific colors in a font palette                             |
| [syntax (@property)](https://developer.mozilla.org/en-US/docs/Web/CSS/@property)                                                | Defines the syntax of a custom property                                 |

## Cascade Layers

| Property                                                                      | Description                                                                   |
|-------------------------------------------------------------------------------|-------------------------------------------------------------------------------|
| [layer()](https://developer.mozilla.org/en-US/docs/Web/CSS/@layer)            | Defines a cascade layer                                                       |
| [layer() (@import)](https://developer.mozilla.org/en-US/docs/Web/CSS/@layer)  | Imports styles into a specific cascade layer                                  |
| [revert-layer](https://developer.mozilla.org/en-US/docs/Web/CSS/revert-layer) | Reverts a property value to the value established in a previous cascade layer |

## Colors & theming

| Property                                                                                                                                    | Description                                                              |
|---------------------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------|
| [accent-color](https://developer.mozilla.org/en-US/docs/Web/CSS/accent-color)                                                               | Specifies the accent color for user-interface controls                   |
| [color-scheme](https://developer.mozilla.org/en-US/docs/Web/CSS/color-scheme)                                                               | Specifies which color schemes the element can comfortably be rendered in |
| [color-mix()](https://developer.mozilla.org/en-US/docs/Web/CSS/color_value/color-mix)                                                       | Mixes two colors                                                         |
| [color() - display-p3, rec2020, a98, prophoto, xyz, xyz-d50, xyz-d65](https://developer.mozilla.org/en-US/docs/Web/CSS/color_value/color)   | Specifies a color in various color spaces                                |
| [color(from ...) - relative color syntax](https://developer.mozilla.org/en-US/docs/Web/CSS/color_value/color)                               | Specifies a color relative to another color                              |
| [Hue interpolation (gradients "in" syntax, "hue longer" syntax)](https://developer.mozilla.org/en-US/docs/Web/CSS/hue-interpolation-method) | Specifies how hue should be interpolated in gradients                    |
| [hwb()](https://developer.mozilla.org/en-US/docs/Web/CSS/color_value/hwb)                                                                   | Specifies a color using the Hue-Whiteness-Blackness model                |
| [oklab()](https://developer.mozilla.org/en-US/docs/Web/CSS/color_value/oklab)                                                               | Specifies a color using the OKLAB color space                            |
| [oklch()](https://developer.mozilla.org/en-US/docs/Web/CSS/color_value/oklch)                                                               | Specifies a color using the OKLCH color space                            |
| [lab()](https://developer.mozilla.org/en-US/docs/Web/CSS/color_value/lab)                                                                   | Specifies a color using the CIELAB color space                           |
| [lch()](https://developer.mozilla.org/en-US/docs/Web/CSS/color_value/lch)                                                                   | Specifies a color using the LCH color space                              |

## Container Queries

| Property                                                                                                                                                   | Description                                                 |
|------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------|
| [length#cqw, cqi, cqb, cqh, cqmax, cqmin](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_containment/Container_queries#container_query_length_units) | Container query length units                                |
| [contain-intrinsic-block-size](https://developer.mozilla.org/en-US/docs/Web/CSS/contain-intrinsic-block-size)                                              | Specifies the intrinsic block size of an element's content  |
| [contain-intrinsic-height](https://developer.mozilla.org/en-US/docs/Web/CSS/contain-intrinsic-height)                                                      | Specifies the intrinsic height of an element's content      |
| [contain-intrinsic-inline-size](https://developer.mozilla.org/en-US/docs/Web/CSS/contain-intrinsic-inline-size)                                            | Specifies the intrinsic inline size of an element's content |
| [contain-intrinsic-size](https://developer.mozilla.org/en-US/docs/Web/CSS/contain-intrinsic-size)                                                          | Specifies the intrinsic size of an element's content        |
| [contain-intrinsic-width](https://developer.mozilla.org/en-US/docs/Web/CSS/contain-intrinsic-width)                                                        | Specifies the intrinsic width of an element's content       |
| [container](https://developer.mozilla.org/en-US/docs/Web/CSS/container)                                                                                    | Declares a container for container queries                  |
| [container-name](https://developer.mozilla.org/en-US/docs/Web/CSS/container-name)                                                                          | Specifies a name for a query container                      |
| [container-type](https://developer.mozilla.org/en-US/docs/Web/CSS/container-type)                                                                          | Specifies the type of container for container queries       |

## Logical Properties

| Property                                                                                  | Description                                                  |
|-------------------------------------------------------------------------------------------|--------------------------------------------------------------|
| [inset](https://developer.mozilla.org/en-US/docs/Web/CSS/inset)                           | Shorthand for the top, right, bottom, and/or left properties |
| [inset-block](https://developer.mozilla.org/en-US/docs/Web/CSS/inset-block)               | Shorthand for inset-block-start and inset-block-end          |
| [inset-block-end](https://developer.mozilla.org/en-US/docs/Web/CSS/inset-block-end)       | Defines the logical block end offset of an element           |
| [inset-block-start](https://developer.mozilla.org/en-US/docs/Web/CSS/inset-block-start)   | Defines the logical block start offset of an element         |
| [inset-inline](https://developer.mozilla.org/en-US/docs/Web/CSS/inset-inline)             | Shorthand for inset-inline-start and inset-inline-end        |
| [inset-inline-end](https://developer.mozilla.org/en-US/docs/Web/CSS/inset-inline-end)     | Defines the logical inline end offset of an element          |
| [inset-inline-start](https://developer.mozilla.org/en-US/docs/Web/CSS/inset-inline-start) | Defines the logical inline start offset of an element        |

## Math Functions

| Property                                                          | Description                                                                        |
|-------------------------------------------------------------------|------------------------------------------------------------------------------------|
| [abs()](https://developer.mozilla.org/en-US/docs/Web/CSS/abs)     | Returns the absolute value of a number                                             |
| [acos()](https://developer.mozilla.org/en-US/docs/Web/CSS/acos)   | Returns the arccosine of a number                                                  |
| [asin()](https://developer.mozilla.org/en-US/docs/Web/CSS/asin)   | Returns the arcsine of a number                                                    |
| [atan()](https://developer.mozilla.org/en-US/docs/Web/CSS/atan)   | Returns the arctangent of a number                                                 |
| [atan2()](https://developer.mozilla.org/en-US/docs/Web/CSS/atan2) | Returns the arctangent of the quotient of its arguments                            |
| [cos()](https://developer.mozilla.org/en-US/docs/Web/CSS/cos)     | Returns the cosine of a number                                                     |
| [exp()](https://developer.mozilla.org/en-US/docs/Web/CSS/exp)     | Returns e raised to the power of a number                                          |
| [hypot()](https://developer.mozilla.org/en-US/docs/Web/CSS/hypot) | Returns the square root of the sum of squares of its arguments                     |
| [log()](https://developer.mozilla.org/en-US/docs/Web/CSS/log)     | Returns the natural logarithm of a number                                          |
| [mod()](https://developer.mozilla.org/en-US/docs/Web/CSS/mod)     | Returns the remainder of a division                                                |
| [pow()](https://developer.mozilla.org/en-US/docs/Web/CSS/pow)     | Returns the base to the exponent power                                             |
| [rem()](https://developer.mozilla.org/en-US/docs/Web/CSS/rem)     | Returns the remainder of a division                                                |
| [round()](https://developer.mozilla.org/en-US/docs/Web/CSS/round) | Rounds a number to the nearest integer                                             |
| [sin()](https://developer.mozilla.org/en-US/docs/Web/CSS/sin)     | Returns the sine of a number                                                       |
| [sign()](https://developer.mozilla.org/en-US/docs/Web/CSS/sign)   | Returns the sign of a number, indicating whether it is positive, negative, or zero |
| [sqrt()](https://developer.mozilla.org/en-US/docs/Web/CSS/sqrt)   | Returns the square root of a number                                                |
| [tan()](https://developer.mozilla.org/en-US/docs/Web/CSS/tan)     | Returns the tangent of a number                                                    |

## Pseudo-classes

| Property                                                                                                  | Description                                                                            |
|-----------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------|
| [:has()](https://developer.mozilla.org/en-US/docs/Web/CSS/:has)                                           | Matches elements that contain at least one element that matches the specified selector |
| [:is()](https://developer.mozilla.org/en-US/docs/Web/CSS/:is)                                             | Matches any of the selectors in the selector list                                      |
| [:nth-child(An+B [of S]?)](https://developer.mozilla.org/en-US/docs/Web/CSS/:nth-child#using_of_selector) | Matches elements based on their position among siblings, with optional filtering       |
| [:picture-in-picture](https://developer.mozilla.org/en-US/docs/Web/CSS/:picture-in-picture)               | Matches an element that is currently in picture-in-picture mode                        |
| [:popover-open](https://developer.mozilla.org/en-US/docs/Web/CSS/:popover-open)                           | Matches a popover element that is currently showing                                    |
| [:where()](https://developer.mozilla.org/en-US/docs/Web/CSS/:where)                                       | Matches elements that match the selector list, but doesn't add specificity             |

## Pseudo-elements

| Property                                                                              | Description                                                                           |
|---------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------|
| [::grammar-error](https://developer.mozilla.org/en-US/docs/Web/CSS/::grammar-error)   | Represents a text segment which the user agent has flagged as grammatically incorrect |
| [::marker](https://developer.mozilla.org/en-US/docs/Web/CSS/::marker)                 | Represents the marker box of a list item                                              |
| [::spelling-error](https://developer.mozilla.org/en-US/docs/Web/CSS/::spelling-error) | Represents a text segment which the user agent has flagged as incorrectly spelled     |

## Relative Units

| Property                                                                                                                                   | Description                                                                                         |
|--------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------|
| [Dynamic Viewport Units (dvh, lvh & svh)](https://developer.mozilla.org/en-US/docs/Web/CSS/length#relative_length_units_based_on_viewport) | Viewport units that account for dynamic viewports (e.g., mobile browsers with collapsible toolbars) |
| [length#cap](https://developer.mozilla.org/en-US/docs/Web/CSS/length#cap)                                                                  | Equal to the cap height of the element's font                                                       |
| [length#ex, length#rex](https://developer.mozilla.org/en-US/docs/Web/CSS/length#ex)                                                        | Represents the x-height of the element's font                                                       |
| [length#ic, length#ric](https://developer.mozilla.org/en-US/docs/Web/CSS/length#ic)                                                        | Equal to the used advance measure of the "水" (CJK water ideograph, U+6C34) glyph                    |
| [length#lh, length#rlh](https://developer.mozilla.org/en-US/docs/Web/CSS/length#lh)                                                        | Equal to the line height of the element                                                             |

## Scroll

| Property                                                                                      | Description                                                                                          |
|-----------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------|
| [content-visibility](https://developer.mozilla.org/en-US/docs/Web/CSS/content-visibility)     | Controls whether or not an element renders its contents at all                                       |
| [overflow](https://developer.mozilla.org/en-US/docs/Web/CSS/overflow)                         | Specifies how to handle content that overflows the element's box (clip value)                        |
| [overflow-clip-margin](https://developer.mozilla.org/en-US/docs/Web/CSS/overflow-clip-margin) | Specifies how far outside its bounds an element with `overflow: clip` may paint before being clipped |
| [scrollbar-color](https://developer.mozilla.org/en-US/docs/Web/CSS/scrollbar-color)           | Sets the color of the scrollbar track and thumb                                                      |
| [scrollbar-gutter](https://developer.mozilla.org/en-US/docs/Web/CSS/scrollbar-gutter)         | Controls the behavior of the scrollbar gutter                                                        |
| [scrollbar-width](https://developer.mozilla.org/en-US/docs/Web/CSS/scrollbar-width)           | Sets the width of the scrollbar                                                                      |

## Scroll-driven animations

| Property                                                                                        | Description                                                    |
|-------------------------------------------------------------------------------------------------|----------------------------------------------------------------|
| [animation-range](https://developer.mozilla.org/en-US/docs/Web/CSS/animation-range)             | Specifies the range for a scroll-driven animation              |
| [animation-range-end](https://developer.mozilla.org/en-US/docs/Web/CSS/animation-range-end)     | Specifies the end of the range for a scroll-driven animation   |
| [animation-range-start](https://developer.mozilla.org/en-US/docs/Web/CSS/animation-range-start) | Specifies the start of the range for a scroll-driven animation |
| [animation-timeline](https://developer.mozilla.org/en-US/docs/Web/CSS/animation-timeline)       | Specifies the timeline for an animation                        |
| [scroll-timeline](https://developer.mozilla.org/en-US/docs/Web/CSS/scroll-timeline)             | Defines a scroll timeline                                      |
| [scroll-timeline-axis](https://developer.mozilla.org/en-US/docs/Web/CSS/scroll-timeline-axis)   | Specifies the axis of the scroll timeline                      |
| [scroll-timeline-name](https://developer.mozilla.org/en-US/docs/Web/CSS/scroll-timeline-name)   | Specifies the name of the scroll timeline                      |
| [scroll()](https://developer.mozilla.org/en-US/docs/Web/CSS/animation-timeline/scroll)          | Creates a scroll progress timeline                             |
| [timeline-scope](https://developer.mozilla.org/en-US/docs/Web/CSS/timeline-scope)               | Sets the timeline scope for descendant elements                |
| [view-timeline](https://developer.mozilla.org/en-US/docs/Web/CSS/view-timeline)                 | Defines a view timeline                                        |
| [view-timeline-axis](https://developer.mozilla.org/en-US/docs/Web/CSS/view-timeline-axis)       | Specifies the axis of the view timeline                        |
| [view-timeline-inset](https://developer.mozilla.org/en-US/docs/Web/CSS/view-timeline-inset)     | Specifies the inset for the view timeline                      |
| [view-timeline-name](https://developer.mozilla.org/en-US/docs/Web/CSS/view-timeline-name)       | Specifies the name of the view timeline                        |

## Transition & Transforms

| Property                                                                                    | Description                                   |
|---------------------------------------------------------------------------------------------|-----------------------------------------------|
| [overlay](https://developer.mozilla.org/en-US/docs/Web/CSS/overlay)                         | Defines how an element's overlay is displayed |
| [rotate](https://developer.mozilla.org/en-US/docs/Web/CSS/rotate)                           | Specifies rotation transforms                 |
| [scale](https://developer.mozilla.org/en-US/docs/Web/CSS/scale)                             | Specifies scaling transforms                  |
| [transition-behavior](https://developer.mozilla.org/en-US/docs/Web/CSS/transition-behavior) | Specifies the behavior of transitions         |
| [translate](https://developer.mozilla.org/en-US/docs/Web/CSS/translate)                     | Specifies translation transforms              |

## Typography

| Property                                                                                                      | Description                                                                               |
|---------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------|
| [ascent-override (@font-face)](https://developer.mozilla.org/en-US/docs/Web/CSS/@font-face/ascent-override)   | Overrides the font's ascent metric                                                        |
| [descent-override (@font-face)](https://developer.mozilla.org/en-US/docs/Web/CSS/@font-face/descent-override) | Overrides the font's descent metric                                                       |
| [font-size-adjust](https://developer.mozilla.org/en-US/docs/Web/CSS/font-size-adjust)                         | Specifies that font size should be chosen based on the height of lowercase letters        |
| [font-synthesis-position](https://developer.mozilla.org/en-US/docs/Web/CSS/font-synthesis-position)           | Controls the synthesis of superscript and subscript glyphs                                |
| [hyphenate-character](https://developer.mozilla.org/en-US/docs/Web/CSS/hyphenate-character)                   | Specifies the character (or string) to be used for line breaks resulting from hyphenation |
| [hyphenate-limit-chars](https://developer.mozilla.org/en-US/docs/Web/CSS/hyphenate-limit-chars)               | Specifies the minimum number of characters in a hyphenated word                           |
| [initial-letter](https://developer.mozilla.org/en-US/docs/Web/CSS/initial-letter)                             | Specifies styling for dropped, raised, and sunken initial letters                         |
| [initial-letter-align](https://developer.mozilla.org/en-US/docs/Web/CSS/initial-letter-align)                 | Specifies the alignment of initial letters within a paragraph                             |
| Text-box trim                                                                                                 | Controls the trimming of text boxes                                                       |
| [text-wrap](https://developer.mozilla.org/en-US/docs/Web/CSS/text-wrap)                                       | Specifies line breaking rules for text (balance / pretty)                                 |

## View transitions

| Property                                                                                                      | Description                                                                |
|---------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------|
| [::view-transition](https://developer.mozilla.org/en-US/docs/Web/CSS/::view-transition)                       | Represents the root of a view transition pseudo-element tree               |
| [::view-transition-group](https://developer.mozilla.org/en-US/docs/Web/CSS/::view-transition-group)           | Represents a group of elements that transition as a unit                   |
| [::view-transition-image-pair](https://developer.mozilla.org/en-US/docs/Web/CSS/::view-transition-image-pair) | Represents the parent element of the old and new views during a transition |
| [::view-transition-new](https://developer.mozilla.org/en-US/docs/Web/CSS/::view-transition-new)               | Represents the new view during a transition                                |
| [::view-transition-old](https://developer.mozilla.org/en-US/docs/Web/CSS/::view-transition-old)               | Represents the old view during a transition                                |
| @view-transition                                                                                              | Defines styles for view transitions                                        |
| view-transition-class                                                                                         | Specifies the class of a view transition                                   |
| [view-transition-name](https://developer.mozilla.org/en-US/docs/Web/CSS/view-transition-name)                 | Specifies the name of a view transition                                    |
| view-transition-type                                                                                          | Specifies the type of a view transition                                    |

# Future (Uncategorized, out of scope for CSS4/5)

## Align

| Property                                                                          | Description                                                               |
|-----------------------------------------------------------------------------------|---------------------------------------------------------------------------|
| [align-tracks](https://developer.mozilla.org/en-US/docs/Web/CSS/align-tracks)     | Specifies the alignment of tracks in a masonry grid                       |
| [justify-tracks](https://developer.mozilla.org/en-US/docs/Web/CSS/justify-tracks) | Specifies the alignment of tracks in a masonry grid along the inline axis |

## Anchoring

| Property | Description                           |
|----------|---------------------------------------|
| anchor() | Anchors an element to another element |

## Aural CSS

| Property                                                                                              | Description                                                        |
|-------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------|
| [speak-as (@counter-style)](https://developer.mozilla.org/en-US/docs/Web/CSS/@counter-style/speak-as) | Specifies how a counter should be announced by speech synthesizers |

## Color

| Property                                                                                        | Description                                                       |
|-------------------------------------------------------------------------------------------------|-------------------------------------------------------------------|
| [contrast-color()](https://developer.mozilla.org/en-US/docs/Web/CSS/color_value/color-contrast) | Selects the color with the highest contrast from a list of colors |

## Container Queries

| Property                                                                                             | Description                                                    |
|------------------------------------------------------------------------------------------------------|----------------------------------------------------------------|
| [Style queries](https://developer.mozilla.org/en-US/docs/Web/CSS/@container#container_style_queries) | Allows querying the computed values of an element's properties |

## Functions

| Property                                                                | Description                                                                                     |
|-------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------|
| [element()](https://developer.mozilla.org/en-US/docs/Web/CSS/element)   | Defines an `<image>` value generated from an arbitrary HTML element                             |
| [image()](https://developer.mozilla.org/en-US/docs/Web/CSS/image/image) | Defines an `<image>` in a similar fashion to the `url()` function, but with added functionality |

## Grid

| Property                                                                                | Description                                  |
|-----------------------------------------------------------------------------------------|----------------------------------------------|
| [masonry-auto-flow](https://developer.mozilla.org/en-US/docs/Web/CSS/masonry-auto-flow) | Specifies how items flow in a masonry layout |

## Pseudo-classes

| Property                                                                          | Description                                                                            |
|-----------------------------------------------------------------------------------|----------------------------------------------------------------------------------------|
| [:modal](https://developer.mozilla.org/en-US/docs/Web/CSS/:modal)                 | Matches elements that are in a modal state                                             |
| [:target-within](https://developer.mozilla.org/en-US/docs/Web/CSS/:target-within) | Represents an element that is a target element or contains an element that is a target |
| :top-layer                                                                        | Matches elements that are in the top layer                                             |

## Pseudo-elements

| Property                                                                        | Description                                                                                    |
|---------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------|
| [::target-text](https://developer.mozilla.org/en-US/docs/Web/CSS/::target-text) | Represents the text that has been scrolled to if the browser supports scroll-to-text fragments |

## Scroll

| Property      | Description                                                      |
|---------------|------------------------------------------------------------------|
| target-text() | A function that allows targeting specific text within an element |

## Text Fragmentation

| Property                                                            | Description                                                                                          |
|---------------------------------------------------------------------|------------------------------------------------------------------------------------------------------|
| [orphans](https://developer.mozilla.org/en-US/docs/Web/CSS/orphans) | Specifies the minimum number of lines in a block container that must be left at the bottom of a page |

## Typography

| Property                                                                                      | Description                                                                              |
|-----------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------|
| [line-clamp](https://developer.mozilla.org/en-US/docs/Web/CSS/-webkit-line-clamp)             | Allows limiting of the contents of a block container to the specified number of lines    |
| [line-height-step](https://developer.mozilla.org/en-US/docs/Web/CSS/line-height-step)         | Sets the step unit for line height                                                       |
| [margin-trim](https://developer.mozilla.org/en-US/docs/Web/CSS/margin-trim)                   | Specifies whether margin collapsing is applied to the start and end edges of the element |
| [text-size-adjust](https://developer.mozilla.org/en-US/docs/Web/CSS/text-size-adjust)         | Controls the text inflation algorithm used on some smartphones and tablets               |
| [white-space-collapse](https://developer.mozilla.org/en-US/docs/Web/CSS/white-space-collapse) | Specifies how white space inside an element is collapsed                                 |
| white-space-trim                                                                              | Specifies trimming of white space inside an element                                      |

## Units

| Property                                                                   | Description                     |
|----------------------------------------------------------------------------|---------------------------------|
| [frequency#Hz](https://developer.mozilla.org/en-US/docs/Web/CSS/frequency) | Represents a frequency in hertz |