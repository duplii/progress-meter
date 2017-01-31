# Progress meter

This is a progress meter built with css animations and gradients.

The animation will be toggled by clicking on the little text below the meter. This will mimick our app's real needs, where we will have to trigger the animation on call start and stop it on call-end.

The timer here is set at 9 seconds for demonstration purposes, while for the real app it will probably be around 90s. This is a reasonable time for our use-case, but it can easily be changed in the future by modifying the sass variable `$animation-duration`.

When the timer expires, the circle will turn red and start pulsing to signal that the time is elapsed.

Only the styles contained in `animation.scss` are relevant to the animation itself. The styles in style.scss are just for presentational purposes. Take a look at `index.html` to see how we are using JavaScript here.

I am also including the `config.codekit` file so that everyone using Codekit will be able to get started immediately.

## Live demo

A live demo of this project can be found at [duplii.github.io/progress-meter](http://duplii.github.io/progress-meter "Duplii | Progress meter demo").

<img src="http://duplii.s3.amazonaws.com/call-progress.jpg" width="463" height="275" alt="Call progress meter for Duplii.com" />