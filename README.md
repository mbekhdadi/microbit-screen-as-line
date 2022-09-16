
> Open this page at [https://mbekhdadi.github.io/microbit-screen-as-line/](https://mbekhdadi.github.io/microbit-screen-as-line/)

## Usage

### ``plotat``

Use the ``plotAt`` block to render LEDs at an index location.

```blocks
basic.forever(function () {
    for (let index = 0; index <= 25; index++    ) {
        screenMagic.plotAt(index)
        basic.pause(100)
    }
}
```

## Use as Extension

This repository can be added as an **extension** in MakeCode.

* open [https://makecode.microbit.org/](https://makecode.microbit.org/)
* click on **New Project**
* click on **Extensions** under the gearwheel menu
* search for **https://github.com/mbekhdadi/microbit-screen-as-line** and import

## Edit  this project ![Build status badge](https://github.com/mbekhdadi/microbit-screen-as-line/workflows/MakeCode/badge.svg)

To edit this repository in MakeCode.

* open [https://makecode.microbit.org/](https://makecode.microbit.org/)
* click on **Import** then click on **Import URL**
* paste **https://github.com/mbekhdadi/microbit-screen-as-line** and click import

## Blocks preview

This image shows the blocks code from the last commit in master.
This image may take a few minutes to refresh.

![A rendered view of the blocks](https://github.com/mbekhdadi/microbit-screen-as-line/raw/master/.github/makecode/blocks.png)

#### Metadata (used for search, rendering)

* for PXT/microbit
<script src="https://makecode.com/gh-pages-embed.js"></script><script>makeCodeRender("{{ site.makecode.home_url }}", "{{ site.github.owner_name }}/{{ site.github.repository_name }}");</script>
