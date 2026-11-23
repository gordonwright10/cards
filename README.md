# Easy Solitaire

Big, simple Klondike Solitaire (draw 1) for older eyes. Sideload `Solitaire.apk`.

- Install: copy `Solitaire.apk` to the tablet, open it, allow "install unknown apps" when asked. Requires Android 7+.
- Game is `www/index.html` (single file). To rebuild the APK: `npm install && npx cap sync android && cd android && ./gradlew assembleDebug`.
