# First try at using neopixel ring with micro:bit

## Step 1 - Adding Extensions @unplugged
To be able to code the micro:bit to use and control the neopixel ring, a new library or extension needs to be added. After watching the animation below, add the neopixel extension. 

![Adding NeoPixel Extension.](https://raw.githubusercontent.com/rypsmith/neopixel-ring-tutorial/master/neoPixelExtension.gif)

## Step 2 - Initialize the neoPixelExtension
I wonder how to place NeoPixel blocks?

```blocks
let strip = neopixel.create(DigitalPin.P0, 12, NeoPixelMode.RGB)
basic.forever(function () {

})
```

## Step 3
Hi?

<script src="https://makecode.com/gh-pages-embed.js"></script><script>makeCodeRender("{{ site.makecode.home_url }}", "{{ site.github.owner_name }}/{{ site.github.repository_name }}");</script>