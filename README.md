# Hi, I'm @dmillerzx

I maintain **native ARM64 Android ports** (static recompilations & decompilations) and **zero-touch handheld provisioning tools** verified on **Retroid Pocket 5** (Snapdragon 865 / Adreno 650, Android 13, 1080p 60 FPS).

[![Android 13](https://img.shields.io/badge/Android-ARM64-3DDC84?logo=android&logoColor=white)](https://github.com/dmillerzx/handheld-antigravity-toolkit)
[![SoC](https://img.shields.io/badge/Snapdragon_865-Adreno_650-E02F44)](https://github.com/dmillerzx/handheld-antigravity-toolkit)
[![Obtainium](https://img.shields.io/badge/Obtainium-Auto_Updates-6A5ACD)](https://github.com/dmillerzx/handheld-antigravity-toolkit/blob/main/configs/rp5_master_obtainium.json)

---

## Native Android Ports

All ports ship **source-only APKs** (bring your own legally obtained game files/ROMs) with full physical controller support and Obtainium-compatible GitHub Releases:

| Game | Platform | Renderer | Repository | Latest Release |
| :--- | :--- | :--- | :--- | :--- |
| **OutRun 2006: Coast 2 Coast** | PC / Arcade | SDL2 + OpenGL ES 3.0 | [dmillerzx/outrun2-decomp](https://github.com/dmillerzx/outrun2-decomp) | [Download APK](https://github.com/dmillerzx/outrun2-decomp/releases/latest) |
| **Castlevania: Symphony of the Night (Ultimate v1.4)** | PlayStation (PS1) | OpenGL ES 3.0 | [dmillerzx/SymphonyRecomp-Ultimate-Android](https://github.com/dmillerzx/SymphonyRecomp-Ultimate-Android) | [Download APK](https://github.com/dmillerzx/SymphonyRecomp-Ultimate-Android/releases/latest) |
| **Diddy Kong Racing Recompiled (DKR-R)** | Nintendo 64 | RT64 Vulkan | [dmillerzx/DKR-R](https://github.com/dmillerzx/DKR-R) | [Download APK](https://github.com/dmillerzx/DKR-R/releases/latest) |
| **Banjo-Kazooie Recompiled** | Nintendo 64 | RT64 Vulkan + AdrenoTools | [dmillerzx/BanjoRecomp-Android](https://github.com/dmillerzx/BanjoRecomp-Android) | [Download APK](https://github.com/dmillerzx/BanjoRecomp-Android/releases/latest) |

---

## Handheld Tooling & Automation

- **[handheld-antigravity-toolkit](https://github.com/dmillerzx/handheld-antigravity-toolkit)** — Zero-touch ADB provisioning, configuration snapshotting, save synchronization, emulator tuning, and a master [Obtainium manifest](https://github.com/dmillerzx/handheld-antigravity-toolkit/blob/main/configs/rp5_master_obtainium.json) for Retroid Pocket 5.
- **[Obtainium-Emulation-Pack](https://github.com/dmillerzx/Obtainium-Emulation-Pack)** — Curated Obtainium emulation & native port import pack.

---

## Credits

All native ports build on the incredible work of upstream decompilation, recompilation, and renderer authors (including ThatGuyMcd, AurelioB, sergiomanzur, N64Recomp, RT64, RecompOne, and ylaws/libadrenotools).