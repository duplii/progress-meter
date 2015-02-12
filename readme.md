# Progress meter

This is a progress meter built with svg and css animations.

In order to showcase it, we are now triggering the animation on hover. When implemented, the animation will be started and stopped toggling a class to the element.

Initially, the element was built using an svg-only, self-contained solution, but that would not work in Internet Explorer, so I reverted back to a css animated solution for broader compatibility. That initial stab is still available in the repo in the file `call-progress.svg`.

I am also including the `config.codekit` file so that everyone using Codekit will be able to get started immediately.

## Live demo

A live demo of this project can be found at [duplii.com/call-progress/](http://duplii.com/call-progress/index.html "Duplii | Progress meter demo").

<img src="http://duplii.s3.amazonaws.com/call-progress.jpg" width="463" height="275" alt="Call progress meter for Duplii.com" />