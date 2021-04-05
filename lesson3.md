# lesson3


## lesson 3
Create a variable called ``||Variables:count||``

```blocks
let count = 0
```

## Step2 

Code the following

```blocks
let count = 0
basic.forever(function () {
    basic.clearScreen()
    basic.pause(300)
    for (let count = 0; count <= 4; count++) {
        led.plot(count, count)
        basic.pause(300)
    }
})

```

## End

Congratulations ! You have completed the task

<script src="https://makecode.com/gh-pages-embed.js"></script><script>makeCodeRender("{{ site.makecode.home_url }}", "{{ site.github.owner_name }}/{{ site.github.repository_name }}");</script>

