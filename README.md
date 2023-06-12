# IMPORANT NOTE

This project is mostly a proof of concept around creating Android keyboard layout configurations.

The behavior of the dead key mappings is dictated by Android, and much of it is unintuitive to users of dead key layouts on other systems.

For example, most users would expect `'` followed by a space to emit U+0027, the US-ASCII apostrophe character.
Instead, it emits U+00B4, the Latin-1 acute accent.
Changing this behavior is not possible without either changes to the Android API.

This repository is not maintained and will not receive any more updates.

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

## Bugs

Report any problems in the [github issue tracker](https://github.com/dashea/us-intl-android/issues) or by emailing reallylongword@gmail.com
