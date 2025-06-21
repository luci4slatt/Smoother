# Smoother.bat – Windows Optimization & Debloat Script

Smoother.bat is a minimalistic and automated batch script designed to optimize Windows 10/11 for gaming, performance, and privacy.  
It applies a series of safe tweaks and system cleanups to deliver a smoother, faster Windows experience, especially on low-end PCs.

---

## Main features

- **Creates a System Restore Point** for safety before making changes
- **Disables unnecessary background apps and services** (Xbox, Telemetry, Cortana, OneDrive, etc.)
- **Sets system visual effects to best performance**
- **Applies registry tweaks** for mouse and keyboard responsiveness, notifications, and transparency
- **Debloats Windows** by removing pre-installed apps except Microsoft Store (with error suppression for stubborn apps)
- **Enables High Performance power plan**
- **Cleans up disk and disables search indexing**
- **Downloads and installs all Visual C++ Redistributables** (2005–2022, x86/x64) using `winget`
- **Downloads and installs Vulkan Runtime** for enhanced graphics support
- **Applies NVIDIA GPU optimizations** (if present)
- **Disables User Account Control (UAC)** for less intrusive admin prompts (optional and not recommended for all users)
- **Waits 5 seconds before closing** so you can review the final status

---

## Usage

For best results and full permissions, run `Smoother.bat` via **PowerRun** (from Sordum) and enable command line mode.  
See the included README for step-by-step instructions.

---

**Created by [luci4slatt]**
Feel free to fork, modify, or suggest improvements!

https://discord.gg/3vnf5enUZC
