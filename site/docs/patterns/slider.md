---
wrapper_template: '_layouts/default.html'
context:
  title: Slider | Components
---

## Slider

<hr>

The `p-slider__wrapper` and `p-slider__input` classes should be used with `<input type="range">` elements
when you want to provide a numeric representation of the slider value, as well as allow the user to specify a value.

<a href="/docs/examples/patterns/slider/slider-input/" class="js-example">
View example of the slider pattern
</a>

<span class="p-label--updated">Updated</span> In version 2.6.0 Vanilla framework added slider styling as default for
all range inputs, so adding `p-slider` class just to style `<input type="range">` is not necessary any more.

### Import

To import just this component into your project, copy the snippet below and include it in your main Sass file.

```scss
@import 'patterns_slider';
@include vf-p-slider;
```

For more information see [Customising Vanilla](/customising-vanilla/) in your projects, which includes overrides and importing instructions.

### Design

For more information [view the slider design spec](https://github.com/ubuntudesign/vanilla-design/tree/master/Slider), which includes the specification in markdown format and a PNG image.