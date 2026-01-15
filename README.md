# Link Browser

Link Browser is an ultra minimalistic Android app. It just opens web links without a normal browser interface. You won't find it in your app drawer; it only pops up when you tap a link from another app.

I made this app for digital detox. If you've ditched your main browser, but still need to open a link now and then (like for an app login or a chat message), this tool lets you do that without the distraction of a full browser.

## Building

This project can be built using Android Studio or the included Gradle wrapper.

To build the project from the command line, run the following command in the project's root directory:

```bash
./gradlew assembleRelease
```

### Dependencies

*   Android SDK: `34`
*   Android Gradle Plugin: `8.2.0`
*   Java: `8`