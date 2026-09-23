<p align="center">
	<img src="logo.png" width="376" height="128" alt="Winlator Logo" />  
</p>

# Winlator

Winlator is an Android application that lets you run Windows (x86_64) applications with Wine and Box86/Box64.

This fork includes **[VKWIND](https://github.com/ggt64818-sys/vkwind)** (D3D9→Vulkan) and **[VKWIND11](https://github.com/ggt64818-sys/vkwind11)** (D3D10/11/12→Vulkan) translation layers built in — no separate DXVK download needed.

## VKWIND Integration

Select in Container Settings → DXVK/VKD3D:

| Option | Select | Translates |
|---|---|---|
| DXVK Version | `vkwind-0.5.2` | D3D9 games |
| DXVK Version | `vkwind11-0.2.0` | D3D11 games |
| VKD3D Version | `vkwind11-0.2.0` | D3D12 games |

# Installation

1. Download and install the APK from [GitHub Releases](https://github.com/ggt64818-sys/winlator/releases)
2. Launch the app and wait for the installation process to finish

----

[![Play on Youtube](https://img.youtube.com/vi/8PKhmT7B3Xo/1.jpg)](https://www.youtube.com/watch?v=8PKhmT7B3Xo)
[![Play on Youtube](https://img.youtube.com/vi/9E4wnKf2OsI/2.jpg)](https://www.youtube.com/watch?v=9E4wnKf2OsI)
[![Play on Youtube](https://img.youtube.com/vi/czEn4uT3Ja8/2.jpg)](https://www.youtube.com/watch?v=czEn4uT3Ja8)
[![Play on Youtube](https://img.youtube.com/vi/eD36nxfT_Z0/2.jpg)](https://www.youtube.com/watch?v=eD36nxfT_Z0)

----

# Useful Tips

- If you are experiencing performance issues, try changing the Box86/Box64 preset in Container Settings -> Advanced Tab.
- For applications that use .NET Framework, try installing Wine Mono found in Start Menu -> System Tools.
- If some older games don't open, try adding the environment variable MESA_EXTENSION_MAX_YEAR=2003 in Container Settings -> Environment Variables.
- Try running the games using the shortcut on the Winlator home screen, there you can define individual settings for each game.
- To speed up the installers, try changing the Box86/Box64 preset to Intermediate in Container Settings -> Advanced Tab.

# Credits and Third-party apps
- Ubuntu RootFs ([Focal Fossa](https://releases.ubuntu.com/focal))
- Wine ([winehq.org](https://www.winehq.org/))
- Box86/Box64 by [ptitseb](https://github.com/ptitSeb)
- PRoot ([proot-me.github.io](https://proot-me.github.io))
- Mesa (Turnip/Zink/VirGL) ([mesa3d.org](https://www.mesa3d.org))
- DXVK ([github.com/doitsujin/dxvk](https://github.com/doitsujin/dxvk))
- VKD3D ([gitlab.winehq.org/wine/vkd3d](https://gitlab.winehq.org/wine/vkd3d))
- D8VK ([github.com/AlpyneDreams/d8vk](https://github.com/AlpyneDreams/d8vk))
- CNC DDraw ([github.com/FunkyFr3sh/cnc-ddraw](https://github.com/FunkyFr3sh/cnc-ddraw))
- VKWIND ([github.com/ggt64818-sys/vkwind](https://github.com/ggt64818-sys/vkwind)) — D3D9 to Vulkan
- VKWIND11 ([github.com/ggt64818-sys/vkwind11](https://github.com/ggt64818-sys/vkwind11)) — D3D10/11/12 to Vulkan

Many thanks to [ptitSeb](https://github.com/ptitSeb) (Box86/Box64), [Danylo](https://blogs.igalia.com/dpiliaiev/tags/mesa/) (Turnip), [alexvorxx](https://github.com/alexvorxx) (Mods/Tips) and others.
Thank you to all the people who believe in this project.