<p align="center">
	<img src="logo.png?v=2" width="376" height="128" alt="WinDri Logo" />
</p>

# WinDri

WinDri is an Android application based on [Winlator](https://github.com/brunodev85/winlator) that lets you run Windows (x86_64) applications with Wine and Box86/Box64.

# Installation

1. Download and install the APK from [GitHub Releases](https://github.com/LUAN228/WinDri/releases)
2. Launch the app and wait for the installation process to finish

----

# Useful Tips

- If you are experiencing performance issues, try changing the Box64 preset to `Performance` in Container Settings -> Advanced Tab.
- For applications that use .NET Framework, try installing `Wine Mono` found in Start Menu -> System Tools -> Installers.
- If some older games don't open, try adding the environment variable `MESA_EXTENSION_MAX_YEAR=2003` in Container Settings -> Environment Variables.
- Try running the games using the shortcut on the WinDri home screen, there you can define individual settings for each game.
- To display low resolution games correctly, try enabling the `Force Fullscreen` option in the shortcut settings.
- To improve stability in games that use Unity Engine, try changing the Box64 preset to `Stability` or in the shortcut settings add the exec argument `-force-gfx-direct`.
- If you are experiencing audio crackling, try increasing the average latency in ALSA/PulseAudio configuration. Old games like Unreal Gold resolve audio issues by increasing this value to 90ms.

# Credits and Third-party apps

- Based on **Winlator** by [brunodev85](https://github.com/brunodev85/winlator)
- GLIBC Patches by [Termux Pacman](https://github.com/termux-pacman/glibc-packages)
- Wine ([winehq.org](https://www.winehq.org/))
- Box86/Box64 by [ptitseb](https://github.com/ptitSeb)
- Mesa (Turnip/Zink/VirGL) ([mesa3d.org](https://www.mesa3d.org))
- DXVK ([github.com/doitsujin/dxvk](https://github.com/doitsujin/dxvk))
- VKD3D ([gitlab.winehq.org/wine/vkd3d](https://gitlab.winehq.org/wine/vkd3d))
- CNC DDraw ([github.com/FunkyFr3sh/cnc-ddraw](https://github.com/FunkyFr3sh/cnc-ddraw))

Special thanks to all the developers involved in these projects.<br>
Thank you.
