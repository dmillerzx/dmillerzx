I maintain **native ARM64 Android ports** (static recompilations & decompilations) and **zero-touch handheld provisioning tools** verified on **Retroid Pocket 5** (Snapdragon 865 / Adreno 650, Android 13, 1080p 60 FPS).

[![Android 13](https://img.shields.io/badge/Android-ARM64-3DDC84?logo=android&logoColor=white)](https://github.com/dmillerzx/handheld-antigravity-toolkit)
[![SoC](https://img.shields.io/badge/Snapdragon_865-Adreno_650-E02F44)](https://github.com/dmillerzx/handheld-antigravity-toolkit)
[![Obtainium](https://img.shields.io/badge/Obtainium-Auto_Updates-6A5ACD)](https://github.com/dmillerzx/handheld-antigravity-toolkit/blob/main/configs/rp5_master_obtainium.json)
[![GitHub Sponsors](https://img.shields.io/badge/Sponsor-dmillerzx-ea4aaa?logo=githubsponsors&logoColor=white)](https://github.com/sponsors/dmillerzx)
[![Ko-fi](https://img.shields.io/badge/Ko--fi-dmillerzx-FF5E5B?logo=ko-fi&logoColor=white)](https://ko-fi.com/dmillerzx)

---

## Native Android Ports

All ports ship **source-only APKs** (bring your own legally obtained game files/ROMs) with physical controller support, 16:9 widescreen, and Obtainium-compatible GitHub Releases:

| Game | Platform | Renderer | Highlights | Repository | Latest Release |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **OutRun 2006: Coast 2 Coast** | PC / Arcade | SDL2 + OpenGL ES 3.0 | 60 FPS, widescreen, Xbox/PC asset support | [dmillerzx/outrun2-decomp](https://github.com/dmillerzx/outrun2-decomp) | [![Release](https://img.shields.io/github/v/release/dmillerzx/outrun2-decomp?label=APK)](https://github.com/dmillerzx/outrun2-decomp/releases/latest) |
| **Castlevania: Symphony of the Night Ultimatee** | PlayStation (PS1) | OpenGL ES 3.0 | Ultimate v1.5, 16:9 room fills, QoL | [dmillerzx/SymphonyRecomp-Ultimate-Android](https://github.com/dmillerzx/SymphonyRecomp-Ultimate-Android) | [![Release](https://img.shields.io/github/v/release/dmillerzx/SymphonyRecomp-Ultimate-Android?label=APK)](https://github.com/dmillerzx/SymphonyRecomp-Ultimate-Android/releases/latest) |
| **Diddy Kong Racing Recompiled (DKR-R)** | Nintendo 64 | RT64 Vulkan | 1080p 60 FPS, Track Lab, rollback netplay | [dmillerzx/DKR-R](https://github.com/dmillerzx/DKR-R) | [![Release](https://img.shields.io/github/v/release/dmillerzx/DKR-R?label=APK)](https://github.com/dmillerzx/DKR-R/releases/latest) |
| **Banjo-Kazooie Recompiled** | Nintendo 64 | RT64 Vulkan + AdrenoTools | 16:9 widescreen, Turnip loader, dual-trigger crouch | [dmillerzx/BanjoRecomp-Android](https://github.com/dmillerzx/BanjoRecomp-Android) | [![Release](https://img.shields.io/github/v/release/dmillerzx/BanjoRecomp-Android?label=APK)](https://github.com/dmillerzx/BanjoRecomp-Android/releases/latest) |

---

## Handheld Tooling & Automation

- **[handheld-antigravity-toolkit](https://github.com/dmillerzx/handheld-antigravity-toolkit)** — Zero-touch ADB provisioning, configuration snapshotting, save synchronization, emulator tuning, and a master [Obtainium manifest](https://github.com/dmillerzx/handheld-antigravity-toolkit/blob/main/configs/rp5_master_obtainium.json) for Retroid Pocket 5.
- **[Obtainium-Emulation-Pack](https://github.com/dmillerzx/Obtainium-Emulation-Pack)** — Curated Obtainium emulation & native port import pack for automatic APK updates.

---

## Credits

All native ports build on the work of upstream decompilation, recompilation, and renderer authors, including:
- **Upstream Projects**: [ThatGuyMcd](https://github.com/ThatGuyMcd), [AurelioB](https://github.com/AurelioB), [sergiomanzur/SymphonyRecomp](https://github.com/sergiomanzur/SymphonyRecomp), [renanbianchi/sotn-ultimate](https://github.com/renanbianchi/sotn-ultimate), [N64Recomp](https://github.com/N64Recomp/N64Recomp), [RT64](https://github.com/rt64/rt64), RecompOne, and [bylaws/libadrenotools](https://github.com/bylaws/libadrenotools).

---

## Quick FAQ

- **Where do I get game data?** All repositories and APKs are strictly **source-only** (bring your own legally dumped PC files or console ROMs/disc images).
- **How do I stay updated?** Import [obtainium-emulation-pack-latest.json](https://github.com/dmillerzx/Obtainium-Emulation-Pack/releases/latest) into [Obtainium](https://github.com/ImranR98/Obtainium) for automatic APK update notifications straight from GitHub Releases.
- **Found a bug or want to share device results?** Open a structured **Bug Report** in Issues or share compatibility feedback for other Snapdragon / Adreno handhelds in each repo's **Discussions** tab.
