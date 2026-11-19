# StremCompat

<p align="center"><img src="assets/stremcompat-hero-en.png" alt="StremCompat home screen" width="1000"></p>

<p align="center">
  <img alt="LG webOS 3 and newer" src="https://img.shields.io/badge/LG%20webOS-3%20and%20newer-0F766E">
  <img alt="Samsung Tizen 4 and newer" src="https://img.shields.io/badge/Samsung%20Tizen-4%20and%20newer-0F766E">
  <img alt="Android TV 7.0 and newer" src="https://img.shields.io/badge/Android%20TV-7.0%20and%20newer-0F766E">
  <img alt="No root required" src="https://img.shields.io/badge/root-not%20required-2ea44f">
  <a href="https://buymeacoffee.com/Alexesmm"><img alt="Buy me a coffee" src="https://img.shields.io/badge/support-Buy%20me%20a%20coffee-ffdd00?logo=buymeacoffee&logoColor=black"></a>
</p>

<p align="center"><b>English</b> · <a href="README.pt.md">Português</a></p>

Your Stremio or Nuvio account and addons on TVs the official apps left behind: older LG webOS sets, Samsung Tizen and Android TV. Unofficial, free, and it needs no root.

## Pick your TV

| TV | Download and install |
|---|---|
| **LG** (webOS 3 and newer) | [StremCompat/webos](https://github.com/StremCompat/webos) |
| **Samsung** (Tizen 4 and newer) | [StremCompat/samsung](https://github.com/StremCompat/samsung) |
| **Android TV / Google TV** (7.0 and newer) | [StremCompat/android-tv](https://github.com/StremCompat/android-tv) |

## Two versions, side by side

Every TV has both, and they can be installed together:

| | **StremCompat** | **StremCompat Native** |
|---|---|---|
| What it is | The interface as a web page, the original version of the app | The same app rewritten in C, drawn by the TV's own graphics chip |
| Best for | Everyday use | Weaker TVs, or anyone who wants the smoothest scrolling |
| Status | **Stable, recommended** | **Beta**, not stable yet: faster, but expect rough edges |

Your account, library and settings carry over: on its first start the native version takes them from the web one, so there is no need to sign in again.

## A look inside

<table>
  <tr>
    <td><img src="assets/screens/home.jpg" alt="Home" width="100%"></td>
    <td><img src="assets/screens/series.jpg" alt="Series page" width="100%"></td>
  </tr>
  <tr>
    <td><img src="assets/screens/channels.jpg" alt="Live channels" width="100%"></td>
    <td><img src="assets/screens/store.jpg" alt="Addon store" width="100%"></td>
  </tr>
</table>

## Source code

| Repository | What is in it |
|---|---|
| [stremcompat](https://github.com/StremCompat/stremcompat) | The local server both versions use, and the web interface |
| [native](https://github.com/StremCompat/native) | The native interface in C (SDL2, OpenGL ES) |

StremCompat is not affiliated with Stremio, Nuvio, LG, Samsung or Google. It plays what your own addons provide.

If it has been useful to you, you can [buy me a coffee ☕](https://buymeacoffee.com/Alexesmm). Entirely optional.
