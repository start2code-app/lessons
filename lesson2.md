# lesson2


## lesson 2
Create a variable called ``||Variables:frame||``

```blocks
let frame = 0
```

## Step2 

Code the following

```blocks
let frame = 0
basic.forever(function () {
    if (frame == 0) {
        led.plot(0, 0)
    }
    if (frame == 1) {
        led.plot(1, 1)
    }
    if (frame == 2) {
        led.plot(2, 2)
    }
    if (frame == 3) {
        led.plot(3, 3)
    }
    if (frame == 4) {
        led.plot(4, 4)
    }
    if (frame == 5) {
        frame = 0
        basic.clearScreen()
    } else {
        frame += 1
    }
    basic.pause(300)
})

```

## End

Congratulations ! You have completed the task

<script src="https://makecode.com/gh-pages-embed.js"></script><script>makeCodeRender("{{ site.makecode.home_url }}", "{{ site.github.owner_name }}/{{ site.github.repository_name }}");</script>
