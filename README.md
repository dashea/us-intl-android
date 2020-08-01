# US-Intl with Dead Keys for Android

This package provides the [US International](https://en.wikipedia.org/wiki/QWERTY#US-International) keyboard layout for use with Android and external (USB, Bluetooth) keyboards.
This layout differs from the "English (US), International style" layout that comes with Android in that all diacritics (`'`, `` ` ``, `"`, `~`, `^`) are dead keys by default.

## Building

This package requires the [Android SDK](https://developer.android.com/studio).
The environment variable `ANDROID_SDK_ROOT` should be set to the location of your SDK installation.

To build the package, simply run:

`./gradlew build`

or on Windows,

`gradlew build`

## Installing

Enable [USB debugging](https://developer.android.com/studio/debug/dev-options) on your device, and connect it to your computer.

Run `./gradlew installDebug` to install the package on your device.

To use the layout, connect an external keyboard, and in settings navigate to `System -> Languages & Input -> Physical Keyboard`.
Select your keyboard, tap `Set up keyboard layouts`, and enable `English (US International with Dead Keys)`

## Bugs

Report any problems in the [github issue tracker](https://github.com/dashea/us-intl-android/issues) or by emailing reallylongword@gmail.com
