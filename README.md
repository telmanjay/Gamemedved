# Мага в городе — Android source project

Android WebView wrapper with an original Canvas-based mobile platformer prototype.

## Included
- Three level themes: Makhachkala, Dagestan mountains, Moscow
- Touch controls and keyboard controls for browser testing
- Movement, jump, melee/ranged weapon selection, enemies, coins and food power-ups
- Four hearts, pause/menu/settings, level select, Instagram link
- GitHub Actions workflow to build debug and release APKs

## Build APK using GitHub Actions
1. Upload the contents of this archive to the root of a GitHub repository (the `maga-v-gorode` folder contents should be at the repository root).
2. Open **Actions** → **Build Maga v Gorode APK** → **Run workflow**.
3. Open the completed run and download the `Maga-v-gorode-APKs` artifact.
4. Install `Maga-v-gorode-debug.apk` for testing.

## Honest status
This is a playable prototype, not a finished commercial game. The environments and characters are currently drawn with Canvas shapes/emoji rather than the cinematic painted sprites shown in the concept collage. No APK was built or device-tested in this workspace. The workflow produces APK artifacts only if the Android build succeeds.
