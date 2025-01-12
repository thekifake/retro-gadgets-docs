# ScreenButton

<img src="https://docs.retrogadgets.game/api/modules/ScreenButton.png" width="200" align="right">

The Screen Button is a combination of both a button and [Screen](../output/Screen.md). As such, it functions as both an input and output device. **It is sorted under Input.**


## Properties

### VideoChip - `VideoChip`
The [VideoChip](../misc/VideoChip.md) the [Screen](../output/Screen.md) part of this button is bound to.

### ButtonState - `boolean` **[Read only]**
`true` if the button is currently held down, `false` otherwise.

### ButtonDown - `boolean` **[Read only]**
`true` for the first tick the button starts being held. Useful for performing actions only one time per hold.

### ButtonUp - `boolean` **[Read only]**
`true` for the first tick the button stops being held. 


## Input sources
Properties for use with the [GamepadChip](../misc/GamepadChip.md) or [KeyboardChip](../misc/KeyboardChip.md).

### InputSource - `InputSource`