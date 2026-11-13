SadSha 2048
===========

SadSha's Android port of the 2048 puzzle game, made by Gabriele Cirulli https://github.com/gabrielecirulli/2048
It's nothing fancy; just a WebView that loads the locally stored html files of the original game.
Playable instantly without internet (the app doesn't require any permissions), with
a quick access icon for your smartphone. No ads.

Based on the 2048-android port by uberspot https://github.com/uberspot/2048-android
(rebranded to SadSha, toolchain modernised to AGP 8.2 / Gradle 8.2 / SDK 34).

## Building

Requires JDK 17 and the Android SDK (API 34). Build from source with:

    git clone https://github.com/rembghd/2048-android.git
    cd 2048-android
    ./gradlew build

### With Android Studio

1. Follow the lines above to clone the repo.
2. In Android Studio select "Open an existing Android Studio Project".
3. When prompted, add the VCS root.

## License

SadSha 2048 is licensed under the [MIT license](LICENSE).
The 2048 web game bundled under `assets/2048` is MIT licensed by Gabriele Cirulli
(see `assets/2048/LICENSE.txt`).
