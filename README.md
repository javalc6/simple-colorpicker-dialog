# ColorPickerDialog

The ColorPickerDialog class is a simple color picker dialog for Android platform, tested with API >= 17 (JELLY_BEAN_MR1).
This class is very simple, by design.

The user can display a dialog with a user provided palette of colors, that will be displayed either as circles or squares.
The color selected is displayed as bigger circle or square.

The dialog is set up by invoking the following constructor:
```
ColorPickerDialog(Context context, int initialColor, String title, int[] colors, int mode, OnColorChangedListener listener)

initialColor: initial selected color
title: the title of the dialog
colors: user provided palette
mode: squares or circles
listener: used to return the color selected by user
```

The color selected by the user is reported via the OnColorChangedListener interface.

The file dimens.xml shall be stored under folder res\values.

# Screenshot

The following example is related to a device running JELLY_BEAN_MR1:


![Screenshot](https://raw.githubusercontent.com/javalc6/simple-colorpicker-dialog/master/screenshot_api17.png)
