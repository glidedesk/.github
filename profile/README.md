<div align="center">
  <img src="https://raw.githubusercontent.com/glidedesk/glidedesk/main/src-tauri/icons/128x128@2x.png" width="120" alt="GlideDesk Logo">
  <h1>GlideDesk</h1>
  <p><b>Lightweight, Zero-Latency Multi-Device Software KVM</b></p>
  <p>Share one mouse, keyboard, and clipboard seamlessly across <b>macOS</b>, <b>Windows</b>, <b>Linux</b>, and <b>Android</b>.</p>

  <p>
    <a href="https://github.com/glidedesk/glidedesk/releases/latest"><img src="https://img.shields.io/github/v/release/glidedesk/glidedesk?color=00c853&label=Release" alt="Latest Release"></a>
    <img src="https://img.shields.io/badge/Tauri-v2.0-24c8db" alt="Tauri v2">
    <img src="https://img.shields.io/badge/Rust-1.78%2B-dea584" alt="Rust">
    <img src="https://img.shields.io/badge/macOS%20%7C%20Windows%20%7C%20Linux%20%7C%20Android-Supported-blue" alt="Cross Platform">
    <img src="https://img.shields.io/badge/License-GPL--3.0-blue" alt="License">
  </p>
</div>

---

### ⚡ Why GlideDesk?

GlideDesk re-engineers the software KVM experience from the ground up to solve the latency, battery drain, and input collision issues common in legacy tools:

- 🚀 **15x Lower Memory**: Runs on **~28 MB RAM** via native OS webviews (WebKit / WebView2) compared to 500 MB – 1 GB+ in Electron alternatives.
- ⚡ **Zero-GC Latency**: Powered by an asynchronous Rust engine with deterministic event dispatch and zero stop-the-world garbage collection pauses.
- 🛡️ **Dual-Input & Gesture Isolation**: Strict 3-state input machine (`home`, `driving`, `driven`) prevents fighting between laptop precision touchpads and external mice. Laptop gestures stay local and won't accidentally trigger destructive minimize actions on remote Macs.
- 🪟 **Single-Window Edge Handoff**: Drag individual application windows across screen borders (`Ctrl`/`Cmd` + Drag) to project and control them on adjacent computers.
- 📋 **Unified Real-Time Clipboard**: Instant text, code snippet, and PNG/JPEG image synchronization with hardware-level loopback echo suppression.
- 📱 **Native Android Companion**: Ultra-lightweight native Kotlin app providing wireless second screen display, phone trackpad, and notification mirroring with 24/7 background persistence.

---

### 📥 1-Line Quick Install

| Platform | Quick Command |
| :--- | :--- |
| **macOS** | `curl -fsSL https://raw.githubusercontent.com/glidedesk/glidedesk/main/mac/scripts/install.sh \| bash` |
| **Windows** | `irm https://raw.githubusercontent.com/glidedesk/glidedesk/main/windows/scripts/install.ps1 \| iex` |
| **Linux** | `curl -fsSL https://raw.githubusercontent.com/glidedesk/glidedesk/main/linux/scripts/install.sh \| bash` |
| **Android** | `adb install -r GlideDesk-1.1.1.apk` or direct download from [Releases](https://github.com/glidedesk/glidedesk/releases/latest) |

---

### 📦 Primary Repository

- **[`glidedesk/glidedesk`](https://github.com/glidedesk/glidedesk)** — Main codebase, native OS runners, background daemons, and Android companion.

---

<div align="center">
  <sub>Maintained with ❤️ by the GlideDesk Team & Open Source Contributors.</sub>
</div>
