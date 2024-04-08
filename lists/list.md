# List of CSS4, CSS5 and future

This list is still a draft and should be handled as a work in progress.
This list is based on
the [full list of CSS features](https://docs.google.com/spreadsheets/d/1_zDofLl3nJiNAV2Cn1x-59f4NFE_p-y5_IYjIzKNK6k/edit#gid=0)
that were discussed

## CSS4

<details>
  <summary>Align</summary>

| Property      | Notes |
|---------------|-------|
| align-content |       |
| align-items   |       |
| align-self    |       |
| order         |       |
| place-content |       |
| place-items   |       |
| place-self    |       |
| row-gap       |       |

</details>

<details>
  <summary>Animating on a path</summary>

| Property | Notes |
|----------|-------|
| offset   |       |

</details>

<details>
  <summary>At-rules</summary>

| Property            | Notes |
|---------------------|-------|
| @media range-syntax |       |
| @supports           |       |

</details>

<details>
  <summary>Blend Modes</summary>

| Property  | Notes |
|-----------|-------|
| isolation |       |

</details>


<details>
  <summary>Contain</summary>

| Property | Notes |
|----------|-------|
| contain  |       |

</details>

<details>
  <summary>Counter</summary>

| Property                  | Notes |
|---------------------------|-------|
| @counter-style            |       |
| counter-set               |       |
| fallback (@counter-style) |       |
| suffix (@counter-style)   |       |
| symbols (@counter-style)  |       |
| symbols()                 |       |
| system (@counter-style)   |       |

</details>

<details>
  <summary>Flex</summary>

| Property       | Notes |
|----------------|-------|
| flex           |       |
| flex_value#fr  |       |
| flex-basis     |       |
| flex-direction |       |
| flex-flow      |       |
| flex-grow      |       |
| flex-shrink    |       |
| flex-wrap      |       |

</details>




<details>
  <summary>Functions</summary>

| Property      | Notes |
|---------------|-------|
| clamp()       |       |
| env()         |       |
| fit-content   |       |
| fit-content() |       |
| max()         |       |
| min()         |       |
| var(), --*    |       |

</details>

<details>
  <summary>Gradient</summary>

| Property         | Notes |
|------------------|-------|
| conic-gradient() |       |

</details>

<details>
  <summary>Grid</summary>

| Property              | Notes |
|-----------------------|-------|
| grid                  |       |
| grid-area             |       |
| grid-auto-columns     |       |
| grid-auto-flow        |       |
| grid-auto-rows        |       |
| grid-column           |       |
| grid-column-end       |       |
| grid-column-start     |       |
| grid-row              |       |
| grid-row-end          |       |
| grid-row-start        |       |
| grid-template         |       |
| grid-template-areas   |       |
| grid-template-columns |       |
| grid-template-rows    |       |

</details>

<details>
  <summary>Typography</summary>

| Property                             | Notes |
|--------------------------------------|-------|
| local()                              |       |
| font-family (@font-palette-values)   |       |
| font-optical-sizing                  |       |
| font-palette                         |       |
| font-synthesis                       |       |
| font-synthesis-small-caps            |       |
| font-synthesis-style                 |       |
| font-synthesis-weight                |       |
| font-variant                         |       |
| font-variant (@font-face)            |       |
| font-variant-alternates              |       |
| font-variant-caps                    |       |
| font-variant-east-asian              |       |
| font-variant-emoji                   |       |
| font-variant-ligatures               |       |
| font-variant-numeric                 |       |
| font-variant-position                |       |
| font-variation-settings              |       |
| font-variation-settings (@font-face) |       |
| line-gap-override (@font-face)       |       |
| @ornaments                           |       |
| ornaments()                          |       |

</details>

## CSS5

<details>
  <summary>Animation</summary>

| Property              | Notes |
|-----------------------|-------|
| animation-composition |       |
| offset-anchor         |       |
| offset-distance       |       |
| offset-path           |       |
| offset-position       |       |
| offset-rotate         |       |

</details>

<details>
  <summary>At-rules</summary>

| Property                               | Notes |
|----------------------------------------|-------|
| @custom-media                          |       |
| @layer                                 |       |
| @scope                                 |       |
| @scope :scope                          |       |
| @starting-style                        |       |
| @supports selector()                   |       |
| override-colors (@font-palette-values) |       |
| syntax (@property)                     |       |

</details>

<details>
  <summary>Cascade Layers</summary>

| Property          | Notes |
|-------------------|-------|
| layer()           |       |
| layer() (@import) |       |
| revert-layer      |       |

</details>

<details>
  <summary>Colors & theming</summary>

| Property                                                              | Notes |
|-----------------------------------------------------------------------|-------|
| accent-color                                                          |       |
| color-scheme                                                          |       |
| color-mix()                                                           |       |
| "color() - display-p3, rec2020, a98, prophoto, xyz, xyz-d50, xyz-d65" |       |
| color(from ...) - relative color syntax                               |       |
| "Hue interpolation (gradients ""in"" syntax, ""hue longer"" syntax)"  |       |
| hwb()                                                                 |       |
| oklab()                                                               |       |
| oklch()                                                               |       |
| lab()                                                                 |       |
| lch()                                                                 |       |
| New color spaces                                                      |       |

</details>

<details>
  <summary>Container Queries</summary>

| Property                                  | Notes |
|-------------------------------------------|-------|
| "length#cqw, cqi, cqb, cqh, cqmax, cqmin" |       |
| contain-intrinsic-block-size              |       |
| contain-intrinsic-height                  |       |
| contain-intrinsic-inline-size             |       |
| contain-intrinsic-size                    |       |
| contain-intrinsic-width                   |       |
| container                                 |       |
| container-name                            |       |
| container-type                            |       |

</details>

<details>
  <summary>Grid</summary>

| Property | Notes |
|----------|-------|
| Subgrid  |       |

</details>


<details>
  <summary>Logical Properites</summary>

| Property           | Notes |
|--------------------|-------|
| inset              |       |
| inset-block        |       |
| inset-block-end    |       |
| inset-block-start  |       |
| inset-inline       |       |
| inset-inline-end   |       |
| inset-inline-start |       |

</details>

<details>
  <summary>Math Functions</summary>

| Property | Notes |
|----------|-------|
| abs()    |       |
| acos()   |       |
| asin()   |       |
| atan()   |       |
| atan2()  |       |
| cos()    |       |
| exp()    |       |
| hypot()  |       |
| log()    |       |
| mod()    |       |
| pow()    |       |
| rem()    |       |
| round()  |       |
| sin()    |       |
| sign()   |       |
| sqrt()   |       |
| tan()    |       |

</details>



<details>
  <summary>Pseudo-classes</summary>

| Property                 | Notes |
|--------------------------|-------|
| :has                     |       |
| :is                      |       |
| :nth-child(An+B [of S]?) |       |
| :picture-in-picture      |       |
| :popover-open            |       |
| :where()                 |       |

</details>

<details>
  <summary>Pseudo-elements</summary>

| Property                     | Notes |
|------------------------------|-------|
| ::grammar-error              |       |
| ::marker                     |       |
| ::spelling-error             |       |
| ::view-transition            |       |
| ::view-transition-group      |       |
| ::view-transition-image-pair |       |
| ::view-transition-new        |       |
| ::view-transition-old        |       |
| view-transition-name         |       |

</details>

<details>
  <summary>Relative Units</summary>

| Property                                  | Notes |
|-------------------------------------------|-------|
| "Dynamic Viewport Units (dvh, lvh & svh)" |       |
| length#cap                                |       |
| "length#ex, length#rex"                   |       |
| "length#ic, length#ric"                   |       |
| "length#lh, length#rlh"                   |       |

</details>

<details>
  <summary>Scroll</summary>

| Property             | Notes |
|----------------------|-------|
| content-visibility   |       |
| overflow-clip-margin |       |
| scrollbar-color      |       |
| scrollbar-gutter     |       |
| scrollbar-width      |       |

</details>

<details>
  <summary>Scroll-driven animations</summary>

| Property              | Notes |
|-----------------------|-------|
| animation-range       |       |
| animation-range-end   |       |
| animation-range-start |       |
| animation-timeline    |       |
| scroll-timeline       |       |
| scroll-timeline-axis  |       |
| scroll-timeline-name  |       |
| scroll()              |       |
| timeline-scope        |       |
| view-timeline         |       |
| view-timeline-axis    |       |
| view-timeline-inset   |       |
| view-timeline-name    |       |

</details>


<details>
  <summary>Transition & Transforms</summary>

| Property            | Notes |
|---------------------|-------|
| overlay             |       |
| rotate              |       |
| scale               |       |
| transition-behavior |       |
| translate           |       |

</details>

<details>
  <summary>Typography</summary>

| Property                      | Notes |
|-------------------------------|-------|
| ascent-override (@font-face)  |       |
| descent-override (@font-face) |       |
| font-size-adjust              |       |
| font-synthesis-position       |       |
| hyphenate-character           |       |
| hyphenate-limit-chars         |       |
| initial-letter                |       |
| initial-letter-align          |       |
| Text-box trim                 |       |
| text-wrap                     |       |

</details>

## Future

<details>
  <summary>Align</summary>

| Property       | Notes |
|----------------|-------|
| align-tracks   |       |
| justify-tracks |       |

</details>

<details>
  <summary>Anchoring</summary>

| Property | Notes |
|----------|-------|
| anchor() |       |

</details>


<details>
  <summary>Aural CSS</summary>

| Property                  | Notes |
|---------------------------|-------|
| speak-as (@counter-style) |       |

</details>

<details>
  <summary>Color</summary>

| Property         | Notes |
|------------------|-------|
| contrast-color() |       |

</details>

<details>
<summary>Container Queries</summary>

| Property      | Notes |
|---------------|-------|
| Style queries |       |

</details>


<details>
  <summary>Functions</summary>

| Property  | Notes |
|-----------|-------|
| element() |       |
| image()   |       |

</details>

<details>
  <summary>Grid</summary>

| Property          | Notes |
|-------------------|-------|
| masonry-auto-flow |       |

</details>



<details>
  <summary>Pseudo-classes</summary>

| Property       | Notes |
|----------------|-------|
| :target-within |       |

</details>

<details>
  <summary>Pseudo-elements</summary>

| Property      | Notes |
|---------------|-------|
| ::target-text |       |

</details>
<details>
  <summary>Scroll</summary>

| Property      | Notes |
|---------------|-------|
| target-text() |       |

</details>

<details>
  <summary>Text Fragmentation</summary>

| Property | Notes |
|----------|-------|
| orphans  |       |

</details>

<details>
  <summary>Typography</summary>

| Property             | Notes |
|----------------------|-------|
| line-clamp           |       |
| line-height-step     |       |
| margin-trim          |       |
| text-size-adjust     |       |
| white-space-collapse |       |
| white-space-trim     |       |

</details>

<details>
  <summary>Units</summary>

| Property     | Notes |
|--------------|-------|
| frequency#Hz |       |

</details>

<details>
  <summary>View transitions</summary>

| Property                     | Notes |
|------------------------------|-------|
| ::view-transition            |       |
| ::view-transition-group      |       |
| ::view-transition-image-pair |       |
| ::view-transition-new        |       |
| ::view-transition-old        |       |
| @view-transition             |       |
| view-transition-class        |       |
| view-transition-name         |       |
| view-transition-type         |       |

</details>



