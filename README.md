# 🚀 NEXUS GOD MODE - Next-Gen Optimizer v7.0.0

The **ultimate one-button optimization script** for Windows + GameLoop (ADB) + PUBG Mobile.  
Built for **maximum performance** while adding **safety, rollback, and auto-update**.  

---

## ⚡ Features
- **God Mode = All Optimizations**  
  Runs Windows, ADB, and PUBG tweaks in a single flow.
- **Safety Layer**  
  - Creates a System Restore Point before risky changes  
  - Exports registry keys  
  - Saves original power plan and restores on rollback
- **Ultimate Performance**  
  Imports + activates the Ultimate Performance power plan automatically.
- **ADB Tweaks**  
  GPU rendering, EGL hardware accel, frame latency fixes, FPS tweaks, and PUBG DPI settings.
- **Logging & Reports**  
  Every run creates a log in `NEXUS-Backups`.
- **Auto-Update**  
  Always fetches the latest version + changelog from GitHub.
- **Legacy Optimizations Included**  
  (bcdedit, netsh autotuning, thermal disable, registry hacks) — tagged as risky, but still there.

---

## ⚠ Requirements
- **Windows 10 or Windows 11**  
- **PowerShell 5.1+** (built into Windows)  
- **Run as Administrator** — this is **mandatory** for system-level tweaks.

---

## ▶ How to Run
1. [Download the latest release](https://github.com/<YourUser>/NEXUS-GOD-MODE).  
2. Right-click `NEXUS-GOD.ps1` → **Run with PowerShell (Admin)**.  
   - Or open PowerShell as Administrator and run:  
     ```powershell
     Set-ExecutionPolicy Bypass -Scope Process -Force
     .\\NEXUS-GOD.ps1
     ```
3. Choose from the menu:  
   - `[1] Run GOD MODE` — apply all optimizations  
   - `[2] Dry Run` — preview without changes  
   - `[3] Restore` — rollback to pre-optimization state  
   - `[4] Changelog` — view version history  

---

## ⚡ Changelog
See [changelog.md](./changelog.md) for the full history.  

---

## ⚠ Disclaimer
This script applies **system-level modifications**. While it includes **restore points, backups, and rollback hooks**, use at your own risk.  
Always keep your system updated and make sure you understand the tweaks you are applying.  
