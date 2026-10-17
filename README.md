# Geronfir

[![lexiclock build](https://github.com/Geronfir/Lexiclock/actions/workflows/build.yml/badge.svg)](https://github.com/Geronfir/Lexiclock/actions/workflows/build.yml)
[![lexiclock release](https://img.shields.io/github/v/release/Geronfir/Lexiclock?label=lexiclock&color=blue)](https://github.com/Geronfir/Lexiclock/releases)

**Android (Kotlin) + embedded + Linux-tooling developer — I build, test and ship real software from an Android phone.** No laptop, no PC.

I develop entirely on an Android phone: a full Linux environment via **Termux + proot (Debian)**, a persistent **tmux** workspace, **ESP32-S3 firmware flashed over Wi-Fi OTA**, and **GitHub Actions as my build machine**. Everything below was written, compiled, tested and released from that device.

Constraints force discipline — no desktop IDE means scripted, reproducible builds; a small CPU and tight RAM mean lean, deliberate code. I ship anyway.

---

### Featured work

**[voxnova-esp32](https://github.com/Geronfir/Voxnova-esp32)** — real-time AI voice assistant on an **ESP32-S3**: I2S mic in, audio streamed to the **Gemini Live API** through a **Cloudflare Workers + Durable Objects** relay, spoken reply out. C++/PlatformIO firmware, TypeScript edge layer, Python flash tooling. Adapted from Nova AI.

**[lexiclock](https://github.com/Geronfir/Lexiclock)** — Android home-screen widget that spells the time in words. The time-to-words engine is pure Kotlin with **no Android imports**, so all **71 unit tests run on a plain JVM** in CI. Jetpack Glance, Material 3, offline-first, no background service.

**termux-workstation** *(private)* — how I turned an Android phone into a real dev box: tmux sessions that survive app restarts, a Debian userland via proot, shell tooling that pushes build results to the phone, and CI as the build machine. Docs + sanitized configs.

**[geronfir.github.io](https://geronfir.github.io)** — portfolio with case studies for the projects above.

### Stack

`Kotlin` · `Android` · `Jetpack Compose / Glance` · `Python` · `C++ / PlatformIO` · `TypeScript` · `Bash` · `Linux (Termux, proot)` · `ESP32-S3` · `Cloudflare Workers` · `Git` · `GitHub Actions`

### Contact

[Email](mailto:whichrisy@gmail.com) · [Portfolio](https://geronfir.github.io) · [GitHub](https://github.com/Geronfir)

<sub>Built from an Android phone. Yes, really.</sub>
