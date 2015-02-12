# Progress meter

This is a progress meter built with svg and css animations.

The animation will be toggled by clicking on the little text below the meter. This will mimick our app's real needs, where we will have to trigger the animation on call start and stop it on call-end.

The timer is set at 90 seconds. This is a reasonable time for our use-case, but it might change in the future.

Initially, the element was built using an svg-only, self-contained solution, but that would not work in Internet Explorer, so I reverted back to a css animated solution for broader compatibility. That initial stab is still available in the repo in the file `call-progress.svg`.

I am also including the `config.codekit` file so that everyone using Codekit will be able to get started immediately.

## Live demo

A live demo of this project can be found at [duplii.github.io/progress-meter](http://duplii.github.io/progress-meter "Duplii | Progress meter demo").

<img src="http://duplii.s3.amazonaws.com/call-progress.jpg" width="463" height="275" alt="Call progress meter for Duplii.com" />