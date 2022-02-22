# Things I want to add to convolution demo

Probably I could make these into issues.

## Style
- I prefer Brandon Rohrer's [style of showing the multiplication and sum](https://e2eml.school/convolution_one_d.html)
- He has [code to create this visualization](https://gitlab.com/brohrer/cottonwood/-/blob/main/cottonwood/experimental/visualize_conv1d.py) on GitLab and it is MIT-licensed

## Exposition -- basics
- Need to add some context on where convolution gets used
- I want to keep the math light, but should include a sum formula with comparison to correlation
- I can also describe the algorithm / recipe / steps

## Exposition -- why flip the kernel?
- There's a detailed explanation on page 8 of [this guide from Carlo Tomasi](https://courses.cs.duke.edu/fall15/compsci527/notes/convolution-filtering.pdf)
- I think there's some underlying intuition here that could be put into a single sentence

## Interactivity
- Slider/scrubber to move forward and backward in time
- Toggle between convolution and correlation
- Ability to paste in your own amplitudes or choose a few different signals

## 1D convolution of 2D layers
- as in zero-offset [SRME](https://wiki.seg.org/wiki/Surface-related_multiple_elimination) or Jacubowicz-style Internal Multiple Prediction

## Code
- I could pre-compute things instead of using an iterator
- Could use `numba` to make for-loop faster

## References
- https://e2eml.school/convolution_one_d.html
- https://timdettmers.com/2015/03/26/convolution-deep-learning/
- https://glassboxmedicine.com/2019/07/26/convolution-vs-cross-correlation/
- https://dsp.stackexchange.com/questions/3482/how-can-output-sequence-be-equal-to-the-sum-of-copies-of-the-impulse-response-s
- https://www.youtube.com/watch?v=MQm6ZP1F6ms
