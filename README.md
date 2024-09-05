
[![](https://jitpack.io/v/com.vuzix/hud-actionmenu.svg)](https://jitpack.io/#com.vuzix/hud-actionmenu)

![Vuzix Logo](https://apps.vuzix.com/images/vuzix-logo-old.png)
# HUD Action Menu SDK
Use this library for creating a menu-based user-interface ideal for use on the our line of Android
enabled Vuzix smart glasses, including VUZIX M400™, VUZIX M4000™, VUZIX SHIELD™, VUZIX BLADE®, and
VUZIX BLADE 2™. 

## Requirements
- Compatible Vuzix smart glasses

## Installation
1. Add JitPack as a maven repository in settings.gradle or settings.gradle.kts at the top level of your Android Studio project:
```
dependencyResolutionManagement {
    repositoriesMode.set(RepositoriesMode.FAIL_ON_PROJECT_REPOS)
    repositories {
        ...
        maven { url "https://jitpack.io" } // if using settings.gradle
        maven ("https://jitpack.io")       // if using settings.gradle.kts
    }
}
```
2. Add hud-actionmenu to your module's build.gradle or build.gradle.kts file. Replace VERSION below with the version of the SDK you wish to use.
```
dependencies {
    ...
    implementation 'com.vuzix:hud-actionmenu:VERSION'   // if using build.gradle
    implementation ("com.vuzix:hud-actionmenu:VERSION") // if using build.gradle.kts
    ...
}
```
The latest hud-actionmenu version on JitPack is [![](https://jitpack.io/v/com.vuzix/hud-actionmenu.svg)](https://jitpack.io/#com.vuzix/hud-actionmenu).

Please note, the latest version uses Jetpack libraries. This is the recommended version, and has
compatibility with the vast majority of modern Android projects.

A legacy version can be retrieved from the 1.13.0 tag for projects not built on Android Jetpack.

## Documentation
API level documentation is available in [javadoc](https://vuzix.github.io/hud-actionmenu/javadoc).

The Developer Center on [vuzix.com](https://www.vuzix.com) includes articles and samples describing how to create applications using this library.

## Legal
Use of the SDK is available to developers agreeing to the
[VUZIX® SOFTWARE DEVELOPMENT KIT LICENSE AND CONFIDENTIALITY AGREEMENT](https://www.vuzix.com/pages/vuzix%C2%AE-software-development-kit-license-and-confidentiality-agreement)
