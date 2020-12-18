# addingblockimages
Get a ``||input:temperature||`` block and place it in the value slot of ``||basic:show number||``.

```blocks
basic.forever(function () {
    basic.showNumber(input.temperature())
})
```
