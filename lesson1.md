# lessons


## lesson 1
When the micro:bit starts ``||basic:Clear the Screen||`` and using the ``||led:plot||`` command switch on the LED at the center of
the microbit.

![A animation that shows how to create a variable](/lessons/static/hand.jpg)

```blocks
basic.clearScreen()
led.plot(2, 2)

input.onButtonPressed(Button.A, function () {
    basic.clearScreen()
    led.plot(0, 0)
    led.plot(1, 1)
    led.plot(2, 2)
    led.plot(3, 3)
    led.plot(4, 4)
})

input.onButtonPressed(Button.B, function () {
    basic.clearScreen()
    led.plot(4, 0)
    led.plot(3, 1)
    led.plot(2, 2)
    led.plot(1, 3)
    led.plot(0, 4)
})

input.onButtonPressed(Button.AB, function () {
    basic.clearScreen()
    led.plot(4, 0)
    led.plot(3, 0)
    led.plot(2, 0)
    led.plot(1, 0)
    led.plot(0, 0)

    led.plot(4, 0)
    led.plot(3, 1)
    led.plot(2, 2)
    led.plot(1, 3)
    led.plot(0, 4)

    led.plot(4, 4)
    led.plot(3, 4)
    led.plot(2, 4)
    led.plot(1, 4)
    led.plot(0, 4)

})

input.onGesture(Gesture.Shake, function () {
    basic.clearScreen()
    led.plot(0, 0)
    led.plot(4, 0)
    led.plot(2, 2)
    led.plot(0, 4)
    led.plot(4, 4)


})

```

## End

Congratulations ! You have completed the task

<script src="https://makecode.com/gh-pages-embed.js"></script><script>makeCodeRender("{{ site.makecode.home_url }}", "{{ site.github.owner_name }}/{{ site.github.repository_name }}");</script>
