## Class: TouchBarPopover

> Create a popover in the touch bar for native macOS applications

Process: [Main](../tutorial/quick-start.md#main-process)

### `new TouchBarPopover(options)`

* `options` Object
  * `label` String (optional) - Popover button text.
  * `icon` NativeImage (optional) - Popover button icon.
  * `items` TouchBar (optional) - Items to display in the popover.
  * `showCloseButton` Boolean (optional) - `true` to display a close button
    on the left of the popover, `false` to not show it. Default is `true`.

### Instance Properties

The following properties are available on instances of `TouchBarPopover`:

#### `touchBarPopover.label`

The popover's current button text. Changing this value immediately updates the
popover in the touch bar.

#### `touchBarPopover.icon`

The popover's current button icon. Changing this value immediately updates the
popover in the touch bar.