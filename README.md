<div align="center">

```
██╗     ███████╗ ██████╗ ██╗ ██████╗ ███╗   ██╗
██║     ██╔════╝██╔════╝ ██║██╔═══██╗████╗  ██║
██║     █████╗  ██║  ███╗██║██║   ██║██╔██╗ ██║
██║     ██╔══╝  ██║   ██║██║██║   ██║██║╚████║
███████╗███████╗╚██████╔╝██║╚██████╔╝██║ ╚███║
╚══════╝╚══════╝ ╚═════╝ ╚═╝ ╚═════╝ ╚═╝  ╚══╝
```

# 🔥 LENOVO LEGION 5 · 15ACH6H · DEVICE BIBLE 🔥
### *The most unnecessarily detailed spec page ever made for a gaming laptop*

[![CachyOS](https://img.shields.io/badge/OS-CachyOS%20KDE-00e5ff?style=for-the-badge&logo=linux&logoColor=black)](https://cachyos.org)
[![Kernel](https://img.shields.io/badge/Kernel-linux--cachyos%20BORE-7c3aed?style=for-the-badge&logo=linux&logoColor=white)](https://cachyos.org)
[![CPU](https://img.shields.io/badge/CPU-Ryzen%207%205800H-ff6b35?style=for-the-badge&logo=amd&logoColor=white)](https://www.amd.com)
[![GPU](https://img.shields.io/badge/GPU-RTX%203060%20130W-00ff88?style=for-the-badge&logo=nvidia&logoColor=black)](https://www.nvidia.com)
[![RAM](https://img.shields.io/badge/RAM-16GB%20DDR4--3200-ffd600?style=for-the-badge)](https://github.com)
[![Display](https://img.shields.io/badge/Display-165Hz%20FHD%20Dolby%20Vision-00e5ff?style=for-the-badge)](https://github.com)
[![Model](https://img.shields.io/badge/Model-82JU%20·%202021-gray?style=for-the-badge)](https://github.com)
[![Battery](https://img.shields.io/badge/Battery-80Wh%20·%20300W-00ff88?style=for-the-badge)](https://github.com)
[![License](https://img.shields.io/badge/License-Do%20Whatever%20You%20Want-ff4466?style=for-the-badge)](https://github.com)

---

> *"They said Linux gaming was impossible on a Legion laptop with an NVIDIA GPU.*
> *They were wrong. CachyOS said hold my AUR package."*

---

**[🌐 VIEW THE LIVE SITE →](https://v4cachy.github.io/Lenovo-Legion-5/)**

---

</div>

## ⚡ WHAT IS THIS?

This is a **complete, obsessively detailed hardware reference page** for the **Lenovo Legion 5 15ACH6H (Model 82JU)** running **CachyOS KDE Plasma 6**. Think of it as the manual Lenovo should have shipped — except actually useful, dark-themed, animated, and built for Linux.

No marketing fluff. No "up to" numbers. Just raw specs, real-world Linux behavior, and honest answers about what works and what doesn't on this exact machine.

---

## 🖥️ THE MACHINE

| Component | Spec |
|-----------|------|
| **Model** | Lenovo Legion 5 15ACH6H · 82JU |
| **CPU** | AMD Ryzen 7 5800H · Zen 3 · 8C/16T · 4.4 GHz Boost |
| **dGPU** | NVIDIA GeForce RTX 3060 Laptop · GA106M · **130W TGP** |
| **iGPU** | AMD Radeon Vega 8 · 8 CU · 2000 MHz |
| **RAM** | 16 GB DDR4-3200 · Dual-channel · 2× SO-DIMM |
| **Display** | 15.6" IPS · 1920×1080 · **165Hz** · Dolby Vision · FreeSync · DC Dimmer |
| **Storage** | M.2 2280 NVMe PCIe 3.0×4 |
| **Battery** | **80 Wh** · 300W barrel charger |
| **Wi-Fi** | Wi-Fi 6 (802.11ax) · Intel AX200 · BT 5.1 |
| **Keyboard** | TrueStrike · 4-zone RGB · 1.5mm travel · 100% anti-ghost |
| **BIOS** | GKCN58WW / GKCN57WW |
| **OS** | ⚡ **CachyOS KDE Plasma 6** |

---

## ⚡ WHY CACHYOS?

Because running a stock distro on a Ryzen 7 5800H is like putting regular fuel in a Formula 1 car.

```
Standard Linux distro:   x86_64 binaries  →  works, but leaving performance on the table
CachyOS:                 x86-64-v3 binaries → AVX2 + FMA + BMI2 + everything your Zen 3 has
```

**What CachyOS brings to this machine specifically:**

- 🔵 **x86-64-v3 optimized packages** — every binary compiled for your exact CPU generation. Not generic x86_64. Every. Single. Package.
- ⚡ **BORE scheduler** — Burst-Oriented Response Enhancer. Lower frame-time spikes under mixed gaming + background loads on this 8-core chip
- 🚀 **LTO + PGO + BOLT** compilation on key packages — link-time optimization, profile-guided optimization, binary layout optimization. Yes, all three.
- 🎮 **Proton-CachyOS** — a custom Proton build with Anti-Lag 2 and FSR4 ML patches baked in
- 📦 **AUR access** — if software exists on Linux, it's in the AUR. One command away.
- ⚙️ **amd-pstate driver** — smarter CPU P-state control than the old acpi-cpufreq. Better clocks, better efficiency.

---

## 🎮 GAMING ON LINUX — THE REAL NUMBERS

```
❌ Misconception:  "Linux gaming is way worse than Windows"
✅ Reality:        It depends entirely on the game and API
```

| Game API | Linux Performance vs Windows |
|----------|------------------------------|
| Vulkan-native | ~95–100% 🟢 |
| DX12 via VKD3D-Proton | ~90–95% 🟢 |
| DX11 via DXVK | ~92–97% 🟢 |
| DX9 via DXVK | ~95–99% 🟢 |
| Ray Tracing titles | ~70–80% 🟡 |
| EAC/BattlEye (where enabled) | ~95% 🟢 |
| Valorant / R6 Siege | ❌ Not supported |

> **CachyOS recovers additional performance** through kernel + package optimizations vs standard distros on the same hardware.

---

## 🖥️ THE SITE FEATURES

The [live page](https://v4cachy.github.io/Lenovo-Legion-5/) is a single self-contained HTML file with:

- 🌌 **Particle canvas** — 90 animated dots with connecting lines across the full background
- 📺 **Moving scanlines** — subtle CRT-style overlay across the entire page
- 🔤 **Glitch effect** — the title randomly glitches like a corrupted BIOS screen
- ✍️ **Typewriter animation** — text types itself out on page load
- 🔵 **Radar ping** — pulsing dot on the recommended GPU mode card
- 📦 **Scroll reveal** — every card slides in as you scroll
- 📊 **Animated bar charts** — all bars animate from zero when they enter the viewport
- 🖱️ **Cursor glow** — cyan radial light follows your mouse
- 🃏 **Card hover effects** — lift + glow on hover
- 🎵 **Music player** — floating player with visualizer, progress bar, seek, volume
- 📌 **HUD corner brackets** — every spec card gets sci-fi corner decorators
- ⚡ **Legion logo** — SVG hexagon with pulsing glow, embedded directly in HTML

Zero external dependencies. Zero frameworks. Pure HTML + CSS + Vanilla JS. One file.

---

## 📋 WHAT'S DOCUMENTED

| Section | What's Inside |
|---------|---------------|
| **Machine Overview** | Full model identity, PSREF-accurate specs |
| **CPU Deep Dive** | Zen 3 architecture, CachyOS-specific tuning, thermal limits |
| **GPU Deep Dive** | RTX 3060 full specs, Linux driver reality, DLSS/NVENC/CUDA |
| **Display** | 165Hz setup, Dolby Vision truth, HDR reality on Linux |
| **Platform & I/O** | All ports, HDMI routing, Wi-Fi, audio, RGB control |
| **CachyOS** | OS profile, gaming stack, what works, known limitations |
| **Gaming** | Proton, DLSS, FSR, MangoHud, GameMode, anti-cheat |
| **GPU Modes** | Hybrid vs Discrete vs iGPU-only with practical guidance |
| **Fan Curves** | LLL EC control, 10-point curves, Fn+Q behavior |
| **Battery & Power** | 80Wh runtime estimates, TLP setup, charge limit |
| **Tips & Commands** | Useful CachyOS terminal commands for this hardware |

---

## 🔴 THE DOLBY VISION TRUTH

Your panel has a **Dolby Vision certified display**. Here is the honest answer:

```
Windows:  ✅ True Dolby Vision — full pipeline, Netflix DV, everything
Linux:    ❌ Not supported — no DV driver exists in the Linux ecosystem
```

This is not a CachyOS limitation. It's not a Linux skill issue. It's a **Dolby licensing gap** — Dolby has not released a Linux implementation of the DV decoder pipeline. The panel hardware can physically display it. The signal never gets sent correctly from Linux.

**What you CAN get on Linux:**
- Experimental HDR via KDE Plasma 6 + Wayland
- Per-game HDR via Gamescope (`--hdr-enabled --adaptive-sync` flags)
- Full 165Hz, 100% sRGB, DC dimmer (no PWM flicker), FreeSync

---

## 🔧 GPU MODE CHEAT SHEET

```
BIOS Setting: F2 at boot → Configuration → Graphics Mode
```

```
┌─────────────────────────────────────────────────────────┐
│  DISCRETE MODE    → RTX 3060 drives everything          │
│                   → Max FPS, HDMI works natively        │
│                   → Best for: gaming sessions           │
├─────────────────────────────────────────────────────────┤
│  HYBRID MODE      → iGPU drives internal display        │
│                   → RTX 3060 renders via PRIME          │
│                   → Best for: battery life              │
├─────────────────────────────────────────────────────────┤
│  iGPU ONLY MODE   → RTX 3060 completely powered off     │
│                   → HDMI does NOT work                  │
│                   → Best for: all-day battery / travel  │
└─────────────────────────────────────────────────────────┘

⚠️  HDMI 2.1 is ALWAYS wired to the RTX 3060.
    It does not function when dGPU is off.
```

---

## ⚙️ USEFUL COMMANDS

```bash
# Install LenovoLegionLinux (fan curves, RGB, power modes)
yay -S lenovolegionlinux-git
sudo systemctl enable --now legion-linux-save.service

# Check which GPU is driving the display
glxinfo | grep "OpenGL renderer"

# Monitor temps in real time
watch -n 1 sensors
nvidia-smi dmon -s pucvem

# Best gaming Steam launch options
MANGOHUD=1 gamemoderun %command%

# Gaming with HDR via Gamescope
gamescope --hdr-enabled --adaptive-sync -W 1920 -H 1080 -f -- %command%

# PRIME offload in Hybrid mode
__NV_PRIME_RENDER_OFFLOAD=1 __GLX_VENDOR_LIBRARY_NAME=nvidia gamemoderun %command%

# Verify Resizable BAR is active
dmesg | grep -i rebar

# Set battery charge limit (80% for longevity)
echo 80 | sudo tee /sys/bus/platform/drivers/ideapad_acpi/VPC2004:00/conservation_mode

# Install snapshot tool (safety net before updates)
sudo pacman -S timeshift

# Update everything
sudo pacman -Syu
```

---

## 📁 REPO STRUCTURE

```
Lenovo-Legion-5/
├── index.html       ← The entire site (single file, ~1600 lines)
├── bgmusic.flac     ← Background music for the site
└── README.md        ← You are here
```

---

## 🌐 TECH STACK

```
HTML5        →  Structure
CSS3         →  Animations, glitch effects, scanlines, HUD elements
Vanilla JS   →  Particles, typewriter, scroll reveal, music player
Zero deps    →  No React. No Vue. No Bootstrap. Nothing.
One file     →  The entire site is index.html
```

Fonts loaded from Google Fonts:
- **Bebas Neue** — headings
- **Barlow / Barlow Condensed** — body text
- **JetBrains Mono** — code snippets

---

## 🤝 RESOURCES

| Resource | Link |
|----------|------|
| CachyOS | [cachyos.org](https://cachyos.org) |
| LenovoLegionLinux | [github.com/johnfanv2/LenovoLegionLinux](https://github.com/johnfanv2/LenovoLegionLinux) |
| Arch Wiki | [wiki.archlinux.org](https://wiki.archlinux.org) |
| ProtonDB | [protondb.com](https://protondb.com) |
| CachyOS Forum | [discuss.cachyos.org](https://discuss.cachyos.org) |
| Lenovo PSREF | [psref.lenovo.com](https://psref.lenovo.com) |

---

<div align="center">

---

```
Built on CachyOS · Powered by Zen 3 · Rendered by RTX 3060 · 165Hz · March 2026
```

*If this helped you — star the repo. If it didn't — star it anyway.*

⭐

</div>
